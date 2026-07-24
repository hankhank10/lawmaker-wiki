# Economy

Most countries in Lawmaker have a **modelled economy** that gives the nation a size (total GDP), a prosperity level (GDP per capita), and a growth trajectory built from its **industries**. All figures are in US dollars. You don't manage the economy directly — but your party's **budget votes** shape it and, crucially, shape how voters see you.

## The shape of a country's economy

Every country starts as a **developed economy**, with a starting GDP per capita in the tens of thousands of dollars and some random variation between countries. GDP comes from the country's electors — each contributes according to whether they're employed and which income band (low, medium, high, or elite) they sit in. [Retired](elections.md#retirement) electors don't contribute, so the **Pension Age** law is a direct economic lever alongside its social effects: raise it and more people work and pay in; lower it and more retire out of the workforce. Temporary [national moods](#national-moods-and-economic-growth) can boost or crash growth on top of the ordinary trajectory described below.

Every country's **Economy page** is split into tabs. **Economic Growth** is the live snapshot — GDP per capita, total GDP, unemployment, income inequality, a GDP breakdown by earner band, an international ranking, and growth history. **Debt & Reserves** covers the credit rating, its borrowing (or interest-earning) rate, and reserve/debt history. There's also an **Industries** tab (below) and a **Budget** tab for casting your vote. Browse these in-game; the numbers update on every visit. The separate **International Economy** page is a world-level financial news terminal: a scrolling GDP ticker running through every country's growth, a sector board of the world's best- and worst-performing industries this month, and a live wire of financial news stories — unread stories are marked **New**, and a badge appears on the World menu whenever there's fresh news to read. Further down the same page sits the league table ranking every country in the world; a country under an active [IMF programme](#imf-intervention) shows a **‼️ IMF** badge in its rating column instead of a normal letter grade, so you can spot which economies are under IMF control at a glance.

The **Budget** tab can also carry a **Global decision effects** section — a set of fixed
income or expenditure rows created when your country votes (or defaults) its way into a
[global decision's](global-decisions.md#budget-effects) programmatic consequence. Each row
shows its label, direction, monthly amount, and months remaining, and folds straight into the
budget totals and Sankey chart alongside ordinary tax and spending. It only appears once your
country actually has an active effect.

## Industries: where growth comes from

A country's growth isn't one flat number — it's built up from **industries**. Every economy is a mix of up to twelve industries: Agriculture & Food, Oil & Gas, Mining & Metals, Technology, Financial Services, Pharmaceuticals, Consumer Goods & Retail, Automotive, Aerospace & Defence, Tourism & Hospitality, Media & Entertainment, and Professional Services. Three of these — Agriculture & Food, Consumer Goods & Retail, and Professional Services — are present in every country; the rest are present or absent depending on the country's mix.

Each industry has its own growth story that plays out across the whole world at once — a global technology boom lifts every tech-heavy country simultaneously, while an oil slump hits every petrostate at the same time. Your country's growth each month is the blended result of how every one of its industries is doing, weighted by how much of your economy that industry makes up. A country that's heavily invested in a booming industry outgrows an otherwise similar rival that isn't — visible, explainable growth, rather than a single dice roll.

### Economic focus

When a country is founded (or proposed), its founder can choose an **economic focus** — a preset economic identity such as *Technology Powerhouse*, *Petrostate*, *Financial Hub*, *Mining Economy*, *Industrial Heartland*, *Agricultural Heartland*, *Tourism Paradise*, *Life Sciences Hub*, or *Cultural Powerhouse* — or leave it as a **Balanced Economy** with no dominant sector. A focus guarantees its chosen industry (or industries) is present and boosted into a genuine **specialism**; the rest of the country's mix is still generated at random. Choosing a focus doesn't change how tax, budgets, or elections work — it only shapes where your country's growth comes from.

### The Industries tab

Every country's Economy page has an **Industries** tab showing the current mix: each industry's share of the economy, a **Specialism** badge on the country's focus industries, and how each industry is growing this month — globally, and (once there's enough history) for your country specifically. The **International Economy** page carries the same idea up a level, with a world-economy-by-industry treemap, a global industry growth chart, and per-industry rankings (click through from any sector on the page) showing which countries have the largest sectors in each field.

A country's industry mix is set at creation and then only changes by growing or shrinking — a fast-growing specialism becomes an even larger share of the economy over time, reinforcing the country's identity the longer it goes unchanged.

### Laws that shape industries

A handful of laws are policy *for* an industry, and while they stand they speed that sector up or slow it down every month. Ban new fossil fuel extraction and Oil & Gas shrinks; deregulate the banks and Financial Services races ahead (while the sectors starved of capital — agriculture, automotive, mining — give a little back); accelerate AI and Technology grows faster. The Industries tab lists every such law your country currently has in force, the option it sits on, and the annual percentage points it adds to or takes off each industry, in a **Laws shaping growth** table below the industry mix.

Only laws set *away* from their neutral default appear: a country at the default position on everything gets no boost and no drag, and the table is empty. Change the law and the effect changes with it at the next monthly tick — nothing lingers. One caveat: a growth buff needs a sector to act on, so an impact aimed at an industry your country doesn't have (a dedicated AI sector, say) is shown greyed out and does nothing until that industry exists.

## How budgets affect voters

This is the part that matters for your strategy. Voters judge you on **how you vote on budgets** (including proposing your own), not just on laws. Each elector's overall view of your party is roughly:

| Component | Driven by | Weight |
| --- | --- | --- |
| Social policy | Your voting record on laws | ~70% |
| Financial policy | Your voting record on budgets | ~30% |

Laws still matter more, but budgets are the decisive secondary factor — and the effect decays over time, so recent budget votes weigh most. The exact split is a per-country setting.

### Tax is personal

Every elector sits in an income band. When you vote for a budget, they look at what it does to **their own band's** income tax: cut it and they warm to you, raise it and they cool. **Wealthier voters react far more strongly** to their own tax rate, while lower-income voters care more about the services tax funds. So a budget that slashes elite taxes delights a small group of rich voters and barely registers with everyone else.

Each personal income tax band can be set anywhere from **0% up to a hard cap of 90%** on a proposed budget — you can't balance the books by taxing a band at 100%.

### Spending maps onto the issues voters care about

Each spending area connects to a political issue voters already hold opinions on:

| Spending area | Issue it speaks to |
| --- | --- |
| Defence | Military strength |
| Education | Education & young people |
| Welfare & healthcare | Welfare state; older people |
| Police & justice | Law and order |
| Environment | Environmental protection |
| Foreign aid | Internationalism |

Boost a category and you gain the voters who prize that issue; cut it and you lose them — in proportion to how much each voter actually cares (their personal salience), and amplified by any national mood that makes the issue hotter.

### Outliers are where the votes are

Your country is compared against similar **peer countries**. Spending that's wildly above or below the **median** peer country becomes a **hot-button issue** — changing it moves lots of opinion. Spending close to the peer norm barely registers. Using the median (rather than the average) means a single outlier peer can't skew the comparison. So your biggest electoral opportunities (and risks) are in the categories where your country is already an outlier.

!!! tip "Make your laws and budget tell the same story"
    The budget is a precision tool, not a blunt one. A defence-and-order party that boosts military and police spending is doubling down convincingly. A green party that *cuts* environment spending is contradicting its own platform — and voters notice. Because budgets are only ~30% of the picture, a budget move works best when it reinforces a voting record already pointing the same way.

## National moods and economic growth

Two temporary [national moods](elections.md#national-moods) act directly on the economy:

- **Economic Miracle** — doubles the baseline annual growth rate for its duration.
- **Economic Crash** — overrides growth and forces a contraction (around -3.5%/year).

These are external events outside player control; they show up as shifts in the nation's economy.

## Credit rating

Every country carries a **credit rating** — a letter grade, shown on the **Debt & Reserves** tab
and in the **International Economy** league table, that sets how expensive it is for your
country to borrow. It is driven entirely by one number: **debt as a percentage of GDP**.

| Rating | Debt-to-GDP | Annual borrow rate |
| --- | --- | --- |
| AAA | Under 30% | 2% |
| AA | 30%–50% | 3% |
| A | 50%–70% | 4% |
| BBB | 70%–90% | 6% |
| BB | 90%–120% | 8% |
| B | 120%–150% | 12% |
| CCC | 150% or more | 18% |

The rating is recalculated automatically every month from your current debt-to-GDP ratio — there's
nothing to vote on directly. A country running a **reserve** (positive balance) rather than debt
always sits at the best rating and *earns* interest on that reserve instead of paying it.

The borrow rate matters because it applies to your whole outstanding debt, every month: a country
that lets its rating slide from AA to BB is paying roughly triple the annual interest on the same
balance, which drags on the budget and makes it harder to ever run a surplus again — a downward
spiral if left unchecked. Bottoming out at **CCC** triggers the **Economy on the Brink** warning
covered below; a country under an active **IMF programme** shows a special **‼️ IMF** badge in place of a letter grade, with its own discounted rate.

## IMF Intervention

A country that lets its debt spiral out of control eventually loses the freedom to run its own books. The status-quo budget bakes in a structural deficit, and as your credit rating falls your borrowing costs climb (up to **18%** a year at the worst rating). Left unchecked, the interest compounds and the debt runs away. When it becomes catastrophic, the **International Monetary Fund steps in** — a rescue, but one with harsh strings attached.

### The warning: "Economy on the Brink"

Before the IMF gets involved, you get a clear warning. Once your **debt reaches 150% of GDP** your credit rating bottoms out at **CCC**, the worst rating, and an **Economy on the Brink** badge appears on the country. This is the danger zone: borrowing is at its most expensive, and you are one bad stretch away from losing control of the budget. Treat it as your last chance to balance the books on your own terms.

### What triggers an intervention

If debt keeps climbing past the brink, the IMF takes over when:

- Your **debt reaches 200% of GDP**, and
- It **hits 200% of GDP in any single month**.

At 200% debt-to-GDP a country is effectively insolvent, so the IMF steps in immediately.

### What happens when the IMF takes over

The intervention hits immediately and reshapes the whole country:

- **An emergency austerity budget is imposed** — no vote, no say. Every tax band is set to **50%**, and spending in every category is slashed to roughly **25% of what comparable countries spend**. By design this budget runs a large surplus: it exists to pay down the debt fast.
- **The economy crashes into a recession** lasting **1 year** — growth turns sharply negative while the austerity bites.
- **Budget policy is locked** under IMF conditions for as long as the programme runs (see below).
- **The responsible parties are branded** with a heavy political penalty (see below).

### The one upside: cheap debt

There is a single carrot. While you are under the programme, your debt becomes **cheap**: a fixed **5%** annual borrow rate, instead of the up-to-18% a 200%-debt country would otherwise pay. Combined with the surplus the austerity budget generates, that cheap interest is the engine that climbs you out of the hole. The programme is brutal, but it is survivable — and the discounted rate is what makes the recovery reachable.

### Living under the programme

You don't lose the budget entirely. You can still propose your own budgets while under the IMF — but they must satisfy two conditions to be valid:

| Condition | Rule |
| --- | --- |
| **No deficit** | Spending must not exceed the tax take. You may run a surplus, never a deficit. |
| **Tax floor** | Every tax band must stay at or above **40%** (just below the 50% emergency level, so you can ease off a little — but not gut revenue). |

A proposal that breaks either rule is rejected. This lets you steer spending priorities and soften the tax burden slightly, but it cannot undo the discipline that gets you out.

### The political cost: "Destroyed Economy"

Someone is blamed for the wreck. When the IMF intervenes, a crushing **Destroyed Economy** brand is applied to:

- **Every party in government** at the time, and
- **Every party that voted for the budgets** that drove the country into insolvency.

The brand cuts the affected parties' vote share roughly **in half** — far harsher than any other party penalty — and it is *sticky*. It lasts the **entire** time the country is under the programme, **plus 2 years after** you exit. Balancing the books does not wash it off; the reckoning outlives the bailout.

!!! warning "Voting for a deficit budget is a recorded act"
    The IMF reads the ledger. If you voted *for* the budgets that ran the debt up, you wear the **Destroyed Economy** brand even if you're long out of government by the time the IMF arrives. Parties that opposed those budgets are spared.

### How the programme ends

The programme ends on recovery, not on a timer. The IMF leaves once your **debt falls back to 100% of GDP or below and stays there for 6 consecutive months**.

Crucially, the **recession only lasts 1 year**, while the programme runs until the debt recovers — which usually takes longer. So once the recession lifts, **growth resumes even while you are still under the IMF**, and a growing GDP helps drag your debt-to-GDP ratio back down alongside the austerity surplus. That combination — surplus, cheap 5% debt, and renewed growth — is how a country claws its way back out.

!!! tip "Avoiding and escaping a bailout"
    The cheapest crisis is the one you never have. Watch your credit rating: once it slips toward **CCC (150% debt)**, your borrowing costs are punishing and the **Economy on the Brink** warning is telling you the IMF is next. Pass a surplus budget *before* you hit 200% and you keep control on your own terms.

    If the IMF is already in, don't fight the programme — use it. The 5% debt rate is the lowest borrowing cost in the game, so a disciplined balanced (or surplus) budget pays the debt down fast. Hold the line through the 1-year recession, let growth resume, and push debt-to-GDP back to 100% for six straight months to exit. Just remember the **Destroyed Economy** brand follows the culprits for two years past recovery — so the parties that *caused* the crisis carry the electoral cost long after the books are balanced.

## Next steps

- [Elections & Voters](elections.md) — how voter opinion turns into seats.
- [Legislation & Voting](legislation.md) — the laws that make up your social-policy record.
- [Global Decisions](global-decisions.md) — the world-wide votes that can add their own income or expenditure rows to your budget.
