Compact embedding models (good accuracy-per-MB):
BGE-small (BAAI/bge-small-en-v1.5) — 384-dim, ~130MB, strong retrieval quality
all-MiniLM-L6-v2 — 384-dim, ~90MB, very fast, decent quality
GTE-small / E5-small-v2 — similar footprint, competitive on MTEB
Nomic Embed / OpenAI text-embedding-3-small — support Matryoshka Representation Learning (MRL), so you can truncate to 256 or even 128 dims with minimal quality loss
Dimensionality reduction techniques:
Matryoshka truncation — if the model was MRL-trained, just slice the vector (e.g., 1536→256); cheapest option, no retraining
PCA — fit on a sample of your embeddings, project down; works on any model but loses some semantic structure
Random projection (JL lemma) — near-zero compute cost, decent for large-scale approximate retrieval
Product Quantization (PQ / OPQ) — splits vector into subvectors, quantizes each via codebooks; big compression (often 8-16x), small recall hit
Storage/energy optimization at the vector DB layer:
Scalar quantization (int8) — 4x memory reduction, minimal accuracy loss; supported natively in Qdrant, Milvus, pgvector
Binary quantization — 32x reduction (1 bit/dim), works well combined with a rerank pass on the top-k candidates; Qdrant and Weaviate both support this now
HNSW + PQ (FAISS IVF-PQ) — good for very large indexes where full-precision HNSW won't fit in RAM
Practical combo for max savings: MRL-truncated small embedding (e.g., 256-dim) → int8 or binary quantization in the vector DB → rerank top ~50 candidates with full precision if you need accuracy back. That stack typically gets you 90%+ of full-precision recall at a fraction of the memory and query energy cost.
If you tell me which vector DB you're targeting (pgvector, Qdrant, Milvus, OpenSearch) I can get more specific on the quantization config.
