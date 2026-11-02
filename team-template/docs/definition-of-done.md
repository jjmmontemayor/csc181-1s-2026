# Definition of Done

A story is **done** when it meets **its own acceptance criteria** and **every item below**.
If even one item is missing, the story is not done. It stays open and goes back to the
backlog at the end of the sprint.

The acceptance criteria describe what *this* story does. The Definition of Done is the
quality bar for *every* story. Quick test: if an item would be true for every story, it
belongs here.

## Every story

### Works

- [ ] All acceptance criteria pass, including the unhappy paths.
- [ ] It works on `main` (merged), not only on a branch or one laptop.
- [ ] It works on a phone-sized screen and on a laptop browser.

### Reviewed

- [ ] It reached `main` through a pull request linked to the issue (`Closes #N`).
- [ ] At least one teammate who did not write the code approved it.
- [ ] Review comments were answered or resolved.

### Tested

- [ ] Tests cover the acceptance criteria. Automated where practical; otherwise written test cases with results.
- [ ] All automated checks pass.
- [ ] No known Critical or Major defects remain open for this story.

### Safe and usable

- [ ] No secrets, passwords, or real personal data are in the repository.
- [ ] User input is validated, and errors show a helpful message instead of crashing.
- [ ] Basic accessibility: form fields have labels, images have alt text, text has enough contrast, and it can be used with a keyboard.

### Documented and tracked

- [ ] The README or docs are updated if setup, usage, or behaviour changed.
- [ ] The issue is closed and its card is in **Done** on the project board.

## Team additions

<!-- Add rules your team agrees on, for example from a retrospective.
     Record the date and the reason so the history stays visible. -->

| Added | Rule | Why |
|---|---|---|
| [YYYY-MM-DD] | [Rule] | [Reason, for example a Sprint 1 retro action] |
