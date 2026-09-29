# Elections & Voters

Elections turn your voting record into seats. Understanding how electors think is the single most important skill in Lawmaker — everything you do is ultimately judged by them.

## How elections work

Elections run on a **regular schedule** set per legislature (the next date is shown on your country dashboard), and every party participates automatically. On election day the electors vote and the count begins — live. Once the ballots are fully counted, seats are allocated **proportionally** to each party's vote share; the new legislature and [government formation](cabinet.md) then take effect overnight, once the day's count is confirmed.

A country's [elected offices](#elected-offices), such as a presidency, are elected in the same count, on their own schedules, but go to a single candidate instead of being split into seats.

Afterwards you'll see each party's vote totals and percentages, seats won, turnout, and the change since last time.

### Watching the count live

Counting isn't instant: ballots are tallied in batches over the course of election day, so the result takes shape in front of you rather than simply appearing. A country's **Election Centre** (linked from its dashboard, or from the "How do elections work?" wiki icon on the page itself) shows the running count as it happens — percentage of ballots counted, turnout among those counted so far, and a live chart of every party's vote share moving as votes come in. The page updates itself while counting is underway and settles once the final ballot is tallied.

The **Global Elections** page lists every count in progress anywhere in the world, and the World menu lights up whenever a count is underway somewhere — so a close race elsewhere doesn't pass you by.

## Understanding electors

Your country's population is modelled as a set of individual **electors**. Every elector has a job, income band, education, housing and religious background, a political worldview, and personal life goals. You can open any elector's profile to see what drives them, and a country's **Demographics** and **Issue Analysis** views show the shape of the electorate as a whole.

This is why elections feel real: electors actually read your record and respond to it.

### Retirement

Electors retire by **age**, not by chance. Once an elector reaches their country's retirement age they're shown as **Retired**, but they keep their working history on record — a profile might read "Retired — formerly a nurse in healthcare" — rather than losing their identity. The threshold itself is just the **Pension Age** law: raise it and electors below the new age go back to work immediately; lower it (or abolish pensions entirely) and more of the population retires at the next tick. There's no lag or transition — the change is visible the moment the law takes effect.

This has real economic teeth: a country's retired share of the population, shown on the [Economy page](economy.md), moves the labour force and GDP along with it, so pension policy is as much an economic lever as a social one. The one group it doesn't touch economically is the **elite** band, whose wealth keeps earning (and paying tax) in retirement — they still show as retired, they just don't stop contributing.

### Suffrage

Not every elector is guaranteed the vote. A country's constitution can restrict the franchise by gender, age, employment, income, education or housing — see [Suffrage](constitution.md#suffrage) for the full rules. Where it's in force:

- An elector who fails the country's franchise rules is shown as unable to vote, with the reason (for example *"Under the voting age of 25"*), and can be filtered for on the elector list.
- **Disenfranchised electors are left out of polls and election counts**, but the turnout figure still divides by the *whole* population — so a restricted franchise shows up as **lost turnout**, right alongside election and poll results, rather than as a separate statistic.
- If a country's franchise rules leave **fewer than 25** of its analysed sample electors eligible, the electorate is too small to safely stand for the whole country: no election is held that round, every seat stays with its current holder, and polls report "too few eligible voters" instead of a projected result.

### How an elector decides

1. They review how each party **voted** on proposals.
2. They compare those votes to **their own** positions and priorities.
3. **Recent votes count more** than old ones — your record is always live.
4. They form an opinion of each party and vote for the best match.

!!! example
    A committed environmentalist sees the Green Alliance voted for renewables and against coal subsidies, while the Business Party did the opposite. They vote Green — a clear match with their values.

!!! note "Budgets count too — about 30%"
    Voters judge you on more than laws. Each elector's view is roughly **70% your social-policy record (laws)** and **30% your financial record (budgets)** — they react to tax changes in their own income band and to spending shifts in areas they care about. A party that ignores budgets hands a free advantage to rivals. See [How budgets affect voters](economy.md#how-budgets-affect-voters).

!!! note "When no party has a positive opinion score"
    An elector's votes always go somewhere, even when nothing they've seen impresses them:

    - If every score is zero or negative, votes are split equally among the parties the elector is merely neutral about — not the ones they dislike.
    - If every known party is disliked, votes are split in proportion to how little each is disliked, rather than all going to whichever party is disliked least.
    - A party with **no recent voting record** is unknown to the elector, not neutral — it's excluded from both of the above and gets no votes by default, so a brand-new party can't sweep the disaffected vote just by having nothing on the record yet. The only exception is a country where no party has any record at all: then votes still split equally across all of them.

### Time-weighting

Recent votes dominate: the last 30 days carry the most weight, 30–90 days moderate weight, and anything over a year barely registers. Voters, like real ones, remember what you did lately.

## National moods

Beyond individual preferences, a country can carry **national moods** — trends that shift how voters weigh issues. A mood can push everyone slightly in one direction on certain issues, change how *important* an issue feels, or both. You'll see active moods on the country page; click one to see exactly what it affects.

Some moods are **permanent**, baked into a country's character when it's created:

| Mood | Effect on voters |
| --- | --- |
| **Traditional Culture** ⛪ | Toward traditional gender roles and religious influence; away from immigration |
| **Pioneer Spirit** 🤠 | Toward individual liberty and free markets; away from the welfare state |
| **Common Ground** 🫂 | Toward the welfare state and worker rights; away from free markets |
| **Stewards of the Land** 🌱 | Toward environmental protection; away from military strength |
| **Strength through Strength** 🗡️ | Toward military strength and law-and-order; away from immigration |
| **Citizens of the World** 🌍 | Toward gender equality and immigration; away from religious governance |
| **Patriarchal Society** 👨‍⚖️ | Toward traditional gender roles; gender issues weigh more heavily |
| **Deeply Polarised** ⚡ | No position shift — but *every* issue matters more to everyone |
| **The Great Disillusionment** 😑 | No position shift — every issue matters *less*; elections get noisier |
| **Nation Builders** 🏗️ | Toward infrastructure and education spending; away from environmental protection |
| **Silver Republic** 👴 | Toward support for older people; away from young people and immigration; elder issues weigh more heavily |
| **Secular Republic** 🏛️ | Toward secular governance and individual liberty; religious-governance issues weigh more heavily |
| **Bread and Circuses** 🍞 | No position shift — but wages, welfare, and prices weigh more heavily; culture-war issues fade |

Others are **event-triggered** and attach automatically when something happens in the game: a **Constitutional Crisis** (a monarch vetoes a passed bill — see [Hereditary Monarchy](monarchy.md#constitutional-crisis)), a **Constitutional Convention** (called by the head of government or the monarch, or at a new country's founding; it doesn't move voters, it only relaxes the rules for constitutional change for a year — see [Constitutional conventions](constitution.md#constitutional-conventions)), a **Suffrage Crisis** (below), or an **Economic Miracle / Crash** that bends the country's growth rate (see [Economy](economy.md#national-moods-and-economic-growth)).

When a mood lines up with your platform, it's a tailwind — propose into it. When it's against you, focus elsewhere and wait, since temporary moods pass.

### Suffrage Crisis

🗳️🔥 **Suffrage Crisis** is a temporary mood that attaches automatically when a constitutional [Suffrage](constitution.md#suffrage) change strips the vote from at least 10% of the electors who could vote immediately before it — including a package that hands the vote to some people while taking it from others, such as a gender swap, as long as enough people lose out. Like a Constitutional Convention, it doesn't skew any elector's positions or issue importance; what it changes is the rulebook for constitutional change itself, not how anyone votes.

- **It lasts 180 days**, and restricting the franchise again while it's active resets the clock.
- **It makes reversing the restriction easier:** while it's active, a package made up only of Suffrage changes that are each unchanged or less restrictive votes at **half** the usual threshold and can be opened even during the normal constitutional-change cooldown.
- **It won't expire while the country's electorate is too small to hold an election** (see [Suffrage](constitution.md#suffrage) and [Understanding electors](#suffrage) above) — every poll and election run refreshes it instead, so a country locked out of voting by its own rules always has a cheaper way back open to it.

## Elector satisfaction

In countries with an economy, each elector also has a **satisfaction** score: how happy they are with the *state of the country*, separate from their opinion of any party. It's driven by how your country's finances compare to similar **peer countries** — mostly the tax rate on their income band (about 70%) and government spending on the issues they care about (about 30%). Tax or spend more favourably than your peers and satisfaction rises; fall behind and it drops.

Satisfaction is a **diagnostic, not a direct vote-changer**. High satisfaction favours incumbents defending the status quo; low satisfaction opens the door for opposition parties running on change. It shows up on polls, elector profiles, and — when it tips into a notable band — as a mood badge on the country page, and only refreshes when a poll or election happens.

## The electoral system

Lawmaker uses **proportional representation**: roughly, vote share equals seat share (10% of votes → ~10% of seats). Small parties can win seats, no one usually wins an outright majority, and coalitions are the norm. Some legislatures also set a **minimum threshold** (often ~5%) below which a party wins no seats — check your country's rules.

```
Party seats ≈ (party votes ÷ total votes) × total seats
```

Seats are allocated using the **D'Hondt method** (highest averages), the same system used in Spain, Portugal, Poland and Israel. It guarantees that a party with over half the vote wins at least half the seats — and a strict majority whenever the chamber has an odd number of seats — so a decisive election winner can actually form a government instead of being locked out by rounding. It's a touch kinder to large parties than a pure remainder-based count would be; that's the trade that buys the guarantee.

### Turnout

Not every elector votes every time. Controversial recent proposals and close races push turnout up; long inactivity pushes it down. **Party branding matters here**: a custom [logo](parties.md#party-branding) gives a +5% turnout boost among your supporters, and going without costs you 5%.

## Polling

Any party with an active presence can **commission a poll for 10 PP** to see projected vote shares, turnout, and seat estimates based on current opinion — a snapshot, not a guarantee, since voters keep reacting to new votes right up to election day.

- **Private polls** keep the results to you — good for secret strategy, but you can't share them as proof.
- **Public polls** are visible to everyone — useful for building trust with coalition partners and setting expectations.

Any logged-in user can *view* public polls; only active parties can commission them.

## Early elections

A party can trigger an election before the scheduled date for **30 PP** (just 10 PP if the chamber voting on the call holds no seats). It's put to a vote over a 60-day window and goes ahead unless opposition reaches 50%. Leading parties use this to lock in gains; opposition parties vote it down to deny them the moment. [Elected offices](#elected-offices) have their own kind of call.

**The motion concludes early** if the outcome becomes mathematically certain before the 60-day window ends — that is, once yes has secured more than 50% of occupied seats (it will pass), or once yes can no longer reach 50% no matter how remaining votes fall (it will fail). This applies even if votes are still incoming.

### Automatic early elections

The game calls an **automatic** early election (no vote, no PP) in two cases, holding it 10 game days later:

- **A chamber empties below 50% occupancy**, usually after a governing party is disbanded.
- **An elected office is vacant**, has held an election before, and at least one party has a valid candidate standing for it. See [Elected offices](#elected-offices) below. An office that has never held an election waits for its first scheduled one.

An [upheld impeachment](supreme-court.md) schedules the same election directly, without waiting for either check.

## Elected offices

An **elected office** is a single post, such as a presidency, held by one person and elected by the voters. Countries name their own offices and decide how often each is elected. Unlike a chamber, an office has no seats and no proportional count: it goes to one **candidate**, and the [constitution](constitution.md) says whether it has a [veto](legislation.md#elected-office-veto), whether it heads the government, and which powers it holds.

### Candidacies

Each party can put up **one candidate per office**, chosen from its own activists. Declaring or changing a candidate costs **20 PP**.

- **One office per character.** A character can stand for only one office at a time, and can't stand for a second office while holding one. A refused candidacy costs nothing.
- **Who can stand.** The candidate must be an activist of your party who isn't retired or expelled, and who hasn't been [removed from that office by the Supreme Court](supreme-court.md). You can declare an [arrested](executive-actions.md#order-arrest) activist, but their candidacy is ignored at the count for as long as they're under arrest.
- **Locked during a count.** You can change or withdraw your candidate at any time except while a count that includes the office is running.
- **It stays on file.** A candidacy carries over after the election, so a sitting holder stands again by default. A candidacy that stops being valid, say because the candidate retires, stays on file but is ignored when the votes are counted.

### Winning the office

Offices are counted in the same election as the country's chambers, using the same electors. Votes for a party with no valid candidate aren't wasted: they go to the candidates in proportion to the votes each candidate's party won. The candidate with the most votes wins, and a tie is settled at random. If there's no valid candidate at all, nobody wins, and the office is left **vacant**. If the country's electorate is [too small](#suffrage) to hold an election, the holder stays and the schedule moves on.

The winner **takes office when the election is processed**, and holds it until the office's next election is processed or it falls vacant. **The holder is fixed at election.** Changing a party's candidate afterwards never changes who holds the office. A cabinet formation that the office was appointing is cancelled after every election held, whoever won.

### Vacancies

An office falls vacant **at once**, with no successor, when:

- the Supreme Court upholds an [impeachment](supreme-court.md) (the holder is also barred from that office for good);
- the holder is **expelled** from their party;
- the holder's party is **disbanded**;
- the holder **retires**; or
- the holder no longer qualifies for any other reason, which a daily check picks up (for instance, a holder who accedes to the throne).

A journalist post and an activity event announce the vacancy. While the office is vacant:

- its **powers are unavailable**, so nobody can use them;
- it has **no veto**;
- it is **nobody's head of government**;
- if it appoints the cabinet, **no new cabinet can be formed**, though the sitting cabinet stays.

Only an election fills it. An election that finds no candidate leaves the office vacant. Once an office has held an election, the game refills it automatically: if it's vacant and at least one party has a valid candidate standing, an [automatic early election](#automatic-early-elections) is held 10 game days later. Nobody standing means an election nobody could win, so a party that wants the seat filled sooner should put a candidate up for it.

### No-confidence and vacant-office calls

A single occupant can't send their own office to the country, so a call on an office is decided by another chamber, the one named in the constitution as its **no-confidence chamber**. What the call is depends on whether anyone holds the office:

- **The office is held.** It's a **vote of no confidence** in the holder, costing **30 PP** and needing the constitution's no-confidence threshold (typically 75% of votes cast) in the deciding chamber. Win it and the office goes to an early election. The holder serves until that election.
- **The office is vacant.** There's no holder to withdraw confidence from, so it's simply a call to refill the office: **10 PP**, and a **simple majority** in the deciding chamber is enough.

Either way, abstentions are ignored and the election is held 10 game days after the voting period ends.

## Next steps

- [Legislation & Voting](legislation.md) — the record electors judge you on.
- [Economy](economy.md#how-budgets-affect-voters) — how budgets feed into voter opinion.
- [Government & Cabinet](cabinet.md) — forming a government after you win.
- [Suffrage](constitution.md#suffrage) — restricting who can vote, and what it costs.
- [Strategy Guide](../strategy-guide.md) — positioning, timing, and winning elections.
