# Economy

Every country in Lawmaker has a **modelled economy**. It gives each nation a size
(its total GDP), a prosperity level (GDP per capita), and a trajectory (a growth
rate). All economic figures are shown in **US dollars ($)** — there is a single
global currency.

## Economy types

When a country is proposed, it is given one of four **economy types**. This sets
its starting assumptions:

| Economy type      | Baseline GDP per capita | Default annual growth |
|-------------------|-------------------------|-----------------------|
| Failed state      | ~$1,500                 | 0.50%                 |
| Developing        | ~$12,000                | 4.50%                 |
| Developed         | ~$50,000                | 2.00%                 |
| Highly advanced   | ~$85,000                | 1.50%                 |

Each country's baseline is seeded from its type with a small (±5%) random
variation, so no two countries are identical. The **annual growth rate** is a
tunable figure (to two decimal places, e.g. `5.02%`) and **can even be negative**
to model a contracting economy.

!!! info "Per capita means per adult"
    Lawmaker models adults only — every elector is an adult, and GDP per capita
    is GDP divided by the (adult) population.

## How national GDP is calculated

A country's population is represented by a sample of **electors**. Each elector
stands in for a slice of the population (population ÷ number of electors).

Each elector contributes to GDP based on:

1. **Employment status** — the unemployed and the retired contribute nothing.
2. **Income band** — each employed elector is in one of four bands that scale
   their contribution relative to the baseline GDP per capita:

    | Income band | Default multiplier | Typical share of employed |
    |-------------|-------------------|--------------------------|
    | Low         | 0.5×              | ~30%                     |
    | Medium      | 1.0× (baseline)   | ~40%                     |
    | High        | 2.0×              | ~29%                     |
    | Elite       | 10.0×             | ~1%                      |

    The per-country multipliers for each band are tunable by a superuser.

3. **A small personal variation** — each elector has a fixed ±5% modifier.

National GDP is the sum of every elector's contribution multiplied by the number
of people they represent.

## Unemployment and retirement

The share of the population that is unemployed or retired varies by economy type:

| Economy type    | Retired (% of adults) | Unemployed (% of workforce) |
|-----------------|----------------------|-----------------------------|
| Failed state    | 8%                   | 35%                         |
| Developing      | 12%                  | 16%                         |
| Developed       | 22%                  | 6%                          |
| Highly advanced | 25%                  | 4%                          |

These reflect the different demographic and labour-market profiles of each
economy type. Both groups contribute zero to GDP.

## Country Summary & Credit Rating

Every country's detail page shows an **economy summary box** with key economic metrics at a glance:

- **GDP** — Total national gross domestic product
- **GDP per capita** — Average wealth per adult
- **Credit rating** — The country's current credit rating (AAA, AA, A, BBB, BB, B, or CCC) based on debt-to-GDP ratio. This rating determines the interest rate the country pays on its debt (AAA = 2.0%, CCC = 18.0%).
- **Unemployment** — Current percentage of the workforce without jobs

The credit rating is a key indicator of fiscal health — managing your country's budget and keeping debt manageable helps maintain a strong rating and lower borrowing costs.

## The Economy page

Every country has an **Economy** page (linked from the dashboard, the country
page, and the menu). It shows a **live** snapshot — recalculated every visit —
including:

- Average GDP per capita (the actual figure, not the baseline)
- Median GDP per capita (the middle value across employed electors)
- Total GDP, broken down by low / medium / high / elite earners
- Unemployment rate
- **Inequality ratio** — the mean GDP per capita of high earners divided by the
  mean of low earners (a higher number means greater inequality; elite earners
  are not included in this figure)
- **Interest expense/income** — the actual interest paid or earned on the country's debt or reserves in the previous month. This is a **backward-looking figure** based on last month's balance and the country's credit rating, not a projection of future interest payments.
- A history table and graph of how the economy has changed month on month
- The country's **international rankings** (by total GDP and GDP per capita)

A monthly snapshot is stored automatically so history and rankings stay fast.

## International Economy

The **International Economy** page ranks every country in the world by total GDP
and GDP per capita, and shows world totals. Click any country to jump to its
Economy page. This league table is built from each country's most recent stored
snapshot.

## Growth over time

At the start of each game month, every country's baseline GDP per capita grows by
the monthly equivalent of its annual growth rate (or shrinks, if the rate is
negative). Each month's increment also has a random variation of ±10%, so
the actual path is noticeably uneven even at a constant growth rate. Over twelve
months this compounds to roughly the stated annual figure.

## How budgets affect voters

Until now, voters judged your party purely on the laws you proposed and voted for. **Budget decisions — how much tax the government raises and what it spends that money on — now shift voter opinions too.**

Every elector's view of your party is made up of two components:

| Component | What drives it | Typical weight |
|-----------|---------------|----------------|
| **Social policy score** | Your voting record on laws | ~70% |
| **Financial policy score** | Your voting record on budgets | ~30% |

The exact split is a per-country setting, so check your country's profile — but as a rule of thumb, **laws still matter more**, and budgets are the decisive secondary factor. A party that ignores budgets entirely is judged only on its social record, and hands a free advantage to rivals who engage.

!!! info "You are judged on how you vote"
    Just like laws, it's your **voting record on budgets** that voters react to — including proposing your own budget. The effect decays over time, so recent budget votes carry more weight than old ones.

### Tax: it's personal

Every elector sits in one of four **income bands**: low, medium, high, or elite. When your party votes for a budget, voters look at what it does to **their own band's income tax rate**:

- Vote for a budget that **cuts taxes on their band** → they warm to your party.
- Vote for a budget that **raises taxes on their band** → they cool toward you.

Crucially, **wealthier voters are more sensitive to tax changes** than poorer voters — the elite and high earners react strongly to rises or cuts in their bracket. Lower-income electors care about tax too, but they weight the services that tax pays for more heavily (see spending, below). This creates real trade-offs: a budget that slashes taxes for the elite might delight a small group of rich voters while barely registering with everyone else.

### Spending: it maps onto the issues voters care about

Each area of government spending connects to the political issues that electors already have opinions on. When a budget increases or decreases spending in an area, voters who care deeply about the related issue react accordingly.

| Spending area | Issue it speaks to | Typical voters it reaches |
|--------------|-------------------|--------------------------|
| **Defence** | Military strength | Hawks, nationalists, security-focused electors |
| **Education** | Education & young people | Parents, progressives, those who value social mobility |
| **Welfare & healthcare** | Welfare state; support for older people | Electors backing the safety net, retirees, low-income voters |
| **Police & justice** | Law and order | Law-and-order conservatives, safety-focused voters |
| **Environment** | Environmental protection | Green voters, younger electors, sustainability advocates |
| **Foreign aid** | Internationalism | Cosmopolitan, outward-looking, globally minded electors |

Boost a spending area and you gain support from voters who prize that issue. Cut it and you lose them. How strongly each elector reacts depends on their **personal salience** — how much they care about that issue in the first place. A committed environmentalist will notice an environment cut far more than someone who barely thinks about it.

National moods amplify this further: if the country is in a mood that makes an issue hotter (say, "Stewards of the Land" pushing environmental concern), spending changes in that area will move even more votes.

### Being an outlier makes a category hot-button

Each country is compared to a set of **peer countries** — nations at a similar stage of development. If your country's spending in a category is wildly higher or lower than its peers, that area becomes a **salient political issue**:

- Spending **far above** peers → voters notice; it's part of the national conversation. Changes to it (up or down) shift more opinions.
- Spending **close to the peer average** → barely registers as a political issue. Voters shrug.

This means the biggest electoral opportunities — and risks — are often in the categories where your country is already an outlier. Nudging defence spending when you already have the biggest military in the region will resonate; doing the same in a country that spends close to the norm will be largely invisible.

!!! example "A worked example: courting hawks, annoying the elite"
    Your party wants to win over law-and-order and defence voters ahead of an election. You vote for a budget that:

    - **Raises defence spending** significantly (above peer average → hot issue, big effect on hawks)
    - **Raises police & justice spending** moderately
    - **Funds it by raising income tax on the high and elite bands**

    **Who you win:** Security-focused voters who care about military strength and law and order — they'll see a party that puts its money where its mouth is.

    **Who you lose:** High and elite earners, who are sensitive to their tax rate and will punish you for it.

    **The maths:** Because budgets are only ~30% of the overall picture, even a decisive budget move won't override a weak social policy record. This works best when your laws and your budget tell the same story — a security-focused party that *also* votes for tough law-and-order legislation will stack both scores in its favour.

!!! tip "Strategic takeaway"
    Think of the budget as a precision tool, not a blunt instrument. Use it to court a specific slice of the electorate that your law-making record is already pointing toward. A defence-and-order party that boosts military and police spending is doubling down convincingly. A green party that cuts environment spending is telling voters one thing with its laws and the opposite with its wallet — and voters will notice the contradiction.

### National Moods and Economic Growth

A country may experience temporary **national moods** that modify its economic
growth rate:

- **Economic Miracle** - Doubles the baseline annual growth rate (e.g., a 2% growth country grows at ~4% while the mood lasts)
- **Economic Crash** - Overrides the baseline and forces contraction at ~-3.5%/year regardless of normal growth

These are external economic events that can occur during gameplay. See
[National Moods](elections.md#event-triggered-moods) for more details.
