# Survey: Do You Need Claude Code?

*Anonymous · 5–6 minutes · 19 questions*

> **Design note for the person running this:** every question feeds either the segmentation rules or the measurement plan at the end of this document. Nothing is here for colour. If you cut a question, check those sections first to see what you lose.

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

---

## Block 4 — Would you actually switch?

**Q8. Which of these do you believe Claude Code can do?**
*Multi-select, choose all you think apply*
- Read and reason across a whole repository, not just an open file
- Create, edit and delete multiple files as one task
- Run terminal commands, tests and builds, and act on the results
- Make a git commit and open a pull request
- Keep working through a long multi-step task without step-by-step instructions
- I'm not sure

**Q9. If you had Claude Code tomorrow, which of your current tools would you use *less*?**
*Multi-select*
- GitHub Copilot inline completions
- GitHub Copilot Chat
- Palantir AIP
- Gemini (web)
- ChatGPT
- None of them — I'd keep my current setup and use Claude Code alongside it
- None of them — I don't think I'd use Claude Code

**Q10. If keeping Claude Code meant giving one of your current tools up, which would you give up?**
*Single choice*
- GitHub Copilot
- Palantir AIP
- Gemini (web)
- ChatGPT
- I wouldn't make that trade — I'd rather keep what I have
- I have no strong preference

**Q11. Suppose there aren't enough licences for everyone at first. Should you be in the first group?**
*Single choice*
- Yes — I'd use it heavily from day one
- Yes, but I could wait a cycle without much cost
- No — someone else would get more out of it than me
- No — my work doesn't really call for it

**Q11b. In one or two lines, why?**
*Short answer, required*

**Q12. How excited are you about Claude Code being introduced?**
*Linear scale, 0 to 10*
- 0 — Not excited at all
- 10 — Extremely excited

---

## Block 5 — Measuring the value of the switch

> This block decides what "it worked" means. Answer it as if you'll be held to it, because the results will be used to set the success criteria before rollout, not after.

**Q13. How should we judge whether moving from GitHub Copilot to Claude Code was worth it? Pick and rank your top 3.**
*Ranking, choose 3*
- Hours saved per person per week
- Cycle time — from task picked up to pull request merged
- Share of large tasks (multi-file, over an hour) that get AI help at all
- Tasks completed end-to-end without me having to take over halfway
- Code quality — fewer bugs and less rework reaching production
- Pull request review turnaround
- Time to get productive on an unfamiliar codebase or pipeline
- Less time spent on toil (boilerplate, tests, documentation)
- Net licence spend — what we retire versus what we add
- Developer satisfaction and reduced frustration

**Q14. How much better than your current Copilot setup would it need to be for you to call the switch a success?**
*Single choice*
- Any measurable improvement is enough
- Roughly 10% faster on the work it touches
- Roughly 25% faster
- Roughly 50% faster
- Speed isn't the test — it needs to let me do things I can't practically do today
- I don't think this is measurable in a meaningful way

**Q15. Where should the "before" number come from?**
*Multi-select*
- Git and pull request history from the last three months
- Sprint or ticket data from recent sprints
- A short time diary I'd be willing to keep for two weeks before the switch
- A set of representative tasks we time before and after
- A one-off estimate from each person
- We shouldn't try to baseline — judge it qualitatively after 90 days

**Q16. What would be the fairest way to compare Claude Code against the Copilot setup?**
*Single choice*
- Split the team — some keep Copilot for a period, then compare the groups
- Same person, before and after, on similar work
- Same task done both ways by different people, then compared
- A fixed set of benchmark tasks re-run each quarter
- Just ask people at the end — a controlled comparison isn't worth the effort

**Q17. What would make you say we should go back to Copilot?**
*Multi-select*
- It produces more bugs or rework than it saves
- It's slower for the small, quick edits that make up most of my day
- Losing inline completions costs me more than the agent gains me
- It can't reach my work (Foundry, restricted repositories)
- Review load goes up because the changes it makes are bigger
- Cost per person ends up higher without matching output
- I'd need to see it fail on real work before saying that
- Nothing — I'd want to stick with it regardless

**Q18. How should the results be shown to the team?**
*Single choice*
- A dashboard we can check any time
- A monthly one-page summary with the numbers
- A before-and-after walkthrough of a few real tasks
- A short internal demo comparing both tools on the same task
- Discussed in sprint retro
- I don't need to see it

**Q19. Three months in, what would make you personally say the switch was worth it?**
*Long answer*

---

# Reading the results

## Step 0 — Do this before anyone gets a licence

Pull the git and pull request baseline now: cycle time, PR size, merge rate, review turnaround, for the last three months. Once the first licence is issued, the before-number is gone and every later claim about value becomes an argument about memory. This survey is the last quiet moment you'll have to capture it.

## Step 1 — Bucket every respondent

Apply these rules in order. First match wins.

| Segment | Rule | What it means |
|---|---|---|
| **Out of reach** | Q2 is 0–19% **and** Q3 is "No" or "technically possible but never" | Claude Code cannot touch their work today. Not a persuasion problem. Excluding them isn't a judgement on them — it's a fact about where their code lives. |
| **Covered** | Q5 is 70%+ **and** Q7 is "None" or "1–2" **and** Q9 includes "I'd keep my current setup" | Their existing tool genuinely does the job. A seat here produces a dormant licence and a bad adoption statistic. |
| **Core** | Q2 is 60%+ **and** Q7 is "3–5" or more **and** Q9 names at least one tool they'd drop | Your wave-one cohort. Real IDE time, agent-shaped work, and stated willingness to displace something. |
| **Convertible** | Meets Core on Q2 and Q7, but Q8 has fewer than 3 ticks **or** Q9 says "none" | The work fits; the understanding doesn't yet. These convert with a demo, not a licence. |
| **Unclear** | Anything else | Read Q11b by hand. Small group, and the free text usually settles it. |

**Your headline number is Core plus Convertible.** That is the addressable population — not the excitement score.

## Step 2 — Build the measurement plan from Block 5

The survey doesn't just tell you who wants the tool; it tells you what evidence this specific team will accept. Use it that way.

- **Q13 sets the metrics.** Take the aggregate top 3 and freeze them. Publish them before rollout. The most common way a rollout gets judged unfairly is that success quietly gets redefined at review time by whoever is least happy with it.
- **Q14 sets the bar.** Take the median answer, not the mean — one person answering "50% faster" shouldn't drag the threshold up for everyone. If a large share pick "speed isn't the test," your measurement plan should be built around *new work now possible* rather than *same work done faster*, and hours-saved will be the wrong headline no matter how tidy it looks in a slide.
- **Q15 tells you what instrumentation people will actually cooperate with.** A time diary only works if people volunteer for it. If few pick it, don't build a plan that depends on it.
- **Q16 decides the design.** If a meaningful group picks the split-team option, take it — a held-back Copilot group is the only method here that separates the tool's effect from everything else changing that quarter. If nobody will accept the disruption, fall back to before-and-after on the same people and be honest in the write-up that attribution is weaker.
- **Q17 gives you kill criteria, agreed in advance.** Write these into the rollout plan. A team that has pre-committed to what failure looks like argues far less about whether it happened, and it protects you too: if none of the stated failure conditions occur, "it doesn't feel faster" is not a finding.
- **Q18 decides the format.** Note that the two demo-style options serve a different purpose from the numeric ones — engineers are usually convinced by seeing a real task run both ways, while budget holders want the aggregate. You'll likely need one of each.

## Step 3 — The three cross-checks

**Is the incumbent actually the constraint?** Cross-tab Q4 against Q5 and Q6. High coverage plus few structural complaints means the case is weak for that group — better to know now than after purchase. High coverage alongside "can't run the code" and "loses the thread" is different: their tool handles small problems well and they've stopped bringing it big ones. That's suppressed demand, and it reads as satisfaction until you look at Q7.

**Does excitement survive a trade-off?** Compare Q12 against Q10. People scoring 8+ who then pick "I wouldn't make that trade" are offering enthusiasm without commitment. The gap between those two is the most honest number in the survey, and it's the one to put in front of whoever signs the budget.

**Is the AIP overlap real?** Among Foundry people, cross Q4 with Q9 and Q10. AIP being both the first tool reached for and the one nobody will give up means Claude Code is additive spend for that cohort, not replacement spend. Worth establishing before it's framed upward as a consolidation.

With under ~25 responses, use counts rather than percentages throughout. Percentages on a small sample invite people to argue with the sample instead of the finding.
