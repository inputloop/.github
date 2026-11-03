# To any agent working in this repository

<!-- landing-rule 1.1: where work lands. Installed by ld1ck (c4/skills-mint/2026-10-29/landing); edit the source and run `ld1ck install --update` again, never this block -->
## Where work lands

- Work lands on this repository's main or development branch (sometimes called master). A session does not
  invent a branch name, and does not invent a reason not to work there; it avoids boilerplate and waste that
  cannot be specifically justified as a necessary cost.
- A branch a hosting harness assigns is a staging post, not a destination: when this repository's checks are
  green, fast-forward `main` to it and push both in the same turn, unless the 17-minute rule below, the last
  line of this block (`landing: review-first`), or the person says otherwise.
- The 17-minute rule (Corwin, 2026-10-29, his words in c4 `skills-mint/2026-10-29/landing/SKILL.md`), for a
  repository that already has work in it, including one we were directed to work on another branch of.
  Three times, ask whether the repository changed within the last 17 minutes (`ld1ck recent`, one receipt
  line each, kept for the hand-back):
  1. before you begin merging changes: if it did, prepare the work so it can go to a working branch or a
     pull request should those be required;
  2. when the work is ready: if it changed again within the last 17 minutes, put the work on an alternative
     branch named from the functional or logical context of what you are doing; a serial number is tacked on
     only when no meaningful name is possible or the name is taken (`ld1ck branch-name`);
  3. when you are about to commit and push: if it still changed within the last 17 minutes, open a pull
     request for that branch instead of moving `main` (`ld1ck pr`); when you know the other workers have
     agents supporting their work, leave them a message in it saying what was completed and suggesting they
     automate the merge if that is within their instructions and their users' preferences.
- Check, then re-check: run the repository's checks before the push, and again after it on what actually
  landed (the fetched `main`); keep both receipts.
- The hand-back says, for every repository pushed, where the work can be seen: the repository, `main` and
  whether it moved, the commit, or the branch and pull request that wait. Anywhere in the hand-back, in any
  order: `ld1ck handback` reads it as a container, never as a template.
- Nothing here lets a session make a repository public, rewrite history, force-push, or move a partner's
  `main`: in a partner's repository, proposals only, on a branch they can take or leave.

landing: main
<!-- /landing-rule -->

## How we work with agents here

This is a workshop with a laboratory in the back. These rules hold in every inputloop repository unless the
repository's own AGENTS.md says otherwise, and the person you work for wins over both.

- **Whose name.** Commits are authored by the person the work is for; signing is theirs, by hand. Your part is
  the last line of the message: `PERSONA (for PERSON, MODEL)`. No vendor trailers, no session links, no
  "Generated with". Your workspace's global git identity does not apply here (the full rule: ils4's AGENTS.md,
  section 1).
- **Their words first.** File the request verbatim before you build. When it carries a word that can be read
  more than one way (UI words especially), write the readings from more to less likely, one line each, beside
  the request; build the first; say in your hand-back if you took another.
- **Yes, and.** Add what is asked without putting away what is liked. When a behaviour changes, keep the old one
  as an option unless that makes things much harder. Correct generated work in its generator, with a test,
  never by hand in the output.
- **A check, not a caution.** Every new promise gets a check, and every check a planted fault that must turn it
  red. Do not invent approval steps.
- **Drive.** Derive what you can from what has been said; ask only what you can explain from downstream. Fix
  your own mistakes without asking, and say what now prevents each.
- **Public is not published.** Making a repository public is a partner's act. Link only public repositories
  from public pages. Check for secrets at every way out; note licences at the way in.
- **Access.** WCAG 2.1 AA in light and dark, keyboard paths for everything, plain words, no hand edits asked of
  the people least able to make them.
- **Terms.** Code `GPL-3.0-or-later` (LGPL where it helps), writing `CC-BY-SA-4.0`; every file says its terms,
  at the end.
