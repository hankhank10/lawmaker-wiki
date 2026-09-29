# Constitution & Constitutional Changes

Every country has a **constitution**: the rules that set out how it is governed. It names the country, its legislatures and elected offices and how often they are elected, who heads the government, who appoints the cabinet, which cabinet positions exist, and how the constitution itself can be changed.

It also decides *who holds which powers*. It assigns specific powers (declaring war, appointing judges, setting monetary policy, granting pardons, and so on) to one of five kinds of holder:

- a **legislature** (an elected chamber),
- an **elected office** (a single post such as a presidency, held by one person),
- a **cabinet position** (whoever holds that office),
- the **monarchy** (in countries with a [Crown](monarchy.md)), or
- **professional non-partisan bureaucrats** (an independent civil service, outside political control).

There are **18 such powers** in all, spanning the military and intelligence services, foreign policy, the courts, economic regulation, and clemency. Each country starts with a different arrangement. (One power, **Ratify Foreign Treaties**, is special: it must always sit with a single office, never a chamber or the bureaucrats. See [International Treaties](treaties.md#who-decides-the-treaty-power).) Parties can propose **constitutional changes** to move powers around and to rewrite much of the rest of the constitution, reshaping how the country is governed.

## What can be amended

Every part of the constitution is either **Amendable** or **Entrenched**, and the constitution page shows which. Entrenched articles carry a closed padlock 🔒: *"Entrenched: this part of the constitution cannot be amended"*. Amendable parts carry a pencil ✏️; hover over it to see exactly what an amendment can change there.

| Part of the constitution | Status | Cost |
| --- | --- | --- |
| Official name (must still end in the common name) | Amendable | Standard |
| Election frequency of any chamber or elected office | Amendable | Standard |
| Who holds each power | Amendable | Standard, per power moved |
| No-confidence rule for an elected office | Amendable (can't be removed) | Standard |
| Whether an elected office has a veto | Amendable | Major |
| Renaming a cabinet position | Amendable | Standard |
| Monarchy name and titles | Amendable | Standard |
| Adding or repealing an amendment | Amendable | Standard |
| Establishing or abolishing the monarchy | Amendable | Major |
| Creating or abolishing a cabinet position | Amendable | Major |
| Head of government | Amendable | Major |
| Who appoints the cabinet | Amendable | Major |
| Seat count of a chamber | Amendable | Major |
| Article II: thresholds, required chambers, cooldown | Amendable | Major |
| [Suffrage](#suffrage): who may vote | Amendable | Major |
| The country's common name | Entrenched | |
| Which chambers and elected offices exist | Entrenched | |
| Legislature names | Entrenched | |
| The Supreme Court | Not amendable by players | |

**Cost:**

- **Standard** changes cost **30 PP** each.
- **Major** changes cost **60 PP** each.
- A package costs at least **60 PP** in total.
- **Dependent changes**, the ones added automatically because another change requires them, are **free**. Abolishing a ministry that holds four powers costs 60 PP, not 180 PP.
- During a [Constitutional Convention](#constitutional-conventions), a package costs **no more than 75 PP**, however many changes it holds.

Some rules the game uses aren't part of the constitution at all, so they can't be amended: the pass thresholds for ordinary laws, the maximum number of parties, how a monarch is chosen, and the parliament's seating style.

## Proposing a change

Constitutional changes are made in **packages**. A package can hold many changes, is voted on as a whole, and either all of it applies or none of it does. A package:

- has a **name** and a **description**, which is where you make your case;
- costs the total of its changes (see [the cost rule](#what-can-be-amended)), at least **60 PP**;
- requires a **supermajority** in every required chamber (see [Article II](#article-ii-the-amendment-rule)), not a simple majority;
- runs for a **60-day** voting period, with the proposing party automatically voting Yes;
- is limited to **one open package per country at a time**.

After a package passes there's a **cooldown** before another can be opened, set in Article II. A [Constitutional Convention](#constitutional-conventions) suspends the cooldown while it sits. A package can resolve early if it already has the votes, or if too many No votes make the threshold impossible. The proposer can withdraw at any time, but the PP isn't refunded once voting has opened.

### Drafting

Press **Propose amendments** at the top of the constitution page to open your party's draft (it's created if you don't have one). While drafting:

- every amendable article has an **Amend** control that opens an editor inside the article, with steppers for numbers, dropdowns for choices, and text boxes for names and wording;
- power chips can be dragged to a new holder;
- entrenched articles show the lock;
- **+ Add cabinet position** and **+ Propose new amendment** add new articles;
- your changes appear in place as **tracked changes**: old wording struck through, new wording highlighted.

A **draft bar** stays on screen with your change count, PP cost and number of problems, for example *"Your draft: 4 changes · 150 PP · 1 problem"*. Any problem is shown in red on the article it affects, with the reason. You can save a draft with problems, but you can't open it for voting until they're fixed. Press **Review & open** to check the package and open it.

You don't write a title or summary for each change: the game describes each one for you (*"The National Assembly is elected every 48 months (currently 60)"*). You can add an optional note to any change.

### Package rules

- **One change per thing.** A package can hold only one change to any single thing: one per power, one per chamber for each rule, one per cabinet position, one official name, and so on.
- **Fixed apply order.** When a package passes, things it creates are applied first, then modifications, then removals. The order you list changes in is only for display, so reordering can never break a package.
- **You can use what you create, not what you remove.** A power can move to a cabinet position created in the same package, or to a monarchy the package establishes. You can't give anything to a position or monarchy the package abolishes. You can't establish and abolish the monarchy in one package, or repeal an amendment the same package adds.
- **Nothing happens silently.** If one change forces another, the other is added to your package automatically, nested under it with a sensible default that you can edit. These dependent changes are free.

### How it differs from normal legislation

| | Normal proposal | Constitutional change |
| --- | --- | --- |
| **Cost** | 30 PP | 30 PP per standard change, 60 PP per major change (min 60) |
| **Threshold** | Simple majority (>50%) | Supermajority of **all seats** |
| **Chambers** | Usually one | Every chamber Article II requires |
| **Cooldown** | None | Set in Article II, 0–5 years (suspended during a [convention](#constitutional-conventions)) |

### Election frequency

You can change **how often a legislature or an elected office is elected** (2–120 months). It's a standard change and applies **prospectively**: the next already-scheduled election still runs under the old frequency.

### Seat counts

You can change the number of seats in a chamber, between **10 and 800**. It's a major change and takes effect at that chamber's **next election**, whether scheduled or early. Until then the article reads, for example, *"shall comprise 400 seats (450 from the next election)"*.

### No-confidence votes

Every elected office, such as a presidency, always has a **no-confidence rule**: exactly one chamber that can vote to remove it, and a threshold. The chamber must be an active legislature in the same country, and the threshold is **51%–100% of those voting**. You can change the chamber or the threshold, but you can't remove the rule. See [Elections](elections.md#elected-offices) for how a no-confidence call works.

### Elected office veto

An elected office can hold a **veto over bills**. While it's held and the veto is on, a bill that clears the legislatures still fails if the holder's party votes **No** on it. See [Legislation](legislation.md#elected-office-veto) for the details. A vacant office has no veto, and an office never has a say over budgets or constitutional changes.

The veto is on by default. A **major** change (60 PP) turns it on or off for a single office, and the constitution article for that office says whether it holds a veto. The setting is read when a bill closes, so a bill that is still open is decided under the rule in force **on the day it closes**, not the day it was proposed. Switching it off shows as a consequence on the package: the office will no longer be able to block bills.

!!! note "Two kinds of percentage"
    No-confidence thresholds count **those voting**. Amendment thresholds in Article II count **all seats**, so empty seats and parties that don't vote count against a package. The constitution always says which one it means ("75% of those voting", "67% of all seats").

## Article II: the amendment rule

Article II sets how the constitution itself is changed. Every part of it is amendable, and every change to it is **major** (60 PP).

- **Threshold per chamber:** **50%–90% of all seats**, in whole percentages. Some countries have an existing threshold such as 66.6%; it stays valid until someone amends it.
- **Required chambers:** which chambers must approve a package. Only chambers can be required (an elected office can't be), and **at least one** must stay required. Adding a chamber means setting its threshold too.
- **Cooldown:** **0–5 whole years** between successful packages. It doesn't apply while a [Constitutional Convention](#constitutional-conventions) is sitting.

A package is always voted on under the thresholds and required chambers **in force when it opened**. A package that lowers the threshold still has to clear the old, higher one. A package that changes the cooldown starts the **new** cooldown when it passes.

## Suffrage

Every country's constitution defines a **franchise**: who is allowed to vote. By default every country has **universal adult suffrage** — every analysed elector can vote — and the Suffrage article on the constitution page reads simply "Universal adult suffrage" until someone amends it. Restricting the franchise is a single **major** change (60 PP), one per country, and it can be combined with anything else in a package.

The franchise is set field by field, and each field defaults to the most inclusive option:

| Field | Options (default first) | Excludes |
| --- | --- | --- |
| Gender | All · Men only · Women only · Men and married women | The other gender, or unmarried women |
| Minimum age | 18 · 21 · 25 · 30 | Anyone younger |
| Maximum age | None · 80 · 70 · 60 · 50 | Anyone older |
| Employment | All · Employed only | Unemployed people of working age |
| Income | All · Medium and above · High and above | Anyone below the chosen band |
| Education | All · Secondary and above · Degree and above | Anyone below the chosen level |
| Housing | All · Homeowners only | Anyone who doesn't own their home |

- **Restrictions intersect.** An elector needs to pass every field you've restricted, not just one.
- **Age limits are inclusive at both ends.** A minimum of 21 still lets a 21-year-old vote, and a maximum of 70 still lets a 70-year-old vote.
- **Income bands:** low, medium, high, elite, the same bands used for tax. Elite earners always count as "high and above", whatever the setting.
- **Education is a ladder:** none → secondary → college → degree → postgraduate. "Secondary and above" only excludes electors with no education; "degree and above" also excludes secondary and college/technical.
- **Housing** looks at whether an elector owns their home (outright or with a mortgage); everyone else — renters, and anyone in between — is excluded by "homeowners only".

!!! note "Employment only excludes people of working age"
    "Employed only" doesn't touch retirees. It excludes an elector only if they're **unemployed and not retired**. A retiree keeps the vote whatever job they used to hold, and whether someone counts as retired follows the country's **Pension Age** law — so raising the pension age can quietly take the vote from older unemployed people who are no longer counted as retired, and lowering it (or abolishing pensions) gives it back. That happens automatically the moment the law changes: it's an ordinary policy change, not a constitutional one, so it costs no extra PP, adds no autocracy points, and starts no grudge (below). See [Retirement](elections.md#retirement).

**Timing.** The new rules take effect the moment the package is **ratified** — there's no transition period. The very next poll or election run in that country uses them. Sitting legislators are never unseated by a franchise change; like every clause but the seat count, it only affects the *next* election.

### How the disenfranchised react

A Suffrage package gets an elector opinion, the same way a law proposal does — the people it targets don't wait for an election to have their say:

- **Losing the vote is punished hard.** Every elector the package would exclude marks down any party that votes **yes** by a steep **−4**, worth more than any single law article. A party that votes **no** earns the opposite, a firm **+4** worth of goodwill, from the very same electors.
- **It bites before the result is known, and even if the vote fails.** The reaction starts the moment a party casts a yes or no vote on an *open* package, and it's still charged in full against a package that later **fails** — attempting to disenfranchise a group and losing the vote still costs you their trust. **Withdrawing** the package stops the reaction, but only from the day it's withdrawn; it still counted for as long as the package was open.
- **Restoring the vote earns a smaller reward.** When a package **gives** the vote to people who didn't have it, everyone it enfranchises rewards a **yes** vote with **+2**, and punishes a **no** with **−2** — half the swing of losing it, because getting a right back never feels as intense as losing it did.
- **Electors who keep the vote either way feel nothing from this.** They aren't part of the target group, so their opinion doesn't move here — they still react through the autocracy penalty below, so nobody is charged twice for the same package.
- **Grudges don't fade while the vote is lost.** A party's voting record normally fades out of electors' memories after a while, but a disenfranchised group's grudge is **paused**: the countdown only starts on the day the group's vote is **restored**, and it then runs for the usual window before it fades completely — so a group kept off the electoral roll for years carries the grudge, at full strength, the entire time. Restoring the vote and then taking it away again pauses the clock once more, and the next restoration starts it fresh.

### The cost of restricting the vote

Restricting who can vote is an act of autocracy, and it's charged through the same [autocracy score](executive-actions.md#the-autocracy-score) as executive actions and authoritarian laws — but only in a world that scores autocracy at all; in one that doesn't, the charge (and the warning below) simply drops the points and the reputation-band sentence.

Each option on each field carries fixed autocracy points, whatever share of the electorate it happens to affect:

| Field → option | Points |
| --- | --- |
| Gender → Men only / Women only | 75 |
| Gender → Men and married women | 55 |
| Minimum age → 21 / 25 / 30 | 10 / 20 / 30 |
| Maximum age → 80 / 70 / 60 / 50 | 10 / 20 / 35 / 50 |
| Employment → Employed only | 30 |
| Income → Medium and above / High and above | 40 / 60 |
| Education → Secondary and above / Degree and above | 15 / 50 |
| Housing → Homeowners only | 40 |

- **The proposing party pays in full; every other party that votes yes pays half.** The proposer always pays, whichever way it voted. Points are only charged once the package is actually **applied** — a failed or withdrawn package costs no autocracy, though it still costs the opinion above.
- **Moving a field further along costs the difference, not the whole thing.** Raising the minimum age from 18 to 21 and later to 30 costs **10 points, then 20 more** — 30 points either way, the same as going straight from 18 to 30 in one step.
- **Loosening a restriction only credits a fifth of what it removes**, and only on a field that's actually been restricted before — there's nothing to credit on a field still at its default. Restricting the vote to men only and then restoring universal suffrage costs **75** to erode and credits only **−15** to restore, netting **+60** for the round trip. Nothing can be laundered by eroding and restoring the same field.
- **Swapping between incomparable options is charged at the new option's full price, never credited as a restoration** — because each side of the swap takes the vote from people who had it. Moving from men-only to women-only costs the full **75**, not zero, and women-only to men-and-married-women costs the full **55**, even though the points went down, because unmarried women lose the vote in the swap.
- **There's no cap on a package's total**, so stacking every restriction into one package is charged in full and a round trip through all of them never nets below zero.
- **Traditional Culture moderates gender restrictions.** In a country carrying the [Traditional Culture](elections.md#national-moods) mood, the gender rows above are charged at **two-thirds** of their normal points (50 and 37) — no other field is affected.

### Suffrage Crisis

Take the vote from enough people at once and the country enters a **Suffrage Crisis** 🗳️🔥 — a temporary [national mood](elections.md#suffrage-crisis) that lasts **180 days**, resetting the clock if the franchise is restricted again while it's active. It's triggered whenever an applied package removes the vote from at least **10% of the electors** who could vote immediately before — including a mixed package, such as a gender swap, that gives the vote to some people while taking it from others; only the share who *lose* the vote is measured.

While a Suffrage Crisis is active, the way back is easier: a package made up of nothing but Suffrage changes that are each unchanged or **less restrictive** than before needs only **half** the usual voting threshold and can open even during the normal constitutional-change cooldown. Judged by who's excluded, not by points, so an incomparable gender swap never qualifies for the fast track even if its point cost happens to fall. Add any change that narrows the franchise, or any other kind of change, and the package loses the discount.

The crisis also **won't expire on its own while the electorate is too small to hold an election** (below) — every poll and election run refreshes it, so a country locked out of voting by its own franchise rules always has an open, cheaper route back.

### Too few eligible voters

If a country's franchise rules leave fewer than **25** of its *analysed* sample electors eligible to vote, the electorate is too small to safely stand for the whole country — with only a handful of voters, a tiny sample would decide every seat.

- **No election is held.** Every seat stays with whoever holds it. The election is still recorded, so the schedule moves on, but no votes are counted and seats are never split up some other way.
- **Polls show "Too few eligible voters to poll"** instead of a projected result.
- **The Suffrage Crisis mood stays active** the whole time this is true (above), so there's always a cheaper, faster way to reverse it.

### The warning before you vote

Any package that would take the vote from anyone shows a warning, on the draft and on the open vote, before you commit your party to it:

!!! warning "This amendment restricts who can vote"
    It would remove the vote from about **38% of voters (4.2 million people)**. If ratified, supporting it adds **+75 autocracy points** to your party, moving it from **Committed to Democracy** to **Terrifyingly Autocratic**. The people who lose the vote will turn sharply against every party that supports it — **even if it fails**. Removing the vote from this many people would trigger a **Suffrage Crisis**.

- **The figures are personal to you:** full points if you're proposing the package, half if you're only voting for it — and the projected reputation band updates to match.
- If the package would leave the country's electorate too small (above), the warning adds a line: *"Too few people would be able to vote for elections to be held. Every seat would stay with its current holder."*
- A package that **only restores** voting rights gets a green notice instead, naming the share who'd get the vote back and the autocracy credit it earns. A mixed package, such as a gender swap, still gets the red warning, with an extra line for how many people would gain the vote.

## Cabinet offices and government

These changes reshape who governs. All of them are major changes except renaming a position.

- **Create a cabinet position:** give it a name and a description. Powers can be moved to it in the same package.
- **Rename a cabinet position:** it keeps its identity, powers and sitting minister. Standard cost.
- **Abolish a cabinet position:** the sitting minister leaves office. The package must give each of the position's powers a new holder, and name a new head of government if the position held that role. You can't abolish the last cabinet position.
- **Head of government:** an elected office, a cabinet position, or the monarchy.
- **Who appoints the cabinet:** an active legislature, an elected office, or the monarchy. The sitting cabinet stays in office until the next formation, except that moving the appointing power **to or from the Crown** ends all appointments at once. A cabinet formation in progress when the change applies is cancelled.

### The monarchy

You can **establish** a monarchy, **abolish** it, or change its **name and titles**. See [Hereditary Monarchy](monarchy.md) for how the throne works.

Abolishing the monarchy automatically adds free dependent changes to your package: a new **head of government**, a new body to **appoint the cabinet**, and a new holder for **each power the Crown holds**. They come pre-filled with defaults, and you can edit any of them.

!!! info "Constitutional Crisis"
    During a [Constitutional Crisis](monarchy.md#constitutional-crisis), a package that abolishes the monarchy has its threshold **halved** and **skips the cooldown**, as long as it contains only the abolition and its automatic dependent changes. You can still edit those dependents, so you can choose where the Crown's powers go at the lowered threshold. Add any other change and the package loses both benefits.

## Amendments

Parties can also propose **amendments**: custom plain-text articles added to the constitution ("Freedom of speech is an inalienable right of every citizen"). They have no direct gameplay effect but represent the will of the people. Adding or repealing an amendment is a standard change (30 PP) in a package, under the same supermajority and cooldown rules. Amendments are a useful way to signal your values or force rivals to vote publicly for or against a popular idea.

!!! tip "Line up a supermajority first"
    A supermajority is a high bar and a package costs at least 60 PP, so don't open one until you've [negotiated](communication.md) the votes. Common moves include centralising power in cabinet posts your coalition holds, decentralising it to legislatures for oversight, or depoliticising a sensitive area by handing it to independent bureaucrats.

## Voting on a package

Each package has a review page, which is also where you vote. It shows:

- **What would change**, grouped by section of the constitution, with the current wording struck through and the proposed wording highlighted. Dependent changes are nested under the change that requires them.
- **Consequences**, listing side-effects such as *"The sitting Minister of Culture (J. Smith) leaves office"* or *"Future amendments will need 60% of the Senate"*.
- **The proposer's case**, from the package description.
- The **vote card** and the **tally** for each required chamber.
- A toggle to read the **whole constitution with the changes marked**.

While a package is open, articles it would change show an **Amendment pending** marker on the constitution page, linking to it.

## Constitutional conventions

Normally a constitution changes slowly: one package at a time, with an Article II cooldown after every package that passes. A **Constitutional Convention** is a year set aside for rewriting it. While a convention sits, packages can pass one after another and each one is cheap, so a country can make a large set of changes in a single burst instead of over many years.

### Calling a convention

A convention can be called from the **Constitutional Convention** panel on the country's constitution page, by:

- the **head of government**: the party whose character holds the head-of-government office, whether that's an elected office such as a presidency or a cabinet position such as Prime Minister. Calling it costs that party **75 PP**.
- the **reigning monarch**, in a country with a [Crown](monarchy.md). This is **free**, since monarchs don't spend PP, and the monarch can call one whether or not the Crown is the head of government.

A convention can be called even while the constitution is in its normal post-amendment cooldown. It can't be called while one is already sitting, or within **10 years** of the last one ending. The panel shows whether a convention is in session and until when, whether one can be called, or when the cooldown ends. When a convention can be called, the head of government's party and the monarch also see a reminder on their dashboard: *"You can call a constitutional convention"*.

### While a convention sits

A convention lasts **one year** (365 game days) and appears on the country as a **Constitutional Convention** [national mood](elections.md#national-moods). Unlike most moods it has no effect on voter opinions, issue importance or the economy: it only changes the rules for constitutional change.

- **The cooldown is suspended.** As soon as one package closes, the next can be opened, so several packages can pass during the year.
- **Package cost is capped at 75 PP.** Put as many changes in a package as you like; opening it never costs more than 75 PP. The usual 60 PP minimum still applies, and the package's cost breakdown shows when the cap has been applied. The price is fixed when the package is opened, so a package opened on the convention's last day keeps its capped price.
- **Any party can propose.** Only the head of government or monarch can *call* a convention, but every party can open packages during it.
- **One package at a time still applies.** Only one package can be open for voting at once; others have to wait for it to close.
- **Voting is unchanged.** Every package still needs the supermajority set in [Article II](#article-ii-the-amendment-rule), in every required chamber, over the usual 60-day voting period.

!!! tip "Plan the year"
    A 60-day voting period and one open package at a time mean only a handful of packages can run through a single convention. Agree the order with other parties before it's called, and bundle related changes together: with the cap, one large package costs the same as a small one.

### When it ends

A convention ends after its year, or earlier if an admin ends it. When it ends:

- the **normal Article II cooldown** resumes, counted from the last time the constitution was changed. A package that passed near the end of the convention still starts the usual cooldown.
- a **10-year cooldown** starts before another convention can be called.

### Founding conventions

A newly created country starts with a **founding convention** for its first year, so its first parties can settle the constitution they want to play under. It works exactly like a convention that has been called, and its end also starts the 10-year cooldown. Countries that existed before conventions were introduced don't get one retroactively.

## The Supreme Court

Some countries also recognise a [Supreme Court](supreme-court.md): a bench that can strike an amendment out of the constitution, or order a law changed, when a party successfully argues it is unlawful. Its rulings take direct effect and bypass the supermajority process entirely, so a constitution with a court in it is never settled by the numbers alone. Players can't add or remove the court through a constitutional change.

## Next steps

- [The Supreme Court](supreme-court.md): appealing an amendment, a law, or an office-holder.
- [Government & Cabinet](cabinet.md): cabinet positions that can hold powers.
- [Hereditary Monarchy](monarchy.md): Crown offices, the constitutional crisis mechanic, and calling a convention as monarch.
- [Communication](communication.md): building the supermajority you'll need.
- [Elections & Voters](elections.md#suffrage): how a restricted franchise shows up in turnout, polls and results.
- [Executive Actions & the Autocracy Score](executive-actions.md#the-autocracy-score): the ledger that prices restricting the vote.
