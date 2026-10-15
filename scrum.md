# Scrum

Scrum is the most widely used agile framework. It's a small
set of roles, events, and artifacts — deliberately
incomplete, which is both its strength and why teams fill
the gaps with nonsense.

## The roles (three, no more)

- **Product Owner** — owns the *what* and the *why*.
  Maintains the backlog, sets priorities, and is the one
  person who can say "build this next." One person, not a
  committee — a committee can't prioritize.
- **Scrum Master** — owns the *process*. Removes blockers,
  protects the team from interruptions, and makes sure the
  ceremonies happen and stay useful. Not a manager, not a
  secretary.
- **Developers** — everyone who builds. They own the *how*
  and commit to what fits in a sprint. Self-organizing: no
  one assigns them tasks.

## The sprint (the heartbeat)

Work happens in **sprints**: fixed-length iterations, one to
four weeks (two is the common default). The length never
changes mid-stream — the fixed cadence is the point. Each
sprint:

1. **Sprint planning** — the team picks backlog items it
   believes it can finish, and says how.
2. **The work** — daily scrums keep it on track.
3. **Sprint review** — demo what got built to stakeholders.
   Working software, not slides.
4. **Sprint retrospective** — the team asks what to improve
   about *how it works*. No stakeholders; honesty requires
   safety.

## The daily scrum (15 minutes, standing)

Once a day, same time, same place, fifteen minutes max.
Each developer answers three questions:

1. What did I do yesterday?
2. What will I do today?
3. What's blocking me?

That's it. It's a *synchronization* meeting, not a status
report to a manager — if your standup is really a daily
status meeting for one boss, that's [agile going
wrong](agile-failing.md).

## The artifacts (three)

- **Product backlog** — the ordered wish list of everything
  that might get built. Ordered by the Product Owner; the
  top is always "what we'd do next."
- **Sprint backlog** — what the team committed to *this*
  sprint, plus the plan to build it.
- **Increment** — the working, tested, potentially shippable
  thing produced by the sprint. "Potentially shippable" is
  doing heavy lifting: half-integrated code isn't an
  increment.

## What's good about Scrum

The fixed cadence forces regular demos and retros, which
forces regular honesty. Time-boxing kills the "just one
more week" death march. And a real Product Owner ends the
"everything is priority one" era.

## What's bad about it

The ceremonies can calcify into ritual — standups nobody
listens to, retros where nothing changes, planning that's
really just a manager assigning work with extra steps. Scrum
also assumes a team building one product together; it fits
maintenance work and interrupt-driven teams poorly (that's
[Kanban](kanban.md) territory).
