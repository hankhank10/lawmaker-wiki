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
negative). Each month's increment also has a small random variation of ±5%, so
the actual path is slightly uneven even at a constant growth rate. Over twelve
months this compounds to roughly the stated annual figure.

### National Moods and Economic Growth

A country may experience temporary **national moods** that modify its economic
growth rate:

- **Economic Miracle** - Doubles the baseline annual growth rate (e.g., a 2% growth country grows at ~4% while the mood lasts)
- **Economic Crash** - Overrides the baseline and forces contraction at ~-3.5%/year regardless of normal growth

These are external economic events that can occur during gameplay. See
[National Moods](elections.md#event-triggered-moods) for more details.
