# Constitution & Constitutional Changes

Every country has a **constitution**: the rules that set out how it is governed. It names the country, its legislatures and elected offices and how often they are elected, who heads the government, who appoints the cabinet, which cabinet positions exist, who may vote, and how the constitution itself can be changed.

It also decides *who holds which powers*. There are **18 powers** (declaring war, appointing judges, setting monetary policy, granting pardons and so on), and each is assigned to one kind of holder:

- a **legislature** (an elected chamber),
- an **elected office** (a single post such as a presidency),
- a **cabinet position** (whoever holds that office),
- the **monarchy** (in countries with a [Crown](monarchy.md)), or
- **professional non-partisan bureaucrats** (an independent civil service, outside political control).

Each country starts with a different arrangement. One power, **Ratify Foreign Treaties**, must always sit with a single office, never a chamber or the bureaucrats (see [International Treaties](treaties.md#who-decides-the-treaty-power)). Parties can propose **constitutional changes** to move powers around and rewrite much of the rest of the constitution.

## What can be amended

Every part of the constitution is either **Amendable** or **Entrenched**. Some rules the game uses aren't in the constitution at all, so they can't be changed: the pass thresholds for ordinary laws, the maximum number of parties, how a monarch is chosen, and the parliament's seating style.

| Part of the constitution | Cost |
| --- | --- |
| Official name (must still end in the common name) | Standard |
| Election frequency of any chamber or elected office | Standard |
| Who holds each power | Standard, per power moved |
| No-confidence rule for an elected office | Standard |
| Renaming a cabinet position; monarchy name and titles | Standard |
| Adding or repealing an amendment | Standard |
| Whether an elected office has a veto | Major |
| Establishing or abolishing the monarchy | Major |
| Creating or abolishing a cabinet position | Major |
| Head of government; who appoints the cabinet | Major |
| Seat count of a chamber | Major |
| Article II: thresholds, required chambers, cooldown | Major |
| [Suffrage](#suffrage): who may vote | Major |
| Not amendable: the country's common name, which chambers and elected offices exist, legislature names, and the Supreme Court | n/a |

**Costs:**

- A **standard** change costs **30 PP**; a **major** change costs **60 PP**.
- A package costs at least **60 PP** in total.
- **Dependent changes**, the ones added automatically because another change requires them, are **free**. Abolishing a ministry that holds four powers costs 60 PP, not 180.
- During a [Constitutional Convention](#constitutional-conventions), a package costs **no more than 75 PP**, however many changes it holds.

## Proposing a change

Constitutional changes are made in **packages**. A package holds any number of changes, has a name and a description (where you make your case), and is voted on as a whole: either all of it applies or none of it does. The game checks the package is consistent and lists any consequences (such as a minister leaving office) before you vote. If one change forces another, it is added for you with an editable default, free of charge.

- It needs a **supermajority** of **all seats** in every chamber [Article II](#article-ii-the-amendment-rule) requires, not a simple majority. Empty seats and parties that don't vote count against it.
- Voting runs for **60 days**, and your party automatically votes Yes. It can resolve early if it already has the votes, or if the No votes make the threshold impossible.
- Only **one package can be open per country** at a time.
- After a package **passes**, Article II's **cooldown** must run before another can be opened. A convention suspends it.
- You can withdraw at any time, but the PP isn't refunded once voting has opened.

!!! note "Two kinds of percentage"
    No-confidence thresholds count **those voting**. Amendment thresholds in Article II count **all seats**. The constitution always says which one it means ("75% of those voting", "67% of all seats").

!!! tip "Line up a supermajority first"
    A supermajority is a high bar and a package costs at least 60 PP, so don't open one until you've [negotiated](communication.md) the votes. Common moves include centralising power in cabinet posts your coalition holds, decentralising it to legislatures for oversight, or depoliticising a sensitive area by handing it to independent bureaucrats.

### Election frequency

You can change how often a legislature or elected office is elected (2 to 120 months). It applies **prospectively**: the next already-scheduled election still runs under the old frequency.

### Seat counts

You can change the number of seats in a chamber (10 to 800). It takes effect at that chamber's **next election**, scheduled or early.

### No-confidence votes

Every elected office has a **no-confidence rule**: one active legislature in the same country that can vote to remove the holder, and a threshold of 51% to 100% of those voting. You can change the chamber or the threshold, but not remove the rule. See [Elections](elections.md#elected-offices) for how a no-confidence call works.

### Elected office veto

An elected office can hold a **veto over bills**: while it's held and the veto is on, a bill that clears the legislatures still fails if the holder's party votes No. It's on by default, and turning it on or off for an office is a **major** change. A bill still open is decided under whichever rule is in force on the day it closes. The full rules are in [Legislation](legislation.md#elected-office-veto).

## Article II: the amendment rule

Article II sets how the constitution itself is changed. Every change to it is **major** (60 PP).

- **Threshold per chamber:** **50% to 90% of all seats**. A country may start with something like 66.6%, which stays valid until amended.
- **Required chambers:** which chambers must approve a package. Only chambers can be required, and at least one must be.
- **Cooldown:** **0 to 5 whole years** between successful packages. It doesn't apply during a convention.

A package is voted on under the thresholds and required chambers **in force when it opened**, so a package that lowers the threshold still has to clear the old, higher one.

## Suffrage

Every constitution defines who may vote. By default it's **universal adult suffrage**. Restricting the franchise is a single **major** change (60 PP) that can be combined with anything else in a package. Each field defaults to the most inclusive option, and an elector must pass **every** restriction to vote:

| Field | Options (default first) | Autocracy points |
| --- | --- | --- |
| Gender | All · Men only · Women only · Men and married women | 75 · 75 · 55 |
| Minimum age | 18 · 21 · 25 · 30 | 10 · 20 · 30 |
| Maximum age | None · 80 · 70 · 60 · 50 | 10 · 20 · 35 · 50 |
| Employment | All · Employed only | 30 |
| Income | All · Medium and above · High and above | 40 · 60 |
| Education | All · Secondary and above · Degree and above | 15 · 50 |
| Housing | All · Homeowners only | 40 |

Age limits are inclusive. "Employed only" never removes the vote from retirees, and who counts as retired follows the country's **Pension Age** law, so raising the pension age can quietly take the vote from older unemployed people. That is an ordinary law change: it costs no extra PP and adds no autocracy points. See [Retirement](elections.md#retirement).

The new rules apply from the moment the package is ratified, and the next poll or election uses them. Sitting legislators are never unseated by a franchise change.

### How the disenfranchised react

The people a Suffrage package targets don't wait for an election to respond.

- **Losing the vote is punished hard.** Every elector the package would exclude marks down any party that votes **yes** by **-4** (more than any single law article), and rewards a party that votes **no** by **+4**.
- **It bites before the result is known, and even if the vote fails.** The reaction starts when a party votes on the open package and stays if the package fails. Withdrawing the package stops it from that day on.
- **Restoring the vote earns half as much:** electors a package enfranchises give **+2** for a yes and **-2** for a no.
- **The grudge doesn't fade while the vote is lost.** A party's voting record normally fades from voters' memories over time, but a disenfranchised group's grudge is paused until its vote is restored, then fades as usual.

### The cost of restricting the vote

Restricting the vote counts as autocracy, charged through the [autocracy score](executive-actions.md#the-autocracy-score) at the fixed points in the table above, with no cap on a package's total. You are warned of the points, your new reputation band and any Suffrage Crisis before you vote.

- **The proposing party pays in full; every other party that votes yes pays half.** Points are only charged once the package is **applied**, so a failed or withdrawn package costs no autocracy (though it still costs the opinion above).
- **Moving a field further along costs the difference.** Raising the minimum age from 18 to 21 and later to 30 costs 10 points, then 20 more.
- **Loosening credits only a fifth** of the points it removes, and only on a field that was actually restricted. Restricting to men only (75) and later restoring universal suffrage credits just 15, so the round trip nets **+60**.
- **Swapping between incomparable options is charged at the new option's full price**, never credited, because each side takes the vote from someone. Men only to women only costs the full 75.
- **Traditional Culture moderates gender restrictions:** in a country with that [national mood](elections.md#national-moods), the gender rows cost two-thirds (50 and 37 points).

### Suffrage Crisis

If an applied package removes the vote from at least **10% of the electors** who could vote before, the country enters a **Suffrage Crisis** for **180 days** (restarting if the franchise is restricted again). See [Elections](elections.md#suffrage-crisis) for the mood itself. It makes the way back easier: a package containing only Suffrage changes that are each unchanged or **less restrictive** needs **half** the usual threshold and can be opened during the normal cooldown. A gender swap never qualifies, and adding any restrictive or unrelated change removes the discount.

### Too few eligible voters

If a country's franchise leaves too few eligible voters, **no election is held**: every seat stays with its holder and polls report too few voters. The Suffrage Crisis stays active for as long as this is true, so a cheaper route back is always open.

## Cabinet offices and government

These changes reshape who governs, and all are major except renaming a position.

- **Create a cabinet position:** give it a name and description; powers can be moved to it in the same package.
- **Rename a cabinet position:** it keeps its powers and minister (standard cost).
- **Abolish a cabinet position:** the sitting minister leaves office. The package must give each of its powers a new holder, and name a new head of government if it held that role. You can't abolish the last position.
- **Head of government:** an elected office, a cabinet position, or the monarchy.
- **Who appoints the cabinet:** an active legislature, an elected office, or the monarchy. The sitting cabinet stays until the next formation, except that moving the appointing power **to or from the Crown** ends all appointments at once. A formation in progress when the change applies is cancelled.

### The monarchy

You can **establish** a monarchy, **abolish** it, or change its **name and titles**. See [Hereditary Monarchy](monarchy.md) for how the throne works. Abolishing it adds free, editable dependent changes: a new head of government, a new body to appoint the cabinet, and a new holder for each power the Crown held.

!!! info "Constitutional Crisis"
    During a [Constitutional Crisis](monarchy.md#constitutional-crisis), a package that contains only the abolition and its dependent changes needs **half** the usual threshold and **skips the cooldown**. Add any other change and it loses both benefits.

## Amendments

Parties can also propose **amendments**: custom plain-text articles added to the constitution ("Freedom of speech is an inalienable right of every citizen"). They have no direct gameplay effect but represent the will of the people. Adding or repealing one is a standard change (30 PP). They let you signal your values or force rivals to vote publicly on a popular idea.

## Constitutional conventions

Normally a constitution changes slowly: one package at a time, with a cooldown after every package that passes. A **Constitutional Convention** is a year set aside for rewriting it, when changes are cheap and can follow one another immediately.

**Who can call one:**

- the party holding the **head of government** office (an elected office such as a presidency, or a cabinet position such as Prime Minister), for **75 PP**;
- the **reigning monarch**, for free, whether or not the Crown is the head of government.

A convention can be called during the normal cooldown, but not while one is already sitting or within **10 years** of the last one ending.

**While it sits** (one year, 365 game days), which shows as a [national mood](elections.md#national-moods) with no effect on voters or the economy:

- the cooldown is **suspended**, so several packages can pass during the year;
- a package costs **no more than 75 PP** (the 60 PP minimum still applies), so one large package costs the same as a small one;
- **any party can propose**, not just the caller;
- only one package can be open at a time, so only a handful fit in the year: agree the order with other parties beforehand and bundle related changes. Voting is unchanged (60 days, Article II supermajority).

When it ends, the normal cooldown resumes (counted from the last change to the constitution) and a 10-year wait starts before another convention can be called.

A newly created country starts with a **founding convention** for its first year, so its first parties can settle the constitution they want to play under. Countries that existed before conventions were introduced don't get one.

## The Supreme Court

Some countries recognise a [Supreme Court](supreme-court.md), which can strike an amendment out of the constitution or order a law changed when a party successfully argues it is unlawful. Its rulings take effect directly and bypass the supermajority process, so a constitution with a court is never settled by the numbers alone. Players can't add or remove the court through a constitutional change.

## Next steps

- [Elections & Voters](elections.md#suffrage): how a restricted franchise shows up in turnout, polls and results.
- [Executive Actions & the Autocracy Score](executive-actions.md#the-autocracy-score): the ledger that prices restricting the vote.
