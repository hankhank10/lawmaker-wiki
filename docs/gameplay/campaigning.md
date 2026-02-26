# Campaign Events

**Campaign events** let your party organise political activities on a calendar to influence elections, raise funds, and build your profile. Each party can schedule one event per day, assigning an activist to carry it out.

## The Campaign Calendar

Every party has a **campaign calendar** showing the current game month. From here you can:

- View upcoming and past events
- Schedule new events on future dates
- Edit or move future events
- See election days marked on the calendar

!!! info "One Event Per Day"
    Each party can only schedule **one campaign event per day**. Choose wisely!

### Scheduling Restrictions

- Events can only be scheduled on **future dates** (not today or in the past)
- Events **cannot be scheduled on election days**
- Past and current-day events become **read-only** and cannot be edited or deleted

## Creating an Event

To schedule a campaign event:

1. Open your party's campaign calendar
2. Click on a future date
3. Choose an **objective** (what you want to achieve)
4. Select an **event type** (how you'll achieve it)
5. Assign an **activist** from your party
6. If relevant, choose a **proposal** and your stance on it
7. Save the event

### Objectives

Each event has one of four objectives:

| Objective | Purpose | Available Event Types |
|-----------|---------|----------------------|
| **Raise Funds** | Generate money for your party | Private Dinner, Telethon |
| **Influence a Proposal** | Sway opinion on active legislation | Media Interview, Set Piece Speech |
| **Raise Profile** | Increase your party's visibility | Media Interview |
| **Get Out The Vote** | Mobilise your supporters for elections | Supporter Rally |

### Event Types

| Event Type | Description | Used For |
|------------|-------------|----------|
| **Supporter Rally** | A public rally to energise your base | Get Out The Vote |
| **Media Interview** | A press appearance to shape the narrative | Influence a Proposal, Raise Profile |
| **Set Piece Speech** | A major policy address | Influence a Proposal |
| **Private Dinner for Business Donors** | An exclusive fundraising dinner | Raise Funds |
| **Telethon for Small Donations** | A grassroots fundraising drive | Raise Funds |

!!! warning "Work in Progress"
    Currently, only the **Supporter Rally** event type has gameplay effects. Other event types are planned for future updates.

## Supporter Rallies

Supporter Rallies are the most impactful event type currently in the game. When a rally takes place, there is a **10% chance** it will trigger the **Energised Base** modifier for your party.

### Energised Base Modifier

When triggered, the Energised Base effect gives your party:

- **+20% turnout boost** for your supporters at election time
- Lasts for **10 game days**
- A social media post is automatically created announcing the rally's success

!!! tip "Timing Your Rallies"
    Schedule Supporter Rallies in the days leading up to an election. If the Energised Base modifier triggers, the turnout boost could make a real difference to your seat count. Since the effect lasts 10 game days, try to schedule rallies within that window before polling day.

### How It Works

```mermaid
graph TD
    A[Rally Day Arrives] --> B{10% Chance Roll}
    B -->|Success| C[Energised Base Activated]
    B -->|No Effect| D[Rally Passes Quietly]
    C --> E[+20% Turnout Boost for 10 Days]
    C --> F[Social Media Post Created]
```

## Assigning Activists

Every campaign event requires an **activist** from your party:

- Only non-expelled activists can be assigned
- The same activist can be assigned to events on different days
- [Recruit activists](characters.md) if you don't have enough for your campaign schedule

## Proposal-Linked Events

When choosing the **Influence a Proposal** objective, you can link your event to a specific active proposal and declare your stance:

- **For** - Campaign in support of the proposal
- **Against** - Campaign in opposition to the proposal

Only proposals that are currently open (not withdrawn or closed) can be targeted.

## Managing Events

### Editing Events

You can edit any **future** event to change its:

- Date
- Objective and event type
- Assigned activist
- Linked proposal and stance

### Moving Events

Drag or move events to a different future date. The same restrictions apply — you can't move events to election days or past dates.

### Deleting Events

Future events can be deleted from the calendar. Past events are preserved as part of your campaign history.

## Party Modifiers

Campaign activity and random events can trigger **party modifiers** — temporary buffs or debuffs that affect your electoral performance.

### Energised Base (Positive)

- **Trigger:** Successful Supporter Rally (10% chance)
- **Effect:** +20% turnout boost for your supporters
- **Duration:** 10 game days

### Campaign Finance Scandal (Negative)

- **Trigger:** Random event
- **Effect:** Voters are 10% less likely to vote for your party
- **Duration:** 3 months

Active modifiers are displayed on your party's profile page. Keep an eye on them — a well-timed Energised Base before an election can overcome a lingering scandal.

## Strategy Tips

!!! success "Best Practices"
    1. **Plan around elections** - Schedule Supporter Rallies 1-10 days before election day for maximum impact
    2. **Use your best activists** - Assign high-profile characters to important events
    3. **Fill your calendar** - One event per day means a full calendar shows an active, engaged party
    4. **Target key proposals** - Use Influence events to rally support for or against important legislation
    5. **Watch the odds** - Supporter Rallies have a 10% trigger chance, so schedule multiple for better odds of getting the Energised Base effect

!!! warning "Common Mistakes"
    - **Scheduling too late** - Events on election day itself are blocked
    - **Forgetting to assign activists** - Every event needs one
    - **Ignoring the calendar** - Campaign events are easy to overlook but can swing close elections

## Next Steps

- [Characters & Activists](characters.md) - Recruit activists for your campaign events
- [Elections & Voters](elections.md) - Understand how turnout affects results
- [Party Management](parties.md) - Overall party strategy
- [Political Power](resources.md) - Manage resources alongside campaigning
