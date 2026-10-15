# User Stories

A **user story** is a work item written from the user's
point of view. It's the unit of planning in most agile
teams — small enough to build in days, concrete enough to
demo.

## The format

> As a **[who]**, I want **[what]** so that **[why]**.

Example:

> As a *shopper*, I want *to save my cart* so that *I can
> finish checkout later*.

The three parts each earn their keep: *who* tells you whose
problem this is, *what* scopes the work, and *why* tells
the builder what success looks like — which is what lets
them make the hundred small decisions the ticket doesn't
specify.

## INVEST (what makes a good story)

A good story is:

- **I**ndependent — buildable without finishing five other
  stories first
- **N**egotiable — a starting point for conversation, not a
  contract
- **V**aluable — delivers something a user would notice
- **E**stimable — the team can size it
- **S**mall — days, not months
- **T**estable — you can say how you'd verify it

Stories that fail INVEST usually fail *small* and
*independent* — they're secretly epics wearing a story
costume.

## Acceptance criteria (the "done" contract)

Under the story, list the concrete checks:

> As a shopper, I want to save my cart so that I can finish
> checkout later.
>
> - Cart contents persist across sessions for 30 days
> - Restoring a cart with a sold-out item shows a notice
>   and removes that item
> - Works logged in; guests get prompted to log in

Acceptance criteria are where "done" stops being a feeling.
Write them *before* building — they're the test plan in
disguise.

## Epics, stories, tasks (the hierarchy)

- **Epic** — a big outcome ("guest checkout"), months of
  work, too big to estimate honestly
- **Story** — a user-visible slice of the epic, days of work
- **Task** — a developer's sub-step ("add cart_items
  table"), hours of work, invisible to users

Epics get *split*, never estimated whole. If you can't see
the stories inside an epic, you don't understand it yet.

## Stories are a conversation, not documentation

The written story is a *placeholder for a conversation*
with the Product Owner — the famous "card, conversation,
confirmation" model. Teams that write perfect tickets and
never talk produce perfectly specified wrong software. The
ticket gets you to the conversation; the conversation gets
you to the right thing.
