# Countries

Lawmaker features multiple **fictional countries**, each functioning as an independent political simulation. This guide introduces the countries available in the game.

## How Countries Work

### Common Features

All countries share:

- [Political issues](laws-and-policies.md#political-issues) - Same 16 issue dimensions
- [Laws catalog](laws-and-policies.md#laws-catalog) - Same available laws
- [Game mechanics](game-concept.md) - Identical rules
- [Electoral system](gameplay/elections.md) - Proportional representation

### Unique Characteristics

Each country has:

- **Different population** - Affects scale of politics
- **Different legislatures** - Number and structure of assemblies
- **Different cabinet positions** - Unique government roles
- **Different constitutional offices** - Some countries may have monarchies or other special institutions
- **Different national moods** - Permanent moods reflect each country's established cultural character (e.g. a libertarian pioneering streak or a strong communitarian tradition)
- **Different player community** - Distinct political culture
- **Different history** - Unique legislative and electoral records

## Available Countries

### [Avalon](countries/avalon.md)

!!! example "Constitutional Monarchy"
**Population:** 65 million
**Legislature:** National Assembly (650 seats)
**System:** Westminster-style constitutional monarchy
**Elections:** Every 4 game years

Avalon is the flagship country in Lawmaker, featuring a large legislature (650 seats), a hereditary Crown, active player community, established political traditions, and complex coalition dynamics. [Read more about Avalon →](countries/avalon.md)

### [Marianne](countries/marianne.md)

!!! example "Republic"
**System:** French-inspired republican system
**Style:** Multi-party parliamentary democracy

Named after the French national symbol, Marianne offers distinct political character, European-influenced governance, and an active legislative system. [Read more about Marianne →](countries/marianne.md)

### [Columbia](countries/columbia.md)

!!! example "Presidential System"
**System:** American-inspired governance
**Style:** Presidential democracy

Columbia brings New World political traditions with a different executive structure, unique cabinet system, and distinct political culture. [Read more about Columbia →](countries/columbia.md)

### [Rheinland](countries/rheinland.md)

!!! example "Federation"
**System:** German-inspired federal system
**Style:** Federal parliamentary democracy

Rheinland offers federal governance with German political traditions, coalition-focused politics, and a structured approach to government. [Read more about Rheinland →](countries/rheinland.md)

## Private Countries

Some countries are set up as **private, invite-only** games. These are created by [supporters](../support) who want to run a closed game with friends or a specific community.

### How to Recognise a Private Country

Private countries are marked with a **padlock icon** on the country list and on their detail page. Instead of a "Create Party" button, you will see a **"Join with Invite Code"** button.

### Joining a Private Country

To create a party in a private country you need an **invite code** — a short alphanumeric password provided by the country owner.

There are two ways to join:

1. **Via the invite link** — The country owner can share a direct URL of the form `/countries/<country-slug>/new-party/<code>`. Opening that link takes you straight to party creation with the code pre-validated.
2. **Via the "Join with Invite Code" button** — Click the button on the country list or detail page, then type in your code when prompted.

If you enter an incorrect code you will see an error and can try again.

!!! tip "Getting an Invite Code"
    Ask the country owner to share their invite link with you. The shareable link looks like: `https://lawmakergame.com/countries/my-country/new-party/ABC123`

### Creating a Private Country

Private countries are a **[supporter-only feature](../support)**. If you have supporter status you can tick the **"Make this a private country"** option when proposing a country, and set your own invite code (up to 8 alphanumeric characters). A random 6-character code is suggested for you, but you can edit it.

### National Moods at Country Creation

When proposing a new country, you can choose one or more **permanent national moods** that define the country's cultural character from day one. These moods immediately influence how voters weigh issues and remain active unless a staff member removes them.

Each mood entry shows its emoji, name, and a one-line summary. Selecting a mood reveals the issues it pulls on and the direction of the effect (e.g. "pulls toward environmental protection"). You can pick multiple moods — their effects stack.

!!! tip "Choose moods that match your country's lore"
    Permanent moods are meant to reflect deep national character, not short-term events. Pick moods that fit the story of your country. Temporary moods (triggered by in-game events) can be added later by staff.

Learn more about how moods affect voters: [National Moods](gameplay/elections.md#national-moods)

!!! info "Supporter Feature"
    The private country feature is available exclusively to Lawmaker supporters. Visit the [support page](../support) to find out how to become a supporter.

## Country Flags & Flag Suggestions

Every country can have a **national flag** displayed on its detail page and in country lists. When a live country doesn't have a flag, any player can initiate a **48-day flag suggestion process** — a democratic way for the community to choose a flag together.

### How Flag Suggestions Work

#### Starting a Suggestion Process

When a country has no flag, any player with an active party in that country can **propose a flag**:

1. Navigate to the country detail page
2. Click the flag section (showing "This country has no flag yet")
3. Upload an SVG file (max 500 KB)
4. Once submitted, the **flag suggestion process starts** for 48 game days

All other players in the country receive **email notifications and Discord alerts** that a flag suggestion process has begun.

#### Participating in Suggestions

During the 48-day window, any player with an active party in the country can:

- **Upload one flag per party** (if you have multiple parties, you can submit one flag from each)
- **Upvote any suggestion** you like (multiple upvotes per suggestion)
- **View all suggestions** and current vote counts on the country page

Voting is anonymous — upvoters aren't shown publicly, but upvote counts are visible.

#### Resolution

When the 48 days end, the system **automatically selects the most-upvoted flag**. If there's a tie, the earliest-proposed flag wins.

The chosen flag becomes the country's official flag and is displayed on:

- Country detail page
- Country list pages
- Proposed countries list
- Any other country display

!!! info "One Process at a Time"
    Only one flag suggestion process can be active per country. Once a flag is chosen, it can only be changed if removed by staff.

### Including a Flag When Proposing a Country

When you propose a new country, you can optionally **include a flag at creation**:

1. Fill in the country creation form (name, legislatures, cabinet positions, etc.)
2. In the **"Country Flag"** section, upload an SVG file
3. The flag is set immediately when the country goes live

If you don't include a flag, the country will be flagless and any player can start the suggestion process later.

### Flag File Requirements

Flags must be:

- **SVG format** (.svg files only)
- **Maximum 500 KB**
- **Valid XML** with proper SVG markup
- **Safe** — scripts and unsafe content are automatically removed

!!! tip "SVG Tips"
    - Use free tools like Inkscape to create or modify SVG flags
    - Simplify your design to keep file size small
    - Test your SVG in a validator before uploading

## Proposing Public Countries

Any logged-in player can **propose a new country** to add to Lawmaker's public roster. Proposed countries go through a two-stage process before going live.

### How to Propose a Country

On the countries list page, click **"Propose a Country"** to open the creation form. You'll define:

- **Name** — Your country's name
- **Official name prefix** — [Optional] A prefix placed before the country name to form the official name (e.g. "The Republic of"). Leave blank to set no official name; it can be adopted later via constitutional amendment.
- **Description** — A short summary of its theme or lore
- **Population** — In millions (affects scale of politics)
- **System type** — The governance model (monarchy, republic, federal, presidential, etc.)
- **Legislatures** — How many assemblies and how many seats in each
- **Cabinet positions** — Government roles unique to your country
- **Constitutional offices** — Special roles like monarch, chancellor, etc.
- **National moods** — Permanent cultural moods that shape voter priorities
- **Country flag** — [Optional] Upload an SVG flag for your country at creation
- **Private option** — [Supporter-only] Make it invite-only instead of public

Once submitted, your proposal enters the **moderation queue**.

### Moderation & Community Voting

Proposed countries follow a two-stage approval process:

#### Stage 1: Staff Moderation

When you submit your proposal, it enters **moderation**. The Lawmaker team reviews it for:

- Lore quality and creativity
- Mechanical balance and viability
- Alignment with Lawmaker's vision
- Technical correctness

While awaiting moderation, your proposal is **not public** — only you and staff can see it. You can view its status on the countries list under **"My Proposed Countries"**.

**Outcomes:**
- **Approved** → Moves to Stage 2
- **Rejected** → You receive an email with the rejection reason; you can propose a revised version anytime

#### Stage 2: Community Voting

Once approved by staff, your proposal appears on the **[Proposed Countries](countries/proposals.md)** page, visible to all players. The community can now **upvote** it (login required) to signal interest.

Countries are sorted by upvote count, so the most popular proposals rise to the top. Staff reviews community feedback and decides when to grant final approval — moving the country from "up for vote" to "live" status.

### Tracking Your Proposal

On the countries list, your proposals appear under **"My Proposed Countries"** with a status badge:

- **Awaiting moderation** — Staff is reviewing it (not yet public)
- **Up for community vote** — Passed moderation; [see it on the proposals list](countries/proposals.md) where players can upvote it
- **Rejected** — Did not pass moderation; check the email for the reason and feel free to propose a revised version

!!! tip "Share Your Proposal"
    Once your country is up for community voting, encourage your friends to upvote it! Countries with strong community support are prioritized for launch.

## Choosing a Country

### Factors to Consider

When selecting which country to play in:

#### 1. Player Activity

Check which countries have:

- Active parties
- Regular proposals
- Frequent elections
- Engaged community

!!! tip "Join Active Countries"
The game is more fun when other players are active. Check recent activity before choosing!

#### 2. Political Landscape

Review existing parties:

- What ideologies are already represented?
- Where is there a gap you could fill?
- Which parties dominate?
- What coalitions exist?

#### 3. Your Preferences

Consider:

- **Large vs. small community** - More or fewer competitors?
- **Established vs. new** - Join mature politics or help build new country?
- **Political style** - Which system interests you?
- **Available niches** - Where can your party make an impact?

### Starting in a New Country

If you're new to Lawmaker:

1. **Research first** - Check country overview pages
2. **Review existing parties** - See who's already playing
3. **Check recent elections** - Understand power balance
4. **Read current laws** - Know the status quo
5. **Identify opportunities** - Find your niche

!!! success "Fill a Gap"
Look for ideological spaces not covered by existing parties. Creating a unique party is more impactful than copying others!

## Country Meta-Game

### Developing Culture

Each country develops unique:

- **Political traditions** - How coalitions form
- **Legislative norms** - What proposals are acceptable
- **Electoral patterns** - Typical vote distributions
- **Player relationships** - Alliances and rivalries

### Becoming Established

Long-term players in a country:

- Know the history
- Have existing relationships
- Understand unwritten rules
- Shape political culture

## Historical Events

Each country has a **Historical Events** section on its detail page, displaying major lore entries from its past. These are significant moments in the country's fictional history — typically 10–20 events spanning its existence.

### What counts as a historical event?

Historical events are **major, one-off moments** in a country's life story that give it depth and character. Good examples include:

- The founding or independence of the country
- A constitutional revolution or regime change
- A major war, invasion, or peace treaty
- A significant natural disaster or national crisis
- The discovery of a valuable resource
- A landmark social or cultural turning point

!!! warning "Don't duplicate what's already recorded"
    Events that are already tracked elsewhere in the game — such as **constitutional changes**, **elections**, and **passed legislation** — should **not** be entered as historical events. Use the historical events section for lore that isn't captured by those systems.

### Adding a historical event

Each event records a **year** (AD), a short **headline**, and an optional longer **description** that is hidden until a player clicks to expand it.

!!! info "One event per year"
    Only one historical event can exist per year in a country. If a year is already taken, you will see a warning as you type.

**Who can add events:**

| User type | Action |
|-----------|--------|
| Country owner or admin | **Add event** — published immediately |
| Any other logged-in player | **Propose event** — saved as a draft pending approval |

Proposed events are shown in a dashed style and marked **"Pending approval"**. Only the submitting player, the country owner, and admins can see them until approved.

### Approving proposed events

Country owners and admins see an **Approve** button on each pending event, and a **Reject & delete** button to discard a proposal that doesn't fit the country's lore. They can also **Delete** an already-published event from their country's record.

!!! info "Email notification for country owners"
    If you proposed the country (you are its owner), you will receive an **email notification** whenever a player submits a lore event proposal that is awaiting your approval — for any of your countries, public or private. The email includes the event year, headline, and description, along with a direct link to your country page where you can review and approve it. You can manage this notification in your email preferences.

## Country Information Pages

Each country has overview pages showing:

- **Historical events** - Major lore events from the country's past
- **Crown status** - Current monarch or vacancy details, for countries with a monarchy
- **National moods** - Active moods shaping voter priorities (click any mood badge to see which issues it affects and how long it lasts)
- **Current laws** - Status of all laws
- **Legislative history** - What's been changed
- **Active parties** - Who's playing
- **Seat distribution** - Current legislature composition
- **Government** - Current cabinet
- **Election schedule** - Upcoming votes
- **Recent activity** - Latest proposals and votes

## Tips for Country Selection

!!! success "Choosing Wisely" 1. **Check activity levels** - Join active countries 2. **Review existing parties** - Find your niche 3. **Consider your time** - Match commitment to activity 4. **Think long-term** - You'll be here for many election cycles 5. **Try the main country first** - Avalon is most established 6. **Communicate** - Talk to existing players before joining 7. **Be unique** - Fill gaps in political spectrum

## Next Steps

Once you've chosen a country:

- [Create your party](gameplay/parties.md) - Build your political organization
- [Review current laws](laws-and-policies.md) - Understand status quo
- [Check election schedule](gameplay/elections.md) - Know when you'll compete
- [Contact other parties](gameplay/communication.md) - Introduce yourself
- [Study the electorate](gameplay/elections.md#understanding-voters) - Learn voter preferences

Good luck building your political legacy!
