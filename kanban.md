# Kanban

Kanban is the quieter agile framework: no sprints, no
required roles, no ceremonies. Just a board, a few rules,
and attention to flow. It comes from Toyota's manufacturing
system, adapted for knowledge work.

## The board

Columns represent workflow states. The classic minimal
board:

```
To Do | Doing | Done
```

Real boards grow columns that match reality: `Backlog |
Ready | In Progress | In Review | Done`. The rule: the board
must show *your actual process*, including the embarrassing
parts (like the "waiting on legal" column everyone
pretends isn't there).

## The one big idea: limit work in progress

Each column gets a **WIP limit** — the maximum number of
items allowed in it at once. When "In Progress" is full, you
don't start something new; you help finish something stuck.

This fights the most expensive habit in knowledge work:
*starting* lots of things and *finishing* few. Every
half-done item is inventory you're paying carrying costs on
— it goes stale, it blocks others, you forget the context.
WIP limits make the jam visible instead of letting everyone
quietly drown.

## Flow metrics (what to actually watch)

- **Cycle time** — how long an item takes from "started" to
  "done." Shorter and more predictable beats heroic and
  erratic.
- **Throughput** — items finished per week. The honest
  measure of capacity; use it for forecasting instead of
  estimates (see [Planning and
  Estimation](planning-estimation.md)).
- **Aging** — how long the oldest in-progress item has been
  sitting. An item aging past your normal cycle time is a
  blocker wearing a disguise.

## The rules (few, and they matter)

1. Visualize the workflow (the board).
2. Limit work in progress.
3. Manage flow (watch the metrics above).
4. Make policies explicit (write down what "done" means for
   each column — a checklist beats tribal knowledge).
5. Improve collaboratively (a regular look at the board's
   data, even without Scrum's formal retro).

## Scrum vs Kanban, honestly

| | Scrum | Kanban |
|---|---|---|
| Cadence | Fixed sprints | Continuous flow |
| Roles | Three defined | None required |
| Change mid-work | Discouraged during sprint | Fine anytime |
| Best for | Product teams, plannable work | Support, ops, interrupt-driven work |
| Failure mode | Ceremony theater | Board nobody looks at |

Many teams end up with **Scrumban** — sprints for planning
cadence, a Kanban board for daily flow. That's fine. The
frameworks are tools; use the parts that shorten your
build-learn loop.
