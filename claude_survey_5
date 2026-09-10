# AI Tooling Survey — Claude Code, Gemini and AIP

*Anonymous · Technical path ~7 minutes · Functional path ~3 minutes*

**Purpose:** to size how much Claude Code will actually be used once it replaces GitHub Copilot, and how that usage will sit alongside Gemini and Palantir AIP — so we can budget seats on evidence rather than on enthusiasm.

---

## Google Forms setup

- Build this as **8 sections** with "Go to section based on answer" branching on Q1.
- Q7 and Q20 are **Multiple choice grid** questions (rows = tools, columns = bands).
- Turn **off** "Collect email addresses". Several questions only work if people answer honestly.
- Mark Q2, Q4 and all long-answer questions as optional; everything else required.

---

# SECTION 1 — Screener

**Q1. Which best describes your role?**
*Single choice — this determines the rest of the form*
- **Technical** — I write code, scripts or infrastructure configuration hands-on in a normal week → *go to Section 2*
- **Techno-functional** — I mostly do analysis, design or solutioning, but I write queries, scripts or configuration sometimes → *go to Section 2*
- **Functional / delivery** — I don't write code (Scrum Master, Product Owner, Project Manager, Functional Analyst, Business Analyst) → *go to Section 7*

**Q2. What is your job title?**
*Short answer, optional*

---

# SECTION 2 — About you and your stack

**Q3. Which technologies do you work with in a normal month?**
*Multi-select*
- Java
- Python
- JavaScript / TypeScript
- C / C++
- C# / .NET
- SQL and databases
- Shell / Bash scripting
- Palantir Foundry — code (PySpark, TypeScript functions, transforms)
- Palantir Foundry — low-code (Workshop, Slate, Pipeline Builder, Ontology)
- Terraform, Ansible or other infrastructure-as-code
- Docker, Kubernetes, container platforms
- CI/CD pipelines
- MATLAB / Simulink
- Test automation frameworks
- Other

**Q4. How many years have you been writing code professionally?**
*Single choice*
- I don't write code as part of my job
- Under 2 years
- 2–5 years
- 6–10 years
- 11–15 years
- More than 15 years

---

# SECTION 3 — Where your work actually happens

**Q5. Where do you do your hands-on work in a normal week?**
*Multi-select*
- Local IDE on my machine (VS Code, IntelliJ, PyCharm, Eclipse, etc.)
- Terminal / command line
- Palantir Foundry — Code Repositories
- Palantir Foundry — Code Workspaces (browser Jupyter / VS Code)
- Palantir Foundry — Workshop, Slate, Pipeline Builder or Ontology
- Jupyter or other notebooks outside Foundry
- A cloud console (AWS, Azure, GCP)
- Another browser-based platform or internal web tool
- Mostly documents, tickets and meetings

**Q6. In a normal working day, what share of your hands-on time is spent in a local IDE or terminal, versus in a browser-based tool?**
*Single choice*
- Almost entirely local IDE or terminal — 80–100%
- Mostly local IDE — 60–79%
- Roughly an even split — 40–59%
- Mostly browser-based — 20–39%
- Almost entirely browser-based — 0–19%

> **This is the single most predictive question in the survey.** Claude Code runs in an IDE and terminal. Someone at 0–19% will get little from it regardless of how enthusiastic they are, and someone at 80–100% will get a lot even if they're sceptical today.

---

# SECTION 4 — What you use today

**Q7. How often do you use each of these today?**
*Multiple choice grid*

| | Daily | A few times a week | A few times a month | Rarely | Never / no access |
|---|---|---|---|---|---|
| GitHub Copilot — inline completions | | | | | |
| GitHub Copilot — Chat | | | | | |
| Gemini (web) | | | | | |
| Gemini in Workspace (Docs, Sheets, Gmail) | | | | | |
| Palantir AIP | | | | | |

**Q8. What do you mainly use Gemini for?**
*Multi-select*
- Explaining code or concepts
- Generating snippets I then paste into my editor
- Debugging help
- Writing documentation or comments
- Analysis, research and general questions
- Emails, documents and meeting notes
- Test data or test case ideas
- I don't really use Gemini

**Q9. Thinking about GitHub Copilot: what share of your coding problems does it handle well enough that you don't look elsewhere?**
*Single choice*
- Almost all — 90%+
- Most — 70–89%
- About half — 40–69%
- A minority — 10–39%
- Almost none — under 10%
- I don't use Copilot

**Q10. When your current AI tools aren't enough, what is usually the reason?**
*Multi-select, choose up to 3*
- They only see the file or snippet I paste, not the whole codebase
- They can't change several files as one coherent piece of work
- They can't run the code, tests or build to check their own output
- They lose the thread on anything longer than a few steps
- Too much copy-pasting between browser and editor
- The answer is wrong for our stack, libraries or conventions
- They can't reach my work inside Foundry
- They're usually enough — I rarely hit a wall

**Q11. In a typical week, how many tasks do you take on that span several files and take more than an hour?**
*Single choice*
- None
- 1–2
- 3–5
- 6–10
- More than 10

---

# SECTION 5 — Foundry and AIP

> **Branching: show this section only if any Foundry option was selected in Q3 or Q5. Otherwise skip to Section 6.**

**Q12. What do you use AIP for?**
*Multi-select*
- AIP Assist — asking how to do something in Foundry itself
- Generating, explaining or fixing code inside Code Repositories or Code Workspaces
- AIP Logic — building LLM-backed logic and functions
- Agent Studio — building agents for end users
- Ontology-aware queries and analysis
- Drafting transforms or pipeline logic
- I have access but don't really use it
- I don't have AIP access

**Q13. Is the Foundry code you work on something you could clone and run on your own machine?**
*Single choice*
- Yes, all or most of it
- Some of it
- Technically possible, but I never do it
- No — it only works inside Foundry
- I don't know

**Q14. Of the work you currently do inside Foundry, what share could realistically move to an IDE with Claude Code?**
*Single choice*
- 0% — none of it, it has to stay in Foundry
- 1–25%
- 26–50%
- 51–75%
- 76–100%
- I can't judge until I've tried it

**Q15. What would stop that work moving out of Foundry?**
*Multi-select*
- Ontology objects and datasets can't leave the platform
- The code isn't easy to work on locally
- Security or compliance approval would be needed
- My work is notebook-driven and doesn't map to a local repo
- It depends on Foundry-specific APIs and libraries
- AIP already understands our Ontology; an outside tool wouldn't
- My Foundry work is mostly low-code, not writing code
- Nothing major — I'd move it happily

---

# SECTION 6 — Claude Code, and how you'd split your usage

**Q16. Before this survey, how much did you know about Claude Code?**
*Single choice*
- Never heard of it
- Heard the name only
- Know roughly what it does
- Read about it in detail
- Have used it myself

**Q17. Which of these do you believe Claude Code can do?**
*Multi-select*
- Read and reason across a whole repository, not just an open file
- Create, edit and delete multiple files as one task
- Run terminal commands, tests and builds, and act on the results
- Make a git commit and open a pull request
- Keep working through a long multi-step task without step-by-step instructions
- I'm not sure

**Q18. How excited are you about Claude Code being introduced?**
*Linear scale, 0 to 10 — 0 is not at all, 10 is extremely*

**Q19. Why that score?**
*Short answer, required*

**Q20. Six months from now, assume you have Claude Code in your IDE, Gemini on the web and in Workspace, and AIP if you work in Foundry. Across all the work where you'd use AI, how would your usage split?**
*Multiple choice grid — your answers should roughly add up to 100%*

| | 0% | 1–25% | 26–50% | 51–75% | 76–100% |
|---|---|---|---|---|---|
| Claude Code (IDE / terminal) | | | | | |
| Gemini (web) | | | | | |
| Gemini in Workspace | | | | | |
| Palantir AIP | | | | | |
| No AI — I'd do it myself | | | | | |

**Q21. Which one would be your main tool?**
*Single choice*
- Claude Code
- Gemini (web)
- Gemini in Workspace
- Palantir AIP
- None — I'd mostly work without AI
- Too early to say

**Q22. Realistically, how many days a week would you open Claude Code?**
*Single choice*
- 5 — every working day
- 3–4 days
- 1–2 days
- Less than once a week
- Never — my work doesn't happen in an IDE

**Q23. If Claude Code were *not* available to you, where would that work go instead?**
*Single choice*
- Gemini would cover it fine
- AIP would cover it fine
- Copilot covered it fine and I'd rather keep Copilot
- I'd do it manually and it would take longer
- I'd struggle — nothing else covers it
- No impact — I wasn't going to use it much anyway

> **Q23 is the budget question.** Q20 and Q22 tell you what people expect to do; Q23 tells you what happens if they don't get a seat. A seat is easy to justify for anyone answering "I'd struggle" and hard to justify for anyone answering "Gemini would cover it fine."

**Q24. Replacing Copilot means giving something up. What must Claude Code do at least as well for that to be acceptable to you?**
*Multi-select, choose up to 3*
- Inline suggestions as I type
- Speed on small, quick suggestions
- IDE integration that doesn't disrupt how I work
- Matching our code style and conventions
- Covering all the languages and frameworks I use
- Enterprise controls — data handling, audit, access
- Working on restricted networks
- Nothing — I barely use Copilot's completions anyway

**→ Now go to Section 8.**

---

# SECTION 7 — For functional and delivery roles

> **Branching: only people who selected "Functional / delivery" on Q1 see this section.**

**Q25. How often do you use each of these today?**
*Multiple choice grid*

| | Daily | A few times a week | A few times a month | Rarely | Never / no access |
|---|---|---|---|---|---|
| Gemini (web) | | | | | |
| Gemini in Workspace (Docs, Sheets, Gmail) | | | | | |
| Palantir AIP | | | | | |

**Q26. What do you use AI for in your role?**
*Multi-select*
- Writing and editing documents
- Summarising meetings, threads or reports
- Drafting user stories, acceptance criteria or requirements
- Analysing data or building spreadsheets
- Preparing status reports and presentations
- Understanding technical work well enough to discuss it
- Research and background reading
- I don't really use AI at work

**Q27. Claude Code is a developer tool — it runs in an IDE or terminal and is aimed at people writing code. Do you expect it to affect your work?**
*Single choice*
- Yes, directly — I do enough hands-on technical work to use it myself
- Yes, indirectly — it should change what my team can deliver
- Only in how I plan or estimate work
- No, I don't expect it to affect me
- Not sure

**Q28. How excited are you about Claude Code being introduced to your team?**
*Linear scale, 0 to 10*

**Q29. From a delivery point of view, what would make this rollout a success?**
*Long answer*

**Q30. What concerns you about it?**
*Long answer, optional*

**→ Now go to Section 8.**

---

# SECTION 8 — How we'll know it was worth it

> **Everyone sees this section.**

**Q31. When judging whether Claude Code was worth the investment, what would you compare it against?**
*Multi-select*
- GitHub Copilot as it works for us today
- Gemini
- Palantir AIP
- How we worked before we had any AI tools at all
- An external benchmark or industry figures
- Not sure

**Q32. How would you capture and show that value? What would you measure, who would collect it, and how often?**
*Long answer, required*

> Leave this genuinely open. The specific measures people reach for unprompted — and whether they reach for hard data or for judgement — tells you more about what the team will accept as proof than any list of options would.

**Q33. If you had to pick just three measures, which would they be?**
*Ranking, choose 3*
- Hours saved per person per week
- Cycle time — from task picked up to pull request merged
- Throughput — tasks or stories completed per sprint
- Code quality — fewer bugs and less rework reaching production
- Pull request review turnaround
- Time to get productive on an unfamiliar codebase or pipeline
- Less time spent on toil (boilerplate, tests, documentation)
- Total AI tool spend per person compared with today
- Team satisfaction and reduced frustration
- Capacity to take on work we'd otherwise drop or defer

**Q34. Ninety days after rollout, what would tell you this *isn't* working?**
*Multi-select, choose up to 3*
- Fewer than half the licences being used in a normal week
- No measurable time saving compared with before
- More time spent reviewing and fixing its output than it saved
- Quality or defect rates getting worse
- A security, compliance or data-handling problem
- People quietly going back to Gemini or AIP
- Cost per person outrunning the benefit
- Nothing at 90 days — I'd give it longer

**Q35. Anything else we should know before deciding?**
*Long answer, optional*

---

# Reading the results

## Turning Q20 into a budget number

The grid gives bands, not numbers. Convert with midpoints — 0%, 13%, 38%, 63%, 88% — then normalise each person's row so it sums to 100. Average across respondents and you have a fleet-level distribution: *"Claude Code 41%, Gemini 28%, AIP 19%, no AI 12%."* That is the sentence your budget conversation needs.

Then discount it. Stated future preference reliably overstates the new tool — people imagine using it more than they will. Treat Q20 as a ceiling and Q23 as the floor, and put your seat count between the two, closer to Q23.

## Sizing seats

| Tier | Rule | Action |
|---|---|---|
| **Definite seat** | Q6 is 60%+ IDE **and** Q22 is 3+ days **and** Q23 is "I'd struggle" or "manual and slower" | Wave one. High IDE time, high stated frequency, no substitute. |
| **Probable seat** | Q6 is 60%+ IDE **and** Q22 is 1–2 days or more, but Q23 names a substitute | Wave two. Real usage but a fallback exists — worth a seat once wave one proves out. |
| **Convert first** | Q6 is 60%+ IDE **and** Q11 is 3+, but Q17 has fewer than three ticks | The work fits, the understanding doesn't. A demo converts these, not a licence. Re-ask Q22 after. |
| **No seat yet** | Q6 is under 40% **or** Q22 is "never" / "less than once a week" | Foundry-heavy and low-code-heavy people mostly land here. Not a judgement on them — AIP and Gemini are staying and genuinely cover them. |

## Four cross-checks

**Does excitement survive a trade-off?** Compare Q18 against Q23. People scoring 8+ who then say "Gemini would cover it fine" are giving you enthusiasm without demand. That gap is the most honest number in the survey and the one I'd show whoever signs the budget.

**Is low excitement really low awareness?** Cross Q18 against Q16 and Q17. If the two track closely — and they usually do — then adoption is a training problem, not a sentiment problem, and the fix is a demo rather than a different tool.

**Is the Foundry cohort reachable at all?** Cross Q13 with Q14 and Q15. "Can't clone locally" plus "0% could move" is a structural finding, not a soft one, and it means the ML population is served by AIP for now. Worth stating plainly in the report rather than leaving as an implication.

**Read Q19 and Q32 by hand.** Q19 explains every excitement score — a 4 because "I've never seen it" and a 4 because "Copilot already does this for me" mean opposite things and lead to opposite actions. Q32 tells you what proof the team will accept, which matters more than what proof you'd prefer to give them.

## Report in this order

1. **Seat count** — Definite + Probable, as a headcount with the tier rules shown
2. **Usage distribution** — the normalised Q20 split, labelled as stated intent
3. **Substitution** — the Q23 breakdown, labelled as the conservative floor
4. **Success charter** — top 3 from Q33 plus top 2 from Q34, agreed before rollout, so nobody redefines success afterwards
5. **Excitement** — Q18 mean, last, explicitly labelled as sentiment rather than demand

With under ~25 responses in any segment, report counts ("14 of 22 developers") rather than percentages. Percentages on a small sample invite people to argue with the sample instead of the finding.
