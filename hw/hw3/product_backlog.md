# CSC181 Team Activity

## From Interviews to a Product Backlog

## Overview

Your team has finished its stakeholder interviews. This week you will turn what you heard into a **product backlog**: an ordered list of user stories, each with acceptance criteria, that your team will build from in Sprint 1 and Sprint 2.

The learning material for this activity is the **Week 4 lecture**:

[CSC181 Week 4: Requirements, User Stories, Use Cases, and Acceptance Criteria](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#1)

Every step below names the slides it uses. Open the slide before you start the step. The links in this document jump straight to the slide.

By Sunday your team will have:

1. An evidence table that turns interview notes into stakeholder needs
2. **10 to 15 user stories** that trace back to those needs, checked with INVEST
3. Specific, testable acceptance criteria for every story, including unhappy paths
4. At least **3 quality requirements or constraints** written with EARS patterns
5. **One use case** for your most complex workflow
6. A story map, a MoSCoW priority and a size for every story, and one ordered backlog
7. A Definition of Done
8. A traceability table, and a record of reviewing the backlog with a stakeholder

The backlog is a living list. You will refine it again when you plan Sprint 1, and at every sprint review after that (Week 4, [slide 26](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#26)).

| Dates | What happens |
|---|---|
| Nov 2–9 (this week) | Product backlog (this activity), due Nov 9 |
| Nov 9–22 | Sprint 1: build the top of the backlog |
| Nov 23–Dec 4 | Sprint 2: finish the MVP, test it, and write the documentation |
| Dec 7–11 | Final demonstration and defense |

> **The backlog decides what you build.** A story that is not in the backlog does not get built, and a story at the bottom may never be built. That is the point. Put the work that matters most to your stakeholders at the top, and be honest about what will not fit.

---

## Team template

Use the provided Markdown template for your submission:

[Open or download the team template](product_backlog_template.md)

After downloading or copying the template:

1. Work on **one shared copy** as a team.
2. Replace all bracketed placeholders, such as `[Team name]`, with your team's answers.
3. Complete the Team AI Use Declaration and the Team Confirmation at the end of the template.
4. Each member saves the same final file in their personal CSC181 GitHub repository as:
   ```text
   activities/product-backlog.md
   ```
   with any images (story map, use-case diagram) in `activities/backlog-images/`.
5. Each member commits and pushes, then submits their own GitHub file link through MOLE before **November 9, 2026 23:59:59**.

---

## Learning goals

After completing this activity, you should be able to:

- Turn interview notes into stakeholder needs, and needs into requirements
- Tell functional requirements, quality requirements, and constraints apart
- Write user stories with a real role, a goal, and a benefit, and check them with INVEST
- Split stories that are too big for one sprint
- Write specific, testable acceptance criteria, including unhappy paths, in Given–When–Then form
- Write quality requirements with EARS patterns and without weak words
- Write a use case with a main success scenario and extensions
- Prioritize and order a backlog with MoSCoW, value versus effort, and rough sizes
- Trace each story to its stakeholder source

---

## Reading list

### Required: Week 4 lecture

Read these slides before you start. Each link opens the slide directly.

| Slides | Topic | Used in |
|---|---|---|
| [5](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#5)–[7](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#7) | What a requirement is; functional, non-functional, and constraints | Step 2 |
| [10](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#10) | From interview notes to requirements | Step 1: the worked example to follow |
| [11](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#11)–[12](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#12) | What makes a requirement good; weak words | Steps 4, 5, and 11 |
| [13](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#13) | EARS sentence patterns | Step 5 |
| [14](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#14)–[17](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#17) | Story format, the 3 Cs, INVEST, weak and strong stories | Step 3 |
| [18](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#18) | Splitting big stories (epics) | Step 3 |
| [19](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#19) | Story maps and the walking skeleton | Step 7 |
| [20](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#20)–[22](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#22) | Acceptance criteria, Given–When–Then, Definition of Done | Steps 4 and 9 |
| [23](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#23)–[25](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#25) | Use cases: diagram, description, stories or use cases | Step 6 |
| [26](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#26)–[28](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#28) | The product backlog (DEEP), MoSCoW, value versus effort | Step 8 |
| [30](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#30) | Traceability: from problem to test | Step 10 |
| [31](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#31)–[32](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#32) | Validate before you build; common mistakes | Step 11 |
| [34](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#34) | Team milestone: requirements package and product backlog | What this activity produces |

> **Warm-up (optional, 25 minutes).** Before writing your own stories, do the in-class activity on [slides 35–36](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#35) with one of the three practice scenarios, then discuss the four flawed requirements on [slide 33](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#33). It is much easier to spot weak stories in someone else's project first.

---

## Activity instructions

### What you start with

- Your interview notes from **at least two stakeholder groups** on your Week 3 stakeholder list
- Your Week 3 problem statement, stakeholder list, and initial scope

Read through all of your interview notes together as a team before Step 1. Each member should bring the notes from the interviews they conducted.

### Step 1. Turn interview notes into needs

Slide: [10](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#10)

Record **at least 8 findings** in the evidence table, using the three columns from slide 10:

1. **What we heard or saw**: a short quote or a description of what you observed.
2. **Underlying need**: the problem behind the words. This is the analysis step. Stakeholders rarely ask for features; they describe problems.
3. **Requirement idea**: what the software could do about it. You will turn these into stories in Step 3.

Give every finding an ID (F1, F2, …) and a source code (V1, O2, …). Keep the team's own beliefs in a separate assumption log (Week 3, slide 19). If no stakeholder said or did it, it is an assumption, not a finding.

> Do not include full names, phone numbers, or other personal information about the people you interviewed. Use a role and a code, such as "Vendor V2".

### Step 2. Sort requirements by type

Slides: [5](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#5)–[7](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#7)

Label each requirement idea from Step 1 as one of:

- **Functional**: what the system does. These become user stories (Step 3).
- **Non-functional (quality)**: how well it does it, such as speed, usability, security, or working offline. These become EARS requirements (Step 5) or acceptance criteria.
- **Constraint**: a limit on the solution, such as the Data Privacy Act, free hosting only, or Android phones only. These also go in Step 5.

A quick test from slide 7: if you can draw it as a button or a screen, it is probably functional. If it describes how fast, how safe, or how easy, it is non-functional.

### Step 3. Write user stories

Slides: [14](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#14)–[18](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#18)

Write **10 to 15 user stories** in the format:

```text
As a <role>, I want <goal>, so that <benefit>.
```

- Use real roles from your stakeholder list, such as "out-of-town visitor" or "canteen cashier", not "user" (slide 14).
- Always include the "so that". It links the story to the problem and leaves room for a better solution.
- Every story must cite at least one finding ID from Step 1.
- Check each story against **INVEST** (slide 16): Independent, Negotiable, Valuable, Estimable, Small, Testable. Rewrite stories that are tasks ("set up the database"), technical choices ("use Firebase"), or several actions joined by "and" (slide 17).
- **Split** any story too big for one sprint (slide 18). Split by workflow step, by business rule, by data type, or by happy path first and variations later. Keep the original as an **epic** and list the stories it was split into.
- Remember the 3 Cs (slide 15): the card is short on purpose. The detail comes from the conversation and is written down as the confirmation, which is Step 4.

### Step 4. Write acceptance criteria

Slides: [11](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#11), [12](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#12), [20](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#20), [21](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#21)

1. For **every** story, write **at least 3 acceptance criteria** as a checklist (slide 20). At least one must be an **unhappy path**: no results, invalid input, no connection, permission denied, a duplicate, an item that sold out, and so on.
2. Use numbers and rules, not weak words (slide 12). Flag and rewrite any criterion containing *fast, easy, user-friendly, relevant, appropriate, etc., and/or, all, some,* or *should be able to*.
3. For every **Must-have** story (Step 8), also write **at least 2 Given–When–Then scenarios**: one normal case and one unhappy path (slide 21). Use concrete values, such as "it is 7:00 PM and two events start before 8:00 PM". These become your test cases in Week 9.

If you cannot write a test for a criterion, it is not finished. Rewrite it.

### Step 5. Write quality requirements and constraints with EARS

Slides: [12](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#12), [13](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#13)

Write **at least 3** non-functional requirements or constraints from Step 2 using the EARS patterns on slide 13 (Ubiquitous, Event-driven, State-driven, Unwanted behaviour, Optional feature). Use at least two different patterns.

For each one, record the finding it came from and who agreed to any number in it. "Within 2 seconds" is a decision, not a fact.

Week 5 covers quality attributes in depth. You may add more then.

### Step 6. Write one use case for your most complex workflow

Slides: [23](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#23)–[25](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#25)

Most teams keep the backlog as user stories and add a use case for the one workflow with the most steps or error paths (slide 25). Do the same:

1. Draw a **use-case diagram** for your system: the system boundary, the actors (roles, not people), and the main use cases (slide 23). A photo of a clear sketch is fine.
2. Pick the use case with the most steps or the most ways to go wrong, such as placing an order, submitting a request, or approving a document.
3. Write a **use-case description** in the format of slide 24: primary actor, precondition, a numbered main success scenario, **at least 2 extensions** numbered against the step where they branch, and a postcondition.
4. List which user stories the use case covers. A use case often matches an epic.

If your team chose use cases as its primary format instead of stories, write a use case for every Must-have goal and give each one acceptance criteria. Discuss this with your instructor first.

### Step 7. Build a story map

Slide: [19](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#19)

1. Across the top, write the **backbone**: the big steps of your primary user's journey, in order.
2. Under each step, place the stories that support it, highest priority at the top.
3. Draw a line for **Release 1 (MVP)**. It must cut through every step of the journey so the user can complete the whole task, even if simply. This is the walking skeleton.

Sticky notes photographed clearly, a table in the template, or a whiteboard tool are all fine.

### Step 8. Prioritize, size, and order the backlog

Slides: [26](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#26)–[28](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#28)

1. **MoSCoW** (slide 27). Label every story **Must, Should, Could, or Won't (this time)**. "Must" means the first release fails without it, not that the team wants it. Keep Musts to about **60% of your capacity** for two sprints.
2. **Size** (slide 26). Give every story a rough size: **S** (a day or two for one person), **M** (several days), or **L** (most of a sprint). Split any L story that is a Must.
3. **Value versus effort** (slide 28). Place your stories on the four-quadrant grid. Value comes from stakeholders; effort comes from the developers on the team. Do quick wins first, split big bets, and drop time sinks.
4. **Order** the backlog into **one sequence with no ties** (slide 26). Use MoSCoW first, then value, risk, and dependencies. A risky story may deserve to go early so you learn sooner.
5. Keep **Won't have** stories in the backlog. Do not delete them. They are your out-of-scope list from Week 3.

Check the result against **DEEP** (slide 26): the top is detailed and ready, every item is estimated, the list can change, and it is ordered.

### Step 9. Agree on a Definition of Done

Slide: [22](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#22)

Write a short Definition of Done that will apply to **every** story from Sprint 1 onward, such as "code reviewed in a pull request, acceptance criteria checked, works on a phone, README updated".

Use the test on slide 22: if it is true for every story, it belongs in the Definition of Done. If it describes this one feature, it is an acceptance criterion.

### Step 10. Complete the traceability table

Slide: [30](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#30)

For each **Must-have** story, record the problem or goal it addresses, and the finding it came from. Leave the test case column empty until Week 9.

Then check both directions:

- A story that traces to no goal is gold-plating. Remove it or move it to Won't.
- A goal from your problem statement with no stories is a gap. Add a story or explain why it is out of scope.

### Step 11. Validate the backlog

Slides: [31](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#31), [32](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#32)

1. **Team review.** Read every story aloud. Check it against INVEST (slide 16), the eight qualities on slide 11, and the common mistakes on slide 32. Record at least two problems you found and fixed.
2. **Stakeholder walk-through.** Show your story map and the top of your backlog to **at least one stakeholder you interviewed**. Ask: "Is anything missing? Is the order right? Would this first release help you?" Record what they said and what you changed.

Validation asks whether these are the right requirements. A short walk-through now is much cheaper than a rebuild in Sprint 2.

---

## Common mistakes to avoid

From Week 4, [slide 32](https://jjmmontemayor.github.io/csc181-1s-2026/lecture/CSC181-Week4-Requirements-User-Stories-Use-Cases.html#32):

- **Every story starts "As a user…".** Use roles from your stakeholder list.
- **No "so that".** State the benefit every time.
- **Only happy-path criteria.** Add at least one unhappy path per story.
- **Stories that are technical tasks.** "Create the database" is a task under a story, not a story.
- **Everything is a Must.** Keep Musts to about 60% of capacity, so something can be cut.

Also:

- **Stories without a source.** If no stakeholder said or did something that supports a story, find the evidence or move it to the assumption log.
- **Weak words in criteria.** "The page loads quickly" cannot be tested. "The event list appears within 3 seconds on a 3G connection" can.
- **AI-generated "findings" or stories presented as stakeholder input.** An AI tool cannot tell you what your stakeholders need. Only your interviews can.

---

## Submission summary

| Item | Requirement |
|---|---|
| Backlog document | `activities/product-backlog.md` in each member's personal CSC181 repository |
| Images | `activities/backlog-images/` (story map, use-case diagram) |
| Submitted through | MOLE: each member submits their own GitHub file link |
| Deadline | **November 9, 2026 23:59:59** |
| AI use | Declare any AI assistance in the Team AI Use Declaration section |
