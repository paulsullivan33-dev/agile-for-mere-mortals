# Planning and Estimation

Every agile team has to answer "when will it be done?" The
honest answer is *we don't know, but here's our best
forecast* — and agile's estimation practices are about
making that forecast less wrong over time.

## Story points (relative sizing)

Instead of estimating hours, teams estimate **story
points** — a relative measure of effort. A 2-point story is
roughly twice the work of a 1-point story. The Fibonacci-ish
scale (1, 2, 3, 5, 8, 13) is deliberate: it forces you to
admit uncertainty grows with size. The gap between 8 and 13
says "we barely know."

Points measure *the team's* effort, not time — a point
means something different on every team, and that's fine.
Points become comparable to hours only through.

## Velocity (your actual pace)

**Velocity** is how many points the team completes per
sprint, averaged over several sprints. If you finished 21,
24, and 19 points in the last three sprints, your velocity
is ~21 — and a backlog of 210 points is roughly ten sprints
of work.

Velocity is a *forecasting* tool, not a *performance*
metric. The moment management uses it to compare teams or
demand "more velocity," teams inflate points and the number
becomes fiction. This happens constantly; it's the most
predictable failure in agile (see [How Agile Goes
Wrong](agile-failing.md)).

## Planning poker (how estimates get made)

The team estimates together:

1. The Product Owner reads a story.
2. Everyone privately picks a point value (cards, app, or
   fingers).
3. All reveal at once — the *simultaneous* reveal matters;
   it stops the senior dev's number from anchoring everyone
   else.
4. Outliers explain their reasoning ("I picked 13 because
   the payment API has no sandbox"). The conversation is
   the point — it surfaces hidden complexity.
5. Re-vote until the numbers converge.

A story nobody can estimate gets *split*, not guessed.

## Why estimates are always wrong (and what to do)

- **Unknown unknowns.** The estimate assumes the work is
  what you think it is. It often isn't.
- **Everything is estimated at the moment of maximum
  ignorance** — before starting. Estimates should get
  *revised* as you learn; teams that never re-estimate are
  planning with stale maps.
- **Pressure corrupts.** An estimate made under "we need it
  Friday" isn't an estimate; it's a wish with numbers.

The agile response isn't better estimating — it's needing
estimates *less*: small batches, working software every
sprint, and forecasting from measured velocity instead of
wishes. And the most honest estimate format ever invented:
a range with a confidence level ("2–4 sprints, 80%
confident").
