# Survey: Claude Code Rollout — Team Readiness Check

*Anonymous · ~5 minutes · 15 questions + 2 open*

---

## Section A — About You

**Q1. What is your primary role?**
*Single choice*
- Backend developer
- Frontend developer
- Full-stack developer
- Data / ML engineer
- DevOps / SRE
- QA / Test engineer
- Architect
- Engineering manager
- Other

**Q2. How many years have you been writing code professionally?**
*Single choice*
- 0–2 years
- 3–5 years
- 6–10 years
- 11–15 years
- 16 years or more

**Q3. Which AI tools do you actually use in a normal work week?**
*Multi-select*
- GitHub Copilot (inline code completions)
- GitHub Copilot Chat
- ChatGPT
- Web Gemini
- Gemini in Google Workspace (Docs, Sheets, Gmail)
- None of these

---

## Section B — Your Current Setup

**Q4. How often do you use an AI assistant for coding work?**
*Single choice*
- Multiple times a day
- About once a day
- A few times a week
- A few times a month
- Rarely or never

**Q5. Roughly what share of the code you ship in a week is AI-assisted (generated, completed, or refactored)?**
*Single choice*
- 0%
- 1–10%
- 11–25%
- 26–50%
- 51–75%
- More than 75%

**Q6. How satisfied are you with the current GitHub Copilot + ChatGPT setup?**
*Linear scale, 1 to 5*
- 1 — Very dissatisfied
- 2 — Dissatisfied
- 3 — Neutral
- 4 — Satisfied
- 5 — Very satisfied

**Q7. Where does the current setup fall short most for you?**
*Multi-select, choose up to 3*
- It doesn't understand our repository or codebase context
- It can't edit multiple files in one go
- It can't run or test the code it writes
- Its answers are outdated or wrong for our stack
- Too much copy-pasting between the browser and my IDE
- Weak at debugging
- Weak at working with legacy code
- Nothing major — it works fine for me

---

## Section C — Claude Code

**Q8. How excited are you about Claude Code being introduced?**
*Linear scale, 0 to 10*
- 0 — Not excited at all
- 10 — Extremely excited

**Q9. Before this survey, how much did you know about Claude Code?**
*Single choice*
- I had never heard of it
- I had heard the name only
- I know roughly what it does
- I have read about it in detail
- I have used it myself

**Q10. Which of the following do you believe Claude Code can do?**
*Multi-select, choose all you think apply*
- Read and reason across an entire repository
- Create, edit and delete multiple files in a single task
- Run terminal commands, tests and builds
- Make a git commit and open a pull request
- Work from the terminal, an IDE, or a desktop app
- Keep working through a long multi-step task without step-by-step instructions
- I'm not sure

**Q11. Compared with pasting code into Web Gemini or ChatGPT, how much difference do you expect from an agent that works directly inside your repository?**
*Single choice*
- No real difference
- Slightly better
- Noticeably better
- Significantly better
- I don't know enough to say

**Q12. How likely are you to use Claude Code for real work in your first month of access?**
*Single choice*
- Definitely will
- Probably will
- Not sure
- Probably won't
- Definitely won't

---

## Section D — If Access Went Away

**Q13. If all AI coding assistants were removed tomorrow, how would your weekly output change?**
*Single choice*
- No change
- Down slightly — less than 10%
- Down noticeably — 10 to 25%
- Down a lot — 25 to 50%
- Down severely — more than 50%

**Q14. Which parts of your work would be hardest without an AI assistant?**
*Multi-select, choose up to 3*
- Boilerplate and scaffolding
- Understanding unfamiliar or legacy code
- Debugging and root-cause analysis
- Writing tests
- Documentation and comments
- Code review
- Learning a new language or framework
- Nothing significant

**Q15. If your access were limited or removed, what would you most likely do?**
*Single choice*
- Use my personal AI account for work tasks
- Go back to Stack Overflow and official documentation
- Ask teammates more often
- Just work slower
- Nothing would change for me

---

## Section E — In Your Own Words

**Q16. What is the one thing you most want Claude Code to do for you?**
*Long answer, optional*

**Q17. What worries you about the switch?**
*Long answer, optional*

---

## Notes for Whoever Runs This

- Turn off "collect email addresses" in the form settings so responses to Q15 (the shadow-IT question) stay honest.
- Keep Q16–Q17 optional so the open questions don't cause drop-off at the very end.
- Run this **before** the announcement email goes out, so it captures baseline sentiment rather than a reaction to the pitch.
- Keep Q1–Q3 even though the survey is anonymous — they enable cross-tabs like "72% of backend devs are excited vs. 41% of QA."

### Scoring guide

| Metric | Derived from | What it tells you |
|---|---|---|
| Excitement score | Q8 mean, plus % scoring 8+ | Overall enthusiasm (NPS-style: 9–10 promoters, 7–8 passive, 0–6 detractors) |
| Awareness gap | % of Q10 respondents ticking fewer than 3 capabilities | Whether this is a training problem, not a sentiment problem |
| Dependency | % of Q13 answering 25%+ output drop | The business case for the rollout |
| Leakage risk | % of Q15 choosing "personal AI account" | Shadow-IT / data-security exposure — flag anything above 10% |

With fewer than ~25 responses, report raw counts ("14 of 22 people") rather than percentages — percentages on a small sample invite people to argue with the sample instead of the finding.
