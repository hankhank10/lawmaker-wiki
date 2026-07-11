# Global Decisions

Every so often the whole world is handed the same dilemma at once — an earthquake in a
far-off land, a viral craze sweeping every classroom, the kind of thing that makes the
evening news everywhere simultaneously. This page is about **Global Decisions**: world-wide
events that every country votes on independently, with real consequences for the countries
that vote themselves into them.

## What a decision is

A global decision is triggered centrally — you'll see it appear for your country with no
warning — and it always has exactly **two choices**. Each choice comes with a short list of
consequences: some are pure flavour ("we'll be seen as a humanitarian leader"), and some are
programmatic — a real budget effect that shows up on your country's books once the decision
resolves. Effect-bearing consequences are marked with a **budget impact** chip so you can see
at a glance which choice actually costs (or earns) something.

One of the two choices is always marked as the **default** — the one that wins automatically
if your country can't produce a clear winner (see [Abstention and deadlock](#abstention-and-deadlock)
below).

## Who votes

Voting follows the game's usual public-politics rules, with one twist: it's **one party, one
vote**, full stop.

- Every active party in a country that received the decision gets exactly one vote — **not**
  weighted by seats, legislature presence, or anything else. A tiny party with no seats
  carries exactly as much weight as the governing party.
- Only the **party leader** can cast it, same as any other leader-gated action.
- Casting a vote requires a short **public reason** — a few sentences explaining your party's
  position. It's moderated like any public text, and just like a demand pledge, it's **locked
  the moment you submit it**: no second thoughts, no quiet editing. Votes and reasons are
  visible to everyone in real time, so you'll see how the rest of the country — and the rest
  of the world — is breaking as the window runs.
- Party eligibility is checked live: a party that's disbanded or been swept onto a throne
  can't vote, but a **brand-new party founded after the decision was triggered can still vote**
  while the window is open. The reverse also applies — a country founded *after* the trigger
  simply doesn't get a row for that decision at all; it'll be in on the next one.

## The 12-day window

Once triggered, a decision stays open for **12 game days** for every country at once, and
every country resolves together on the same date — there's no early resolution the way
budget votes have. You'll see a live countdown ("closes in *N* days", counting down to
"closes in 1 day" on the last votable day) on both the decisions index and the decision's
own page.

## Abstention and deadlock

Not voting is simply **abstaining** — there's no explicit "abstain" button, you just don't
cast a vote, and abstentions count for neither side.

When the window closes, each country resolves independently:

- **Strict majority wins.** More yes votes than no (or vice versa) and that choice's
  consequences apply.
- **A tie — including 0 votes cast either way — falls to the decision's default choice.**
  This is called a "deadlock default," and it's flagged plainly on the decision page
  ("deadlock — default applied") so nobody mistakes it for a real majority.
- A country with **no eligible parties at all** still gets a row and still resolves — it just
  shows "no parties — default pending" while the window is open, then quietly defaults the
  moment it closes. "Every country receives it" is meant literally.

## Budget effects

Some choices carry a real financial consequence, fixed the moment your country's decision
resolves:

- The game takes a **fixed percentage of your country's monthly GDP** (as authored in the
  decision, e.g. 0.5%) and charges (or credits) it **every month for a fixed number of
  months** (e.g. 6). The amount is calculated once, from your GDP at the moment of
  resolution, and then frozen — it does **not** rise or fall with your economy afterwards,
  even if the decision drags on for months.
- These effects start from the **first day of the following game month** and show up as their
  own line items on your **Budget page**, in a dedicated "Global decision effects" section —
  each row shows the label, direction (income or expenditure), the monthly amount, and how
  many months are left, with a link back to the decision that caused it. They're folded into
  the country's live budget totals and Sankey chart alongside ordinary tax and spending, and
  into the monthly treasury flow just like any other income or expense.
- A country with its economy disabled receives and votes on decisions exactly like anyone
  else — the budget effect simply never gets created for it, since there's no budget to
  attach it to.
- Effects apply regardless of whether your country is under an [IMF programme](economy.md#imf-intervention)
  — a decision you voted (or defaulted) into still bites even under emergency austerity.

## Where to find decisions in-game

- **Global Decisions page** — the player-facing home of the feature: live decisions pinned at
  the top with their countdown, historical ones below with their outcome ("14 countries said
  yes, 3 said no"), newest first.
- **Decision detail page** — the full scenario, both choices with their consequence lists, the
  default-choice marker, your party's vote form (if you haven't voted yet) or your party's
  locked vote and reason (if you have), and a **world response table** — one section per
  country, showing every cast vote with its reason while the window is open, and the frozen
  outcome and tallies once it's resolved.
- **Dashboard card** — a prominent card tells you when your party has a decision waiting and
  whether you've voted yet, with the nearest deadline surfaced first if more than one is live.
- **Budget page** — any active decision effects for your country appear as their own section,
  right alongside the rest of your country's finances.

## Next steps

- [Economy](economy.md) — how the budget page and Sankey chart work, and how a decision's
  budget effect fits into that picture.
- [Voter Demands & Pledges](demands.md) — the game's other public-reason-required commitment,
  and the closest existing pattern to a decision vote.
