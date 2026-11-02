# Sprint rules

CSC181 uses two sprints, followed by the final demonstration and defense.

| | Dates | Weeks | Ends with |
|---|---|---|---|
| Sprint 1 | Mon Nov 9 – Sun Nov 22 | 8–9 | Sprint 1 review and retrospective |
| Sprint 2 | Mon Nov 23 – Fri Dec 4 | 10–11 | Sprint 2 review and retrospective; code freeze |
| Final defense | Mon Dec 7 – Fri Dec 11 | 12 | Team presentation, demonstration, and defense |

Sprint 2 is shorter (12 days). Plan it from what the team actually finished in Sprint 1.

## Rules for every sprint

1. **Start with a plan.** On the first day, write a one-sentence sprint goal, pick the stories
   that serve it, and give each story an owner and a reviewer. Put the goal in the board's
   description or the README.
2. **Everything is an issue.** Stories, tasks, and bugs are GitHub issues on the board,
   assigned to one person, labelled, and set to the sprint's iteration. Work that is not on the
   board does not count.
3. **Move cards as you work.** Backlog → Ready → In Progress → In Review → Done. If a card sits
   in In Progress for three days, split it or ask for help.
4. **One approval to merge.** Nobody pushes to `main`. Every change goes through a pull request
   that a teammate approves. Review within 24 hours on school days.
5. **Done means Done.** Only stories that meet the [Definition of Done](definition-of-done.md)
   count. Unfinished stories move to the next sprint or back to the backlog. They are not
   partly done.
6. **Check in three times a week.** Each member posts: what I did, what I will do next, what is
   blocking me. Ask the team after 30 minutes stuck, not three days.
7. **Keep your own evidence.** Each member keeps a contribution log with a link for every row
   (commit, pull request, review, issue, or document).

## What the instructor checks at each sprint review

| Area | What is checked |
|---|---|
| Sprint goal | Stated at the start; met, partly met, or not met, in one sentence. |
| Live demo | Working software shown from `main` (deployed, or run from a fresh clone with the README). No slides, mock-ups, or unmerged branches. |
| Done stories | Which stories meet the Definition of Done, and which went back to the backlog and why. |
| Project board | Every item has an owner and sits in its true column. The board matches the repository history, not a last-hour update. |
| Pull requests | Changes reached `main` through linked, reviewed pull requests with real review comments. |
| Contribution | Each member has commits, pull requests, and reviews. Each member's contribution log and sprint reflection. |
| Retrospective | One or two concrete changes for the next sprint, written into the working agreement or the Definition of Done. |
| Feedback | Questions and feedback from the review recorded as issues. |

### Also checked at the Sprint 2 review

| Area | What is checked |
|---|---|
| Testing | Test plan, test cases with results, and a defect log with severity and priority. |
| Documentation | Draft user guide and technical documentation; README setup steps that work. |
| Readiness | Deployment or release plan; security and privacy checklist done. |

## Code freeze

After the Sprint 2 review, only bug fixes and documentation are merged to `main`. The version
on `main` at the start of defense week is the one you present.
