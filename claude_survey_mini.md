# Survey: Do You Need Claude Code?

*Anonymous · 4–5 minutes · 14 questions*

> **Design note for the person running this:** every question below feeds a segmentation rule at the end of this document. Nothing is here for colour. If you cut a question, check the scoring table first to see what segment you lose the ability to identify.

---

## Block 1 — Can the tool even reach your work?

**Q1. What is your primary role?**
*Single choice*
- ML engineer
- Data / analytics engineer
- Backend developer
- Frontend / full-stack developer
- Foundry application developer (Workshop, Slate, Ontology)
- DevOps / SRE
- QA / Test engineer
- Architect or engineering manager
- Other

**Q2. In a normal working day, what share of your hands-on-code time is spent in a local IDE or terminal, versus in the Foundry browser environment or another browser tool?**
*Single choice*
- Almost entirely local IDE or terminal — 80–100%
- Mostly local IDE — 60–79%
- Roughly an even split — 40–59%
- Mostly browser — 20–39%
- Almost entirely browser — 0–19%
- I don't write code hands-on in a typical week

**Q3. Is the code you work on in a repository you can clone and run on your own machine?**
*Single choice*
- Yes, all or most of it
- Some of it
- It's technically possible but I never do it
- No — it only exists inside Foundry or another platform
- I don't know

---

## Block 2 — Is your current setup already enough?

**Q4. When you hit a coding problem today, which tool do you reach for first?**
*Single choice*
- GitHub Copilot inline completions
- GitHub Copilot Chat
- Palantir AIP
- Gemini (web)
- Gemini in Workspace
- ChatGPT
- I don't use an AI tool for this

**Q5. What share of your coding problems does that tool solve well enough that you don't go looking elsewhere?**
*Single choice*
- Almost all — 90%+
- Most — 70–89%
- About half — 40–69%
- A minority — 10–39%
- Almost none — under 10%

**Q6. When it isn't enough, what is usually the reason?**
*Multi-select, choose up to 3*
- It only sees the file or snippet I paste, not the whole codebase
- It can't change several files as one coherent piece of work
- It can't run the code, tests or build to check its own output
- It loses the thread on anything that takes more than a few steps
- Too much copy-pasting between the browser and where I work
- The answer is wrong for our stack, libraries or conventions
- It can't reach my work inside Foundry at all
- It's usually enough — I rarely hit a wall

---

## Block 3 — Is your work actually agent-shaped?

**Q7. In a typical week, how many coding tasks do you take on that span several files and take more than an hour?**
*Single choice*
- None
- 1–2
- 3–5
- 6–10
- More than 10

**Q8. How often do you need code written, then run and verified (tests, builds, a script executed) before you'd trust it?**
*Single choice*
- Most tasks
- Often
- Sometimes
- Rarely
- Never — I always verify it myself anyway

---

## Block 4 — Would you actually switch?

**Q9. Which of these do you believe Claude Code can do?**
*Multi-select, choose all you think apply*
- Read and reason across a whole repository, not just an open file
- Create, edit and delete multiple files as one task
- Run terminal commands, tests and builds, and act on the results
- Make a git commit and open a pull request
- Keep working through a long multi-step task without step-by-step instructions
- I'm not sure

**Q10. If you had Claude Code tomorrow, which of your current tools would you use *less*?**
*Multi-select*
- GitHub Copilot inline completions
- GitHub Copilot Chat
- Palantir AIP
- Gemini (web)
- ChatGPT
- None of them — I'd keep my current setup and use Claude Code alongside it
- None of them — I don't think I'd use Claude Code

**Q11. If keeping Claude Code meant giving one of your current tools up, which would you give up?**
*Single choice*
- GitHub Copilot
- Palantir AIP
- Gemini (web)
- ChatGPT
- I wouldn't make that trade — I'd rather keep what I have
- I have no strong preference

**Q12. Suppose there aren't enough licences for everyone at first. Should you be in the first group?**
*Single choice*
- Yes — I'd use it heavily from day one
- Yes, but I could wait a cycle without much cost
- No — someone else would get more out of it than me
- No — my work doesn't really call for it

**Q12b. In one or two lines, why?**
*Short answer, required*

**Q13. How excited are you about Claude Code being introduced?**
*Linear scale, 0 to 10*
- 0 — Not excited at all
- 10 — Extremely excited

---

## Block 5 — Measuring the value

**Q14. If we roll this out, how should we judge whether it was worth it? Pick and rank your top 3.**
*Ranking, choose 3*
- Hours saved per person per week
- Cycle time — from task picked up to pull request merged
- Code quality — fewer bugs reaching production
- Time to get productive on an unfamiliar codebase or pipeline
- Less time spent on toil (boilerplate, tests, documentation)
- Reduced spend on other AI tool licences
- Developer satisfaction and reduced frustration
- Capacity to take on work we'd otherwise drop

**Q15. Anything else we should know before deciding?**
*Long answer, optional*

---

# Reading the results

## Step 1 — Bucket every respondent

Apply these rules in order. First match wins.

| Segment | Rule | What it means |
|---|---|---|
| **Out of reach** | Q2 is 0–19% **and** Q3 is "No" or "technically possible but never" | Claude Code cannot touch their work today. Not a persuasion problem. Excluding them isn't a judgement on them — it's a fact about where their code lives. |
| **Covered** | Q5 is 70%+ **and** Q7 is "None" or "1–2" **and** Q10 includes "I'd keep my current setup" | Their existing tool genuinely does the job. Giving them a seat produces a dormant licence and a bad adoption statistic. |
| **Core** | Q2 is 60%+ **and** Q7 is "3–5" or more **and** Q10 names at least one tool they'd drop | Your wave-one cohort. Real IDE time, real agent-shaped work, and a stated willingness to displace something. |
| **Convertible** | Meets the Core rule on Q2 and Q7, but Q9 has fewer than 3 ticks **or** Q10 says "none" | The work fits; the understanding doesn't yet. These convert with a demo, not a licence. Count them separately and re-survey after training. |
| **Unclear** | Anything else | Read Q12b by hand. It's a small group and the free text usually settles it. |

**Your headline number is the size of Core plus Convertible.** That is the addressable population — not the excitement score.

## Step 2 — The three cross-checks that matter

**Is the incumbent tool actually the constraint?** Cross-tab Q4 against Q5 and Q6. If Copilot users report 90% coverage and rarely tick the first four options in Q6, the case for Claude Code is weak for that group and you should say so rather than discover it after purchase. If they report high coverage but still tick "can't run the code" and "loses the thread," their tool is solving small problems well and they've stopped bringing it big ones — that's suppressed demand, and it reads as satisfaction until you ask Q7.

**Does excitement survive contact with a trade-off?** Compare Q13 against Q11. People scoring 8+ on excitement who then pick "I wouldn't make that trade" are giving you enthusiasm without commitment. The gap between those two numbers is the most honest thing in the survey, and it's the number I'd put in front of whoever signs the budget.

**Is the AIP overlap real?** Among Foundry people, cross Q4 with Q10 and Q11. AIP being the first tool reached for *and* the one nobody will give up means Claude Code is additive spend, not replacement spend, for that cohort. Worth knowing before it's framed to leadership as a consolidation.

## Step 3 — What to report

Four numbers, in this order:

1. **Addressable population** — Core + Convertible, as a headcount, not a percentage
2. **Displacement** — % of Core who named a tool in Q10, and which tool came up most
3. **Coverage gap** — % of all respondents reporting under 70% on Q5
4. **Excitement** — Q13 mean, reported last and explicitly labelled as sentiment rather than demand

With under ~25 responses, use counts rather than percentages throughout. Percentages on a small sample invite people to argue with the sample instead of the finding.
