# Executive Actions & the Autocracy Score

The [constitution](constitution.md) decides *who holds which powers*. **Executive actions** are what turn those powers into concrete, devastating deeds. The current holder of a gating power can exercise a matching action from a country's **Executive Actions** page — silencing a rival, bending the state to their will — but every autocratic act is a public, permanent record that costs them for years to come.

The catalogue starts small and grows over time. Whatever the action, the design principle is the same: executive power has **no cooldown and no hard cap**. The only check is the governed — through a reputation score and a running vote penalty — and, for a monarch, the security of the throne.

## Who can act

Each action is gated by one constitutional power (for example, the "Ban party from public events" action is gated by the **Power to regulate political parties**). Whoever currently holds that power may exercise the action. The holder is resolved *live* through the constitution:

- **Cabinet position** — the current appointee's party acts, exercised by the party's owner.
- **Single-seat elected office** (e.g. a presidency) — the office-winning party acts.
- **Monarchy** — the reigning monarch acts (see [the Crown's price](#monarchs-and-the-constitutional-crisis) below).
- **Multi-seat legislature** — *unavailable*: the power is held collectively by the chamber, and there is no way to exercise it individually.
- **Non-partisan bureaucrats** — *unavailable*: a power handed to the independent civil service is deliberately **disarmed**. Moving a power to bureaucrats through a [constitutional change](constitution.md) is how a country takes a dangerous action off the table.

The Executive Actions page shows the whole catalogue to everyone — seeing what the executive *could* do to you is part of the game — but the action button is only enabled for the office holder. Everyone else sees exactly *why* it's unavailable to them.

## The autocracy score

There is no permission meter to fill or cooldown to wait out. Instead, every autocratic action a party takes is written to a permanent public **ledger**, and the party's **autocracy score** is computed from that ledger. Each act contributes its points, then **decays linearly to nothing over 2 game years**. A party that never acts autocratically sits at exactly **0** forever; a party that rules by force wears the stain until time launders it.

The score drives two visible things:

- **A reputation badge** on the party, running from **Committed to Democracy** (score 0) through **Autocratic Leanings** and **Worryingly Autocratic** to **Terrifyingly Autocratic**. The badge's tooltip carries the live number, the current vote penalty, and roughly when it will fade.
- **A continuous election penalty.** At every election, voters are less likely to choose an autocratic party — the penalty scales smoothly with the score (there are no threshold cliffs), up to a ceiling of **half** the party's vote preference at the extreme. Every day of good behaviour buys back a sliver of support.

Because the score is computed from the ledger rather than stored, it is always fully explainable: the ledger *is* the receipt.

!!! warning "You can't wash the stain by refounding"
    Disbanding a stained party and founding a fresh one doesn't reset the score — records committed by your **disbanded** parties follow you, their current owner, and keep decaying on the same 2-year clock. (A second, *concurrently live* party of yours is unaffected.)

## Monarchs and the constitutional crisis

A monarch has no party to stain and no political power to spend, so the autocracy score can't touch them. Their price is the same one a **royal veto** carries: every royal executive action triggers — or, if one is already running, **resets** — a **90-day [Constitutional Crisis](monarchy.md)** on the country. While the crisis is active, the threshold to pass a pure *abolish-the-monarchy* change is **halved** and such a package skips the usual constitutional-change cooldown.

So the symmetry is deliberate: a party executive spends its own electoral standing; a monarch gambles the security of the throne. Repeat royal actions simply keep the abolition window open.

Every executive action costs the acting party a flat **30 PP** (a monarch pays no PP — the constitutional crisis is their price). What differs between actions is the autocracy weight and the effect.

## Ban party from public events

The holder of the **Power to regulate political parties** can silence a rival:

- It costs **30 PP** and adds **15 autocracy points** to the acting party.
- The target party is **banned from organising public events for 6 months**. Any of their scheduled [campaign events](campaigning.md) inside the ban window are **cancelled immediately, with no refund** of money or activist energy.
- While the ban runs, the target **cannot create, edit, move or copy** campaign events at all — their calendar shows the ban and disables those controls. They can still *delete* events to tidy up.
- There is no stacking: a target already under a ban can't be re-banned until it lapses. When it does lapse, the party can organise again the next day, and the executive can pay the price to ban them afresh.

A single ban pushes the acting party to **Autocratic Leanings**; do it repeatedly and you climb toward **Terrifyingly Autocratic**, bleeding votes at every election until the ledger fades.

## Order arrest

The holder of the **Power to be Head of the Police** can have a named politician detained. It costs **30 PP** and adds **25 autocracy points** — the most autocratic act in the catalogue. Any active party politician can be targeted, including your own colleagues.

An arrested politician is detained for **12 months**, during which they:

- **cannot run campaign events** — and any [campaign events](campaigning.md) they were scheduled to lead are **cancelled immediately, with no refund**;
- are **struck from election candidacy** — removed as their party's nominee for any single-seat office, so their party's votes for that seat go elsewhere;
- **keep any cabinet seat but cannot exercise its executive actions** — the office is held, but frozen, while they are detained;
- **cannot post to social media.**

The state is shown by an **Arrested** trait on the character. There is no stacking — a detainee can't be re-arrested until they are released. An arrest lapses automatically after 12 months, restoring everything the next game day.

## Issue pardon

The holder of the **Power to grant pardons** can release an arrested politician early. It costs **30 PP** and, uniquely, *reduces* the acting party's autocracy score — by **10 points**, a smaller swing than an arrest's increase, so a pardon can offset autocratic acts but never buy a party a vote *bonus* (the score never drops below 0). A pardon immediately undoes every arrest effect: the freed politician can run events, stand for election, exercise cabinet powers, and post again at once.

## Next steps

- [Constitution](constitution.md) — how powers are assigned to offices, and how to move (or disarm) them.
- [Hereditary Monarchy](monarchy.md) — the Crown, the veto, and the constitutional-crisis mechanic.
- [Campaign Events](campaigning.md) — what a public-events ban shuts down.
