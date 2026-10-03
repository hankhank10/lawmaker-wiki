# Quick Reference

Every number in one place. The detailed guides explain *why* each of these matters; this page is the at-a-glance lookup, and the rest of the manual links here rather than restating the figures.

## Game time

- **1 real-world hour = 1 game day.**
- 1 real day ≈ 24 game days; a typical election cycle plays out over a few real-world weeks.

## Political Power (PP)

PP is the action currency. You earn it over time and spend it on major moves.

- **Starting amount:** 100 PP
- **Generation:** +1 PP per game day (per real hour)
- **Cap:** 120 PP (generation beyond the cap is wasted)

Generation is multiplied by the power you hold (modifiers compound):

| Condition | Bonus |
| --- | --- |
| Head of State | +20% |
| Each cabinet position held | +10% |
| Holding any multi-seat legislature seats | +10% |
| Holding a legislature majority | +10% |

### Action costs

| Action | Cost |
| --- | --- |
| [Propose a law](gameplay/legislation.md) | 30 PP |
| [Propose a budget](gameplay/economy.md#how-budgets-affect-voters) | 30 PP |
| [Recruit a character](gameplay/characters.md#recruiting-activists) | 10 PP while you have fewer than 10 activists; from then on, your roster size + 1 (the 11th costs 11 PP, the 21st 21 PP) |
| [Expel a character](gameplay/characters.md#expelling-and-free-agents) | 25 PP |
| [Form a government](gameplay/cabinet.md) | 20 PP (10 PP when every cabinet post is vacant) |
| [Call an early election](gameplay/elections.md#early-elections) | 30 PP (10 PP if the chamber voting on the call holds no seats) |
| [Declare a candidate for an elected office](gameplay/elections.md#candidacies) | 20 PP to declare or change; free to replace a candidate who can no longer stand |
| [Endorse another party for an elected office](gameplay/elections.md#endorsements) | Free (0 PP) |
| [Vote of no confidence in an elected office](gameplay/elections.md#no-confidence-and-vacant-office-calls) | 30 PP (10 PP if the office is vacant) |
| [Change a pillar](gameplay/parties.md#changing-a-pillar) | 50 PP |
| [Constitutional change](gameplay/constitution.md#what-can-be-amended) | 30 PP per standard change, 60 PP per major change (min 60 PP per package); required follow-on changes are free. Capped at 75 PP per package during a [constitutional convention](gameplay/constitution.md#constitutional-conventions) |
| [Call a constitutional convention](gameplay/constitution.md#constitutional-conventions) | 75 PP (head of government); free for a reigning monarch |
| [File a Supreme Court appeal](gameplay/supreme-court.md#bringing-a-case) | 60 PP (refunded if no justice can sit, or an impeached office changes party) |
| [Executive action](gameplay/executive-actions.md): ban a party, order an arrest | 40 PP each; free for a monarch |
| [Executive action](gameplay/executive-actions.md): lift a ban, issue a pardon | 15 PP each; free for a monarch |
| [Found an international bloc](gameplay/communication.md#international-blocs) | 50 PP |
| [Apply to a bloc](gameplay/communication.md#international-blocs) | 20 PP (refunded if the bloc's leaders deny it) |
| [Commit to a Major Project](gameplay/major-projects.md) | 50 PP (never refunded) |

**Free actions:** voting on proposals (each vote states a public reason), sending messages, browsing, and treaty actions all cost 0 PP. Nominating an activist for a vacant throne is also free (but winning has heavy consequences).

## Party funds (dollars)

Party funds are separate from PP. You start with none and earn them from fundraising events. See [Campaign Events](gameplay/campaigning.md).

| Spend | Cost |
| --- | --- |
| [Poll](gameplay/elections.md#polling): quick / extensive / comprehensive | $5,000 / $15,000 / $30,000 |
| Supporter Rally | $20,000 |
| Media Interview / Viral Stunt / Set-Piece Speech | $2,000 / $3,000 / $15,000 |
| Grassroots Canvassing / Town Hall Tour / Issue Ad Campaign | $12,000 / $18,000 / $30,000 |
| Private Dinner / Telethon | Free, earn about $25,000 / $10,000 |

## Voting periods & thresholds

| Vote | Window | To pass |
| --- | --- | --- |
| Normal proposal | 60 game days | Simple majority (Yes > No), weighted by seats |
| Budget | 60 game days | Simple majority of filled seats |
| Cabinet formation | 60 game days | Yes votes reach the legislature's approval threshold of *all* seats (a majority by default), **and** every party that nominated a minister votes Yes |
| Constitutional change / amendment | 60 game days | Supermajority (typically ~66.6%), in **every** required chamber |
| Early-election call | 60 game days (5 if no party holds seats in the voting chamber) | Passes unless ≥50% oppose |
| No-confidence vote (elected office) | 60 game days | Constitution's threshold (typically 75%) of votes cast — a simple majority while the office is vacant |

In **bicameral** countries a proposal must clear its threshold in all required chambers. Abstentions never count toward either side.

## Key timers

| Timer | Value |
| --- | --- |
| Inactivity warning email | after 3 days |
| Auto-disband for inactivity | after 5 days (only if the country is ≥70% full) |
| Early election held after a successful call | 10 game days later |
| [Run-off](gameplay/elections.md#run-offs) after an elected-office first round | 1 game day later (about an hour of real time) |
| Changing or withdrawing an [endorsement](gameplay/elections.md#endorsements) for the same office | at most once per game day (about an hour of real time) |
| [Major Project](gameplay/major-projects.md#who-can-commit) cooldown | 12 game months from the party's last commitment |
| [Major Project](gameplay/major-projects.md#who-can-commit) minimum party age | 12 game months (or hold power) |
| [Major Project](gameplay/major-projects.md#which-election) commit window | opens 12 game months before the next election, closes 10 game days before it |
| Auto early election (legislature drops below 50% occupancy) | held 10 game days later, no PP cost, no vote |
| Constitutional-change cooldown | set by Article II of each constitution (0–5 years, 1 by default); suspended during a constitutional convention |
| [Constitutional Convention](gameplay/constitution.md#constitutional-conventions) mood | 1 year (365 game days); new countries start with one |
| Cooldown between constitutional conventions | 10 years after the last one ends |
| Constitutional Crisis mood | 90 days (resets on a further veto) |
| [Suffrage Crisis](gameplay/elections.md#suffrage-crisis) mood | 180 days (resets if the franchise is restricted again; stays active while too few electors are eligible) |
| Economic Miracle / Crash mood | ~2 years |
| [Global decision](gameplay/global-decisions.md) voting window | 24 game days, same for every country |

## Modifiers and suffrage

Turnout and vote-preference modifiers (logo, Energised Base, scandals, court outcomes, pledges) are listed in [Campaign Events](gameplay/campaigning.md#party-modifiers); a custom party logo is worth **+5%** turnout and having none costs **5%**. A bill with no front person loses **5%** persuasiveness. The suffrage rules and costs are in [Constitution](gameplay/constitution.md#suffrage).

## Party basics

- **One active party per account**, and one party per country (use a separate account per country).
- A party chooses **4 pillars** from the **16 political issues** when it's created.
- A proposal bundles **1–5 articles** (each changing one law). There are **148 laws** across 20 policy areas.
- Voter opinion is roughly **70% your law record, 30% your budget record** (a per-country setting).
- Each country caps how many parties can exist in it at once — **7 by default**, though individual countries can be set higher or lower. Once a country hits its cap it shows **Country full** and won't let a new party be founded there until one disbands.
