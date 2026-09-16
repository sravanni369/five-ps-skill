# five-ps: a Claude Code skill for Matt Gray's 5 P's

A skill that applies the 5 P's personal-brand framework (Positioning, Promise, Point of view,
Pillars, Platform) to a person, institute or product, or audits an existing brand against it.
Built 2026-09-16.

What it does differently from pasting the framework into a prompt:

- **Facts first.** Step 0 collects what the brand already produces from the machine before a
  word is written, and lists every missing fact (founder, place, results, handles, price).
- **Gaps are listed, never filled.** No invented follower counts, results or proof points. A
  plan with an honest gaps section beats one with a made-up number.
- **Two modes.** Diagnose: score each P as pass, weak or missing with evidence, and name the
  one to fix first (positioning before promise before POV before pillars before platform;
  posting more is never the first fix). Apply: write the eight-section plan.
- **Two pillars, not three.** Pen or camera, one format mastered, the second medium gated on
  a consistency streak rather than a date.
- **It writes; it never posts.** The output is a dated markdown plan in the brand's folder.

## Install

Copy `SKILL.md` to `~/.claude/skills/five-ps/SKILL.md` and `.claude/commands/5ps.md` into a
project's `.claude/commands/`. Then `/5ps <brand>` or `/5ps audit <brand>`.

## The eight sections the plan produces

1. Positioning: one sentence, the different / relevant / believable table, what to stop saying
2. Promise: one sentence marked draft, specific / time-bound / transformational, what it does not promise
3. Point of view: three to five beliefs the brand already acts on
4. Pillars: two, in a table with format, channel and cadence; subjects not to chase
5. Platform: awareness → authority → audience → asset, one measure each
6. What this changes on Monday
7. Gaps to confirm
8. Attribution: the framework is Matt Gray's; the plan is a proposal

Framework: Matt Gray, "The 5 P's". The skill, its rules and its tests are mine.
