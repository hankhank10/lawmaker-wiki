# Hereditary Monarchy

Some countries have a **hereditary monarchy** alongside their elected institutions. The Crown is a country-level office with its own page, reign history, and, where the constitution assigns powers to it, direct constitutional authority.

The first country to use this system is [Avalon](../countries/avalon.md), where the Crown holds the power to grant pardons.

## The Crown Page

Countries with a monarchy show a **Crown** panel on the country page and a dedicated monarchy page. The page shows:

- Whether the throne is occupied or vacant
- The current monarch's regnal name and dynasty
- The nomination deadline when the throne is vacant
- Submitted nominations for the current vacancy
- Reign history
- Coat of arms controls for the reigning monarch

## Vacancies and Nominations

When a throne is vacant, active parties in that country may nominate one of their own activists.

### Eligibility

To submit a nomination:

- Your party must be active in the country
- Your party must not already be enthroned
- The nominee must be an activist in your party
- The nominee must not be retired
- Your party must not have already nominated someone in the current vacancy window

Each party can submit **one nomination per vacancy**. Nominations cannot be withdrawn or changed after submission.

### Dynasty Name

When nominating, you choose a dynasty name. If you leave it blank, the nominee's last name is used.

If the nomination wins, the monarch receives a regnal name based on their title, first name, and ordinal, such as **King Arthur I** or **Queen Eleanor II**.

## Selection

Each monarchy has its own selection method. Avalon currently uses **oldest party**, which means:

1. The eligible nomination from the oldest nominating party wins
2. If there is a tie, the lower party ID wins

If no nominations are submitted before the deadline, the vacancy is extended for another nomination period.

## Accession

If your nominee wins, your party is transformed into the reigning Crown for the duration of the reign.

The accession has major consequences:

- Your party becomes dormant while you hold the throne
- Your party's Political Power is reset to **0**
- Your party loses all legislature seats
- Any cabinet positions held by your party's characters are vacated
- Your party leaves all international blocs
- The nominated activist leaves the party and becomes the reigning monarch
- Your active identity switches from your party to the monarchy

While reigning, you can post to the social media feed as the Crown. Crown posts use the monarch's regnal name and link back to the monarchy page.

!!! warning "A Crown Is Not A Campaign Vehicle"
    Winning the throne is a permanent-looking prestige move, but it removes your party from normal electoral politics while the reign lasts. Do not nominate casually.

## Constitutional Powers

The Crown can hold constitutional powers just like a legislature, cabinet position, or the non-partisan bureaucracy.

Powers assigned to the monarchy appear in the constitution under the Crown article. Future constitutional changes can move powers to or away from the monarchy if the country has one.

In Avalon, the Crown initially holds **Grant Pardons**.

## Royal Assent and Veto

In any country with a hereditary monarchy, the reigning monarch can pre-register a **veto** on any open proposal. The veto sits on top of the normal legislative vote — it does not replace it.

### How it works

On the proposal page, a reigning monarch sees a **Royal Assent** card with two choices:

- **Allow passage** (the default) — the bill becomes law if the legislatures pass it
- **Veto if it passes** — the bill is blocked at royal assent if the legislatures pass it

The monarch can switch between these two states at any time while the proposal is open. While voting is in progress, no one else can see which option the monarch has chosen — parties continue to vote without knowing whether their bill will receive royal assent.

### Resolution at tally time

When the proposal closes, the legislatures' vote is tallied first:

- If the legislatures **reject** the bill, the bill fails on its own. Any pre-registered veto is discarded and never recorded — no one ever learns that the monarch had a veto pending.
- If the legislatures **pass** the bill and the monarch's choice is "allow passage", the bill becomes law as normal.
- If the legislatures **pass** the bill but the monarch has registered a veto, the bill is blocked. The proposal is marked as **Vetoed by Monarch**, and a Lawbot post on the social feed announces that the monarch refused royal assent.

The veto is therefore only ever made public when it actually changes the outcome.

### When the monarch sees the page

While reigning, the normal "Cast Your Vote" card is replaced by the Royal Assent card on each open proposal — monarchs do not vote on legislation, they decide whether to grant or refuse assent.

## Abdication

A reigning monarch can abdicate at any time.

When you abdicate:

- The current reign ends
- The monarch character retires from public life
- Your party is restored
- Your restored party has **0 seats** and **0 Political Power**
- A new vacancy opens and nominations begin again

Your party comes back, but it does not regain the offices, seats, or resources it held before accession.

## Inactivity

Monarchies are subject to inactivity checks. If a reigning monarch is inactive long enough, warning emails are sent. Continued inactivity can force abdication.

Forced abdication is harsher than voluntary abdication:

- The reign ends as inactive
- The monarch character retires
- The enthroned party is disbanded rather than restored
- The throne becomes vacant

Log in regularly while reigning to keep the Crown active.

## Coat of Arms

The reigning monarch can upload an SVG coat of arms for the Crown. The system supports the same basic SVG safety rules as party logos, with optional colour tinting and display scaling.

## Strategy

Pursuing the throne can be worthwhile when:

- Your party is old enough to have a strong chance under the selection rules
- You want a prestige role rather than normal electoral competition
- The monarchy holds important constitutional powers
- You are ready to give up seats, cabinet roles, bloc memberships, and PP

It is risky when:

- Your party is currently electorally strong
- You rely on cabinet positions or bloc leadership
- You want to keep proposing laws and fighting elections
- You may not be active enough to avoid forced abdication

## Next Steps

- [Constitution](constitution.md) - How powers can be assigned to the Crown
- [Party Management](parties.md) - What happens to parties that become enthroned
- [Characters & Activists](characters.md) - Activists who can become monarchs
- [Avalon](../countries/avalon.md) - The first constitutional monarchy
