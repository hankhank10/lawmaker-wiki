# Executive Actions & the Autocracy Score

The [constitution](constitution.md) decides *who holds which powers*. **Executive actions** are what those powers let you do to others: silence a rival party, have a politician arrested. They have **no cooldown and no hard cap**. The only checks are the **autocracy score**, which costs votes at every election, and, for a monarch, the security of the throne.

## Who can act

Each action is gated by one constitutional power, and whoever currently holds that power can use it. Everyone can see the full list of actions, and why one is unavailable to them.

| Power held by | Who acts |
| --- | --- |
| **Cabinet position** | The party of the current appointee. Unavailable while the post is vacant or the appointee has no party. |
| **Elected office** (e.g. a presidency) | The party of the current holder. Unavailable while the office is vacant. |
| **Monarchy** | The reigning monarch (see [below](#monarchs-and-the-constitutional-crisis)). Unavailable while the throne is vacant. |
| **Multi-seat legislature** | Nobody. The chamber holds the power collectively. |
| **Non-partisan bureaucrats** | Nobody. The power is deliberately disarmed. |

Handing a power to bureaucrats through a [constitutional change](constitution.md) is how a country takes a dangerous action off the table.

## The autocracy score

Every autocratic act a party commits is written to a permanent public **ledger**, and its **autocracy score** is computed from that ledger. Each entry contributes its points, then **decays linearly to nothing over 2 game years**. A party that never acts autocratically sits at **0** forever. The ledger has three sources: executive actions, [authoritarian laws](#authoritarian-laws), and [restricting the franchise](#restricting-the-franchise).

The score drives two things:

- **A reputation badge** on the party: **Committed to Democracy** (0), then **Autocratic Leanings** (from 10), **Worryingly Autocratic** (from 25) and **Terrifyingly Autocratic** (from 50).
- **An election penalty.** At every election, voters are less likely to choose an autocratic party. The penalty grows smoothly with the score (0.5% of your vote preference per point) up to a ceiling of **half** your vote preference.

!!! warning "You can't wash the stain by refounding"
    Records committed by your **disbanded** parties follow you, their current owner, and keep decaying on the same 2-year clock. A second, concurrently live party of yours is unaffected.

## Monarchs and the constitutional crisis

A monarch has no party to stain, so the score can't touch them. Their price is the same one a royal veto carries: every royal executive action starts a **90-day [Constitutional Crisis](monarchy.md)**, or resets one already running. While it lasts, the threshold to pass a pure *abolish-the-monarchy* change is halved and such a package skips the usual constitutional-change cooldown. A monarch pays no PP.

## The actions

Every action costs a party **30 PP**. Each adds its points to the actor's ledger (negative points reduce the score, which never drops below 0, so freeing people can offset past acts but never earns a vote bonus).

| Action | Power needed | Autocracy points | Effect |
| --- | --- | --- | --- |
| **Ban party from public events** | Regulate political parties | +15 | Target can't organise [campaign events](campaigning.md) for **6 months**. |
| **Lift public events ban** | Regulate political parties | −10 (0 if you free your own party) | Ends a ban at once. |
| **Order arrest** | Head of the Police | +25 | Target politician detained for **12 months**. |
| **Issue pardon** | Grant pardons | −10 | Releases an arrested politician. |

**Ban party from public events.** The target's scheduled events inside the ban window are cancelled at once with **no refund** of money or activist energy, and they can't create, edit, move or copy events until it lapses. A party can't be banned again while already banned.

**Lift public events ban.** Only a party currently serving a ban can be freed, and anyone holding the power can do it, including a government that inherits the office from whoever imposed the ban. Cancelled events stay cancelled. You can free your own party, but it scores nothing: the −10 is credit for freeing someone else. Re-banning costs 30 PP and 15 points again, so cycling a rival in and out of a ban deepens your record rather than laundering it.

### Order arrest

Any active party politician can be arrested, including colleagues in your own party, with two exceptions: you can't target **yourself**, and a **sitting elected office holder** can't be arrested at all (only voted out). Candidates for an elected office and cabinet ministers are fair game.

An arrested politician, for **12 months** or until pardoned:

- **cannot run campaign events**, and events they were due to lead are cancelled with no refund;
- has their **candidacy ignored**, so their party's votes for that office go elsewhere;
- **keeps any cabinet seat but cannot use its executive actions**;
- **cannot post to social media**.

Nobody can be re-arrested while detained. A **pardon** undoes every effect at once.

## Authoritarian laws

Voting for a small, hand-picked set of laws also stains your party.

### The boundary: does it stop voters removing the government?

The score isn't about being harsh or illiberal. It fires when a party uses state power against the people who could remove it. A law scores only if it dismantles the means of holding a government to account: press control, protest bans, mass surveillance, martial law, no citizenship rights. Laws that are merely harsh, such as the **death penalty**, **zero-tolerance policing**, **drug prohibition** or restrictive **dress codes**, score **nothing**. A party can win a fair election on those positions, and the game already prices them through issues like Individual Liberty and Law and Order.

### The three tiers

Only these options carry points. Every other option of the same laws scores 0.

**Tier 1, dismantles political competition: +20**

- Media Censorship: Total information control; Strict censorship
- Public Broadcasting: All channels replaced by state propaganda
- Right to Protest: Public protest effectively banned
- Internet Freedom: State-controlled intranet only
- Surveillance Policy: Total surveillance
- Automated Surveillance: Mass AI surveillance and social scoring
- Police Powers: Martial law
- Citizenship Policy: No citizenship rights

**Tier 2, serious erosion: +10**

- Right to Protest: Heavily restricted, easy to ban
- Internet Freedom: Heavy internet censorship
- Surveillance Policy: Mass surveillance
- Automated Surveillance: Broad facial recognition and predictive policing
- Data Privacy: Citizens must share all personal data with the state
- Curfew Policy: Universal curfew
- Official Language Policy: Mandatory state-constructed language
- Government Transparency: Government business secret by default

**Tier 3, weakens accountability: +5**

- Identity Cards: Mandatory biometric ID and central register
- Press Regulation: Statutory press regulator with powers
- Blasphemy Law: Strict blasphemy laws
- Police Body Cameras: No cameras; filming the police is a criminal offence
- Anti-Corruption Commission: Commission appointed and directed by ministers

Points are charged for **new** erosion only. Moving from an unscored option to Tier 1 costs the full 20, stepping from Tier 2 up to Tier 1 costs the 10-point difference, and moving sideways or loosening costs nothing. The Anti-Corruption Commission starts on its scored option in most countries, but points are only charged to parties that *vote a change through*, never to the inherited position.

### Restoration credit

Reversing an erosion pays credit back:

| Law | Option | Points |
| --- | --- | --- |
| Media Censorship | Free press | −5 |
| Right to Protest | Unrestricted right to assemble | −5 |
| Government Transparency | Open by default | −3 |
| Anti-Corruption Commission | Independent commission with its own prosecutors | −3 |

Credit is only paid when the law leaves an option that itself carried points, and never more than that option carried. You can't farm it by toggling a law between an ordinary default and a restoration option.

### Who pays, and how much

- The **proposing party** pays the **full** points.
- Every other party that votes **Yes** pays **half**, including parties with zero seats.
- An **omnibus bill** is capped at **20 points** before the halving, so five Tier 1 articles in one bill still cost the proposer 20.

Points are only written when a bill **actually passes and changes the law**. A vetoed bill, a failed bill, or an article that merely re-affirms the current law scores nothing. Any proposal containing a scored article shows your own point cost and the reputation band it would move you to before you vote.

## Restricting the franchise

Amending who may vote, by gender, age, employment, income, education or housing, is priced like an authoritarian law: fixed points per option, the proposing party pays in full, other yes voters pay half, and points are written only once the change is applied. There is no cap, so stacking restrictions in one package charges for all of them. Loosening a restriction pays some credit back. See [Suffrage](constitution.md#suffrage) for the points table and worked examples, and [Suffrage Crisis](elections.md#suffrage-crisis) for what happens when enough people lose the vote at once.

## Next steps

- [Constitution](constitution.md): how powers are assigned to offices, and how to move or disarm them.
- [Hereditary Monarchy](monarchy.md): the Crown, the veto and the constitutional crisis.
- [Legislation & Voting](legislation.md): how proposals are drafted, debated and passed.
