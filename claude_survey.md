# Survey: Claude Code Rollout — Team Readiness Check

*Anonymous · ~6 minutes · 26 questions, with branching so people outside Foundry see about 19*

---

## Section A — About You and Where You Work

**Q1. What is your primary role?**
*Single choice*
- ML engineer
- Data / analytics engineer (pipelines, transforms, models)
- Backend developer
- Frontend developer
- Full-stack developer
- Foundry application developer (Workshop, Slate, Ontology)
- DevOps / SRE
- QA / Test engineer
- Architect
- Engineering manager
- Other

**Q2. Which AI tools do you actually use in a normal work week?**
*Multi-select*
- GitHub Copilot (inline code completions)
- GitHub Copilot Chat
- ChatGPT
- Web Gemini
- Gemini in Google Workspace (Docs, Sheets, Gmail)
- Palantir AIP (AIP Assist, AIP Logic, Agent Studio)
- None of these

**Q3. Where does your hands-on build work actually happen in a normal week?**
*Multi-select*
- Palantir Foundry — Code Repositories
- Palantir Foundry — Code Workspaces (browser Jupyter / VS Code)
- Palantir Foundry — Pipeline Builder or other low-code transforms
- Palantir Foundry — Workshop or Slate (app building)
- Palantir Foundry — model training, evaluation or deployment
- Local IDE on my own machine (VS Code, IntelliJ, PyCharm, etc.)
- Terminal / command line
- Git repositories outside Foundry
- CI/CD config and infrastructure-as-code
- Other

**Q4. In a normal working day, roughly what share of your hands-on-code time is spent in a local IDE or terminal, versus in the Foundry browser environment?**
*Single choice*
- Almost entirely local IDE or terminal — 80–100%
- Mostly local IDE — 60–79%
- Roughly an even split — 40–59%
- Mostly Foundry in the browser — 20–39%
- Almost entirely Foundry in the browser — 0–19%
- I don't write code hands-on in a typical week

**Q5. Do you currently have a way to work on your Foundry code from a local machine?**
*Single choice*
- Yes, I clone and work locally regularly
- Yes, it's possible but I rarely do it
- I've tried and it didn't work well
- No, everything I do stays in the browser
- I don't know whether this is possible

---

## Section B — Your Current Setup

**Q6. How often do you use an AI assistant for coding work?**
*Single choice*
- Multiple times a day
- About once a day
- A few times a week
- A few times a month
- Rarely or never

**Q7. How satisfied are you with the current GitHub Copilot + ChatGPT setup?**
*Linear scale, 1 to 5*
- 1 — Very dissatisfied
- 2 — Dissatisfied
- 3 — Neutral
- 4 — Satisfied
- 5 — Very satisfied

**Q8. Where does the current setup fall short most for you?**
*Multi-select, choose up to 3*
- It doesn't understand our repository or codebase context
- It can't edit multiple files in one go
- It can't run or test the code it writes
- Its answers are outdated or wrong for our stack
- Too much copy-pasting between the browser and my IDE
- Weak at debugging
- Weak at working with legacy code
- It can't reach my work inside Foundry at all
- Nothing major — it works fine for me

---

## Section C — Foundry and AIP

> **Show this section only if any Foundry option was selected in Q2 or Q3.**

**Q9. What kind of work do you do in Foundry?**
*Multi-select*
- Exploratory analysis and experimentation in notebooks
- Feature engineering and data transforms
- Writing model training code
- Model evaluation and comparison
- Model deployment and monitoring
- Building Workshop or Slate applications
- Ontology modelling and object definitions
- Low-code pipeline work

**Q10. How often do you use Palantir AIP?**
*Single choice*
- Daily
- A few times a week
- Occasionally
- I have access but rarely use it
- No access, or I wasn't aware of it

**Q11. What do you use AIP for?**
*Multi-select*
- AIP Assist — asking how to do something in Foundry itself
- Generating, explaining or fixing code inside Code Repositories or Code Workspaces
- AIP Logic — building LLM-backed logic and functions
- Agent Studio — building agents for end users
- Ontology-aware queries and analysis
- Drafting transforms or pipeline logic
- I don't use AIP

**Q12. When you have a coding task inside Foundry, how likely are you to leave Foundry and do that work in an IDE with Claude Code instead?**
*Single choice*
- Very likely — I'd rather work in an IDE whenever I can
- Likely for larger tasks, but I'd stay in Foundry for small edits
- Only for work that doesn't touch Ontology objects or platform data
- Unlikely — my Foundry work realistically can't leave the platform
- I don't know yet

**Q13. Of the coding work you currently do inside Foundry, what share do you think you would move to Claude Code if it were available to you?**
*Single choice*
- 0% — none of it, it has to stay in Foundry
- 1–10%
- 11–25%
- 26–50%
- 51–75%
- 76–100% — nearly all of it
- I can't judge until I've tried it

**Q14. What would stop you moving that work out of Foundry?**
*Multi-select*
- Ontology objects and datasets can't leave the Foundry environment
- My Foundry code isn't easy to work on from a local machine
- Security or compliance approval would be required
- My work is notebook-driven and doesn't map cleanly to a local repo
- The code depends on Foundry-specific APIs and libraries
- AIP already understands our Ontology; an outside tool wouldn't
- Switching between two tools costs more than it saves
- My Foundry work is mostly low-code, not writing code
- Nothing major — I'd switch happily
- Not sure

**Q15. Where does AIP serve you better than a general coding assistant, and where does it fall short?**
*Long answer, optional*

---

## Section D — Claude Code

**Q16. How excited are you about Claude Code being introduced?**
*Linear scale, 0 to 10*
- 0 — Not excited at all
- 10 — Extremely excited

**Q17. Before this survey, how much did you know about Claude Code?**
*Single choice*
- I had never heard of it
- I had heard the name only
- I know roughly what it does
- I have read about it in detail
- I have used it myself

**Q18. Which of the following do you believe Claude Code can do?**
*Multi-select, choose all you think apply*
- Read and reason across an entire repository
- Create, edit and delete multiple files in a single task
- Run terminal commands, tests and builds
- Make a git commit and open a pull request
- Work from the terminal, an IDE, or a desktop app
- Keep working through a long multi-step task without step-by-step instructions
- I'm not sure

**Q19. Compared with pasting code into Web Gemini, ChatGPT or AIP Assist, how much difference do you expect from an agent that works directly inside your repository?**
*Single choice*
- No real difference
- Slightly better
- Noticeably better
- Significantly better
- I don't know enough to say

**Q20. How likely are you to use Claude Code for real work in your first month of access?**
*Single choice*
- Definitely will
- Probably will
- Not sure
- Probably won't
- Definitely won't — my work doesn't happen in an IDE

---

## Section E — If Access Went Away

**Q21. If all AI coding assistants were removed tomorrow, how would your weekly output change?**
*Single choice*
- No change
- Down slightly — less than 10%
- Down noticeably — 10 to 25%
- Down a lot — 25 to 50%
- Down severely — more than 50%

**Q22. If your access were limited or removed, what would you most likely do?**
*Single choice*
- Use my personal AI account for work tasks
- Fall back to AIP inside Foundry
- Go back to Stack Overflow and official documentation
- Ask teammates more often
- Just work slower
- Nothing would change for me

---

## Section F — Measuring the Value

**Q23. In a typical week, roughly how many hours do you spend on work you believe a coding agent could largely handle?**
*Single choice*
- Under 1 hour
- 1–3 hours
- 3–5 hours
- 5–10 hours
- More than 10 hours
- Hard to say

**Q24. How should we judge whether Claude Code is worth the investment? Pick and rank your top 3.**
*Ranking, choose 3*
- Hours saved per person per week
- Cycle time — from ticket picked up to pull request merged
- Throughput — tickets or story points closed per sprint
- Code quality — fewer bugs reaching production
- Pull request review turnaround time
- Time to get productive on an unfamiliar codebase or pipeline
- Less time spent on toil (boilerplate, tests, documentation)
- Reduced spend on other AI tool licences
- Developer satisfaction and reduced frustration
- Capacity to take on work we'd otherwise drop or outsource

**Q25. How would you like results reported back to the team?**
*Single choice*
- Monthly metrics email
- A dashboard we can check any time
- Discussed in sprint retro
- Quarterly review only
- I don't need to see it

---

## Section G — In Your Own Words

**Q26. Three months from now, what would make you personally say this was worth it?**
*Long answer*

**Q27. What worries you about the switch?**
*Long answer, optional*

---

## Notes for Whoever Runs This

- **Set up the branching on Section C.** Most respondents will see it, but people working entirely outside Foundry shouldn't.
- **Turn off "collect email addresses"** so Q22 (the shadow-IT question) gets honest answers.
- **Run it before the announcement email**, so it captures baseline sentiment rather than a reaction to the pitch.
- **Keep Q1, Q3, Q4 and Q5** — they carry almost all the cross-tab value.
- If you need to cut for length, Q25 is the least load-bearing question in the set.

### The analysis that matters most

Plot **Q16 (excitement)** against **Q4 (IDE time)**. That two-by-two is the whole seat-allocation decision:

| | High IDE time | Low IDE time (Foundry-heavy) |
|---|---|---|
| **High excitement** | Your pilot cohort. Give them access first and let them generate the internal proof. | Genuinely enthusiastic but the tool may not reach their work. Give them browser-based Claude rather than a Claude Code seat, or they'll churn and the churn will look like a product failure. |
| **Low excitement** | A training problem, not a sentiment problem. Cross-check against Q17 and Q18 — awareness is usually the cause. | Don't buy them a Claude Code seat in wave one. Revisit once Q13 and Q14 tell you how much Foundry work could realistically move. |

Because ML engineering here happens only in Foundry, expect the ML cohort to land in the right-hand column. If it does, that isn't a failure of the survey or of enthusiasm — it's a structural finding, and it's arguably the most valuable thing this survey will tell you. Read it alongside Q5 and Q14: whether the answer is "unreachable for now" or "reachable once we sort out local checkout" depends entirely on whether people are blocked by data residency or merely by tooling.

### Scoring guide

| Metric | Derived from | What it tells you |
|---|---|---|
| Excitement score | Q16 mean, plus % scoring 8+ | Overall enthusiasm (NPS-style: 9–10 promoters, 7–8 passive, 0–6 detractors) |
| Awareness gap | % of Q18 respondents ticking fewer than 3 capabilities | Whether low excitement is really a training problem |
| Addressable population | % of Q4 answering 60%+ IDE time | How many seats are actually worth buying in wave one |
| Reachability | Q5 crossed with Q14 | Whether the Foundry cohort is blocked by policy or by tooling — two very different fixes |
| Foundry displacement | Q13 median band, split by Q9 work type | How much Foundry work realistically moves. Expect model-training and transform code to score higher than notebook experimentation and low-code work |
| Dependency | % of Q21 answering 25%+ output drop | The business case for the rollout |
| Leakage risk | % of Q22 choosing "personal AI account" | Shadow-IT and data-security exposure — flag anything above 10% |
| Expected value | Q23 median band × headcount | Your baseline. Re-ask Q23 at 90 days and the delta is your ROI number |
| Success definition | Q24 top-3 aggregate | Lock these in as the metrics *before* rollout, so nobody redefines success afterwards |

Two cautions. With fewer than ~25 responses, report raw counts ("14 of 22 people") rather than percentages — percentages on a small sample invite people to argue with the sample instead of the finding. And Q23 is self-reported, so treat it as an expectation to test rather than a measurement; its real value is as a before-number to compare against the same question asked again in 90 days.
