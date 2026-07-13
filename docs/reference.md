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
| [Recruit a character](gameplay/characters.md) | 10 PP |
| [Commission a poll](gameplay/elections.md#polling) | 10 PP |
| [Expel a character](gameplay/characters.md#expelling-and-free-agents) | 25 PP |
| [Form a government](gameplay/cabinet.md) | 30 PP |
| [Call an early election](gameplay/elections.md#early-elections) | 30 PP (10 PP if no party holds seats) |
| [Change a pillar](gameplay/parties.md#changing-a-pillar) | 75 PP |
| [Constitutional change](gameplay/constitution.md) | 30 PP per item (min 60 PP); 60 PP to establish or abolish a monarchy |
| [Found an international bloc](gameplay/communication.md#international-blocs) | 50 PP |
| [Apply to a bloc](gameplay/communication.md#international-blocs) | 20 PP |

**Free actions:** voting on proposals, sending messages, commenting on proposals, browsing — all cost 0 PP. Nominating an activist for a vacant throne is also free (but winning has heavy consequences).

## Voting periods & thresholds

| Vote | Window | To pass |
| --- | --- | --- |
| Normal proposal | 60 game days | Simple majority (Yes > No), weighted by seats |
| Budget | 60 game days | Simple majority of filled seats |
| Cabinet formation | 60 game days | Majority support (all proposed parties must vote yes) |
| Constitutional change / amendment | 60 game days | Supermajority (typically ~66.6%), in **every** required chamber |
| Early-election call | 60 game days (5 if no party holds seats) | Passes unless ≥50% oppose |

In **bicameral** countries a proposal must clear its threshold in all required chambers. Abstentions never count toward either side.

## Key timers

| Timer | Value |
| --- | --- |
| Inactivity warning email | after 3 days |
| Auto-disband for inactivity | after 5 days (only if the country is ≥70% full) |
| Early election held after a successful call | 10 game days later |
| Auto early election (legislature drops below 50% occupancy) | held 10 game days later, no PP cost, no vote |
| Constitutional-change cooldown | ~2 years after a successful change |
| Constitutional Crisis mood | 90 days (resets on a further veto) |
| Economic Miracle / Crash mood | ~2 years |
| [Global decision](gameplay/global-decisions.md) voting window | 24 game days, same for every country |

## Turnout & vote-preference modifiers

| Modifier | Effect | Duration |
| --- | --- | --- |
| Custom party logo | +5% supporter turnout | permanent while set |
| No party logo | −5% supporter turnout | until a logo is added |
| Energised Base (successful Supporter Rally, 10% chance) | +20% supporter turnout | 10 game days |
| Campaign Finance Scandal (random event) | voters 10% less likely to back you | 3 months |
| Performance-event outcomes (interview / speech / stunt) | vote-preference boost or penalty | varies (a *Career-Defining* speech is permanent) |
| No bill front person | −5% persuasiveness on that proposal | that proposal |

## Party basics

- **One active party per account**, and one party per country (use a separate account per country).
- A party chooses **4 pillars** from the **16 political issues** when it's created.
- A proposal bundles **1–5 articles** (each changing one law). There are **95 laws** across 21 policy areas.
- Voter opinion is roughly **70% your law record, 30% your budget record** (a per-country setting).
