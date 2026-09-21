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

There is no permission meter to fill or cooldown to wait out. Instead, every autocratic act a party commits is written to a permanent public **ledger**, and the party's **autocracy score** is computed from that ledger. The ledger has two sources: **executive actions** (this page) and **[authoritarian laws](#authoritarian-laws)** — voting for a narrow set of laws that attack the mechanisms of accountability. Each act contributes its points, then **decays linearly to nothing over 2 game years**. A party that never acts autocratically sits at exactly **0** forever; a party that rules by force wears the stain until time launders it.

The score drives two visible things:

- **A reputation badge** on the party, running from **Committed to Democracy** (score 0) through **Autocratic Leanings** and **Worryingly Autocratic** to **Terrifyingly Autocratic**. The badge's tooltip carries the live number, the current vote penalty, and roughly when it will fade.
- **A continuous election penalty.** At every election, voters are less likely to choose an autocratic party — the penalty scales smoothly with the score (there are no threshold cliffs), up to a ceiling of **half** the party's vote preference at the extreme. Every day of good behaviour buys back a sliver of support.

Because the score is computed from the ledger rather than stored, it is always fully explainable: the ledger *is* the receipt.

!!! warning "You can't wash the stain by refounding"
    Disbanding a stained party and founding a fresh one doesn't reset the score — records committed by your **disbanded** parties follow you, their current owner, and keep decaying on the same 2-year clock. (A second, *concurrently live* party of yours is unaffected.) This applies equally to points earned from [authoritarian laws](#authoritarian-laws) — it's the same ledger either way.

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
- A ban is not always a sentence served in full — whoever holds the gating power can **[lift it early](#lift-public-events-ban)**, including a government that inherits the office from the executive that imposed it.

A single ban pushes the acting party to **Autocratic Leanings**; do it repeatedly and you climb toward **Terrifyingly Autocratic**, bleeding votes at every election until the ledger fades.

## Lift public events ban

The same **Power to regulate political parties** that silences a party can also free one. It costs **30 PP** and, like a pardon, *reduces* the acting party's autocracy score — by **10 points**.

- Only a party **currently serving a ban** can be freed; the target picker lists them with the date each ban would otherwise have lapsed, and marks your own party if it is among them.
- The ban ends **immediately**. The freed party can create, edit, move and copy campaign events again the same day, without waiting out the remaining months.
- **What's gone stays gone.** Events the ban cancelled were deleted, along with the money and activist energy spent on them. Lifting the ban returns the *right to organise*, not the campaign that was destroyed.
- Nothing stops the executive banning them again afterwards — at the usual price of 30 PP and 15 autocracy points. Since the lift's −10 is smaller than the ban's +15, cycling a rival in and out of a ban *deepens* an autocratic record rather than laundering it.
- You **can** free your own party — a party that wins the office while serving a predecessor's ban is not condemned to sit the rest of it out — but doing so scores you **nothing**. The −10 is credit for freeing *someone else*; ending a ban on yourself costs the 30 PP and buys a way out, not a democratic record. (The ledger still records it, at 0 points, and the press still reports whose ban you lifted.)

As with a pardon, the score is floored at 0: freeing parties can offset autocratic acts you have already committed, but it never buys a party a vote *bonus*.

## Order arrest

The holder of the **Power to be Head of the Police** can have a named politician detained. It costs **30 PP** and adds **25 autocracy points** — the most autocratic act in the catalogue. Any active party politician can be targeted, including colleagues in your own party — with two exceptions: you can't target **yourself**, and a **sitting single-seat office holder** (for example, an elected president) can't be arrested at all — only voted out at the ballot box. A candidate contesting such an office, and anyone holding a cabinet seat, remains fair game.

An arrested politician is detained for **12 months**, during which they:

- **cannot run campaign events** — and any [campaign events](campaigning.md) they were scheduled to lead are **cancelled immediately, with no refund**;
- are **struck from election candidacy** — removed as their party's nominee for any single-seat office, so their party's votes for that seat go elsewhere;
- **keep any cabinet seat but cannot exercise its executive actions** — the office is held, but frozen, while they are detained;
- **cannot post to social media.**

The state is shown by an **Arrested** trait on the character. There is no stacking — a detainee can't be re-arrested until they are released. An arrest lapses automatically after 12 months, restoring everything the next game day.

## Issue pardon

The holder of the **Power to grant pardons** can release an arrested politician early. It costs **30 PP** and, uniquely, *reduces* the acting party's autocracy score — by **10 points**, a smaller swing than an arrest's increase, so a pardon can offset autocratic acts but never buy a party a vote *bonus* (the score never drops below 0). A pardon immediately undoes every arrest effect: the freed politician can run events, stand for election, exercise cabinet powers, and post again at once.

## Authoritarian laws

Executive actions aren't the only way to earn autocracy points. Voting for a small, hand-picked set of laws stains your party too — but only laws that fit one specific test.

### The boundary: does it stop voters removing the government?

The score has never been about being harsh, illiberal, or tough on crime — it fires when a party **uses state power against the people who could remove it from office**. The same test now applies to legislation. A law scores autocracy points only if it dismantles the mechanisms that let voters and rivals hold the government to account: press control, protest bans, mass surveillance, martial law, no citizenship rights, and similar.

Laws that are merely harsh — the **death penalty**, **zero-tolerance policing**, **drug prohibition**, restrictive **dress codes**, and the like — deliberately score **nothing**, however illiberal they read. A party can win a fair election on those positions and govern legitimately; the game already prices them through issues like Individual Liberty and Law and Order. Only laws that remove the *means of losing power* count here.

### The three tiers

Only a curated set of options across the law catalogue carry points. Everything else — including every other rung of these same laws — scores **0**.

**Tier 1 — dismantles political competition · +20 points**

| Law | Option |
| --- | --- |
| Media Censorship | Total information control |
| Media Censorship | Strict censorship |
| Public Broadcasting | All channels replaced by state propaganda |
| Right to Protest | Public protest effectively banned |
| Internet Freedom | State-controlled intranet only |
| Surveillance Policy | Total surveillance |
| Automated Surveillance | Mass AI surveillance and social scoring |
| Police Powers | Martial law |
| Citizenship Policy | No citizenship rights |

**Tier 2 — serious erosion · +10 points**

| Law | Option |
| --- | --- |
| Right to Protest | Heavily restricted, easy to ban |
| Internet Freedom | Heavy internet censorship |
| Surveillance Policy | Mass surveillance |
| Automated Surveillance | Broad facial recognition & predictive policing |
| Data Privacy | Citizens must share all personal data with the state |
| Curfew Policy | Universal curfew |
| Official Language Policy | Mandatory state-constructed language |
| Government Transparency | Government business secret by default; leaking a serious crime |

**Tier 3 — weakens accountability · +5 points**

| Law | Option |
| --- | --- |
| Identity Cards | Mandatory biometric ID + central register |
| Press Regulation | Statutory press regulator with powers |
| Blasphemy Law | Strict blasphemy laws |
| Police Body Cameras | No cameras; filming the police is a criminal offence |
| Anti-Corruption Commission | Commission appointed and directed by ministers |

### Restoration credit

Reversing an erosion pays credit back, the same way a [pardon](#issue-pardon) offsets an arrest:

| Law | Option | Points |
| --- | --- | --- |
| Media Censorship | Free press | −5 |
| Right to Protest | Unrestricted right to assemble | −5 |
| Government Transparency | Open by default; contracts, meetings and expenses published | −3 |
| Anti-Corruption Commission | Independent commission with its own prosecutors | −3 |

The points above are charged for **new** erosion only. Moving a law from an unscored option to a Tier 1 option costs the full 20; stepping it up from a Tier 2 option to a Tier 1 option costs the 10 points of difference; and swapping between two options of the same tier, or loosening a Tier 1 law to Tier 2, costs nothing (and pays nothing back).

One law **starts** on a scored option: most countries begin with their anti-corruption commission appointed and directed by ministers. Starting there costs nobody anything — points are only charged to the parties that *vote a change through*, never to the country's inherited position. The +5 can only be taken by a party that actively rolls the law back from a more independent arrangement.

Restoration credit is only paid when the law is being moved **away from an option that itself carries points** — and never more than that option carried. Moving a *moderate, unscored* law straight to free press pays nothing, and moving it back doesn't cost anything either. That closes off the obvious farm: you can't toggle a law between an ordinary default and a restoration option to rack up free credit, because no erosion ever happened to restore.

### Who pays, and how much

- The **proposing party** pays the **full** points shown above.
- Every other party that votes **Yes** pays **half** — because voting yes is endorsing the law too, just with less ownership of it.
- This includes parties with **zero seats**. Their vote carries no weight and changes no outcome, but it's still a public recorded position, and it's stained the same as anyone else's.
- An **omnibus bill** (multiple articles in one proposal) is capped at **20 points per proposal**, applied before the halving above — so stacking five Tier 1 articles into one bill still costs the proposer 20 points, not 100.

Points are only written when a bill **actually passes and changes the law**. A **vetoed** bill, a **failed** bill, or an article that merely **re-affirms** the law a country already has scores nothing — the ledger records what was *done to the country*, not what was merely proposed or wished for.

### The notice before you vote

Any proposal containing a scored article shows a notice before you cast your vote, naming **your own party's** point delta — full if you're proposing it, half otherwise — and the reputation band it would move you to *if the bill passes*. Nothing is hidden until after the fact: you always know the cost of a "Yes" before you commit to it.

## Next steps

- [Constitution](constitution.md) — how powers are assigned to offices, and how to move (or disarm) them.
- [Hereditary Monarchy](monarchy.md) — the Crown, the veto, and the constitutional-crisis mechanic.
- [Campaign Events](campaigning.md) — what a public-events ban shuts down.
- [Legislation & Voting](legislation.md) — how proposals are drafted, debated and passed.
