# International Treaties

A **treaty** is an agreement between *countries*, not between parties. A country founds a treaty from a fixed list of **treaty articles**, other countries join it, and for as long as a country is a member its own laws are bound by the treaty: parties there can no longer propose moving a **locked law** to an option the treaty forbids.

Treaties are free to found, join and leave: there is **no Political Power cost and no cooldown**. The price is the promise itself. Once you are in, your country's hands are tied.

!!! note "Treaties are not blocs"
    [International blocs](communication.md#international-blocs) are alliances of *parties* with shared ideological goals. Treaties are agreements between *countries*, decided by whoever holds the country's treaty power, and they bind the country's laws. The two features are independent.

You'll find treaties under **International → International Treaties** in the world menu, which lists every treaty in the game. Each country also has its own **International Treaties** page, under **International** in its country menu, and a **Treaties** card on its country page.

## Who decides: the treaty power

Founding a treaty, joining one, leaving one, inviting another country and answering an invitation are all acts of whoever holds the constitutional power **Ratify Foreign Treaties**. Like any power in the [constitution](constitution.md), it is assigned to a holder, and it works differently from most:

- **It is always held by a single office**: a cabinet position, an elected office such as a presidency, or the monarchy. It can **never** be held by a legislature (a chamber) or by professional bureaucrats. A constitutional change that tries to move it there is refused, and abolishing its current holder automatically moves it to a new single office (the head of government where possible) instead of to the bureaucrats.
- **Only the holder acts.** The party that holds the office (the party owner, acting as that party) makes every treaty decision for the country. Other players in the same country can see everything, but the buttons stay off for them, with a note saying who decides.
- **A monarch holding the power acts freely.** Unlike [executive actions](executive-actions.md), treaty acts cause no [constitutional crisis](monarchy.md) and add nothing to anyone's autocracy score.
- **If the office changes hands, so does the decision.** An invitation waiting for an answer goes to whoever holds the power *now*.

!!! info "If nobody holds the office"
    An office can be briefly vacant (an elected office between elections, or an empty throne), or its holder can be a character without a party. Then nobody can found, join, leave, invite or answer for that country until the power has a live holder again. The country is still bound by every treaty it belongs to, and it **can still be invited**: the invitation simply waits for the next holder. No message or email is sent while nobody holds the power, so the holder should check the country page after taking office.

Countries that used to give this power to a chamber or to the bureaucrats had it moved to their head of government when treaties were introduced. You can move it to another single office with an ordinary [constitutional change](constitution.md#proposing-a-change).

## Open and closed treaties

Every treaty is one of two kinds, chosen when it is founded and **fixed for good**:

| Kind | How a country joins |
| --- | --- |
| **Open** | Any eligible country whose laws satisfy every treaty article joins on its own, straight away. There is no approval step. |
| **Closed** | A country joins only by **accepting an invitation** from the treaty's founder. |

A treaty that wants to change from closed to open (or the reverse) has to be dissolved and founded afresh.

A country is **eligible** to found, join or be invited unless it is still a draft country or has been paused by the game's administrators. [Private countries](../countries.md) are eligible on the same terms as public ones.

## Founding a treaty

A treaty has a **name** (up to 120 characters, unique among the active treaties in the game), an optional **preamble** that states its purpose in the founder's own words (up to 2,000 characters), an open or closed setting, and **1 to 20 treaty articles**. Names and preambles are moderated like other public text.

Only the treaty power holder can found a treaty, but anyone with a party in the country, or the crown, can help write one.

### Drafting

Treaties are written as **drafts** first. A draft is a saved, editable treaty that belongs to *you*, not to your party, so you can keep working on it even if your party disbands. Drafts come in two kinds:

- **Private** drafts are visible only to you.
- **Public** drafts are visible to everyone with a party in your country, so a treaty can be worked up in the open and offered to whoever holds the power.

The builder shows a live **"Would your country qualify?"** panel as you add treaty articles, so you can see straight away whether your own laws satisfy the terms you are writing.

Nobody can create a treaty from somebody else's draft directly. Instead, the holder **takes up** a public draft: it is copied into their own private drafts, credited to the original drafter ("based on a draft by ..."), and they can edit it freely before creating the treaty from their copy. Anyone in the country can take up a public draft in the same way to build on it. When the treaty is created, the draft it came from is marked as taken up.

### Founding it

The holder creates the treaty from their own draft. The founding country has to meet **its own terms** to begin with:

- its current laws must satisfy every treaty article, **and**
- it must have no [open bill](#open-bills-block-joining) that would breach one.

The founding country becomes the treaty's first member and its **founder**.

## Treaty articles and locked laws

A treaty is made of **treaty articles**. (Laws have articles too, so this manual always says *treaty articles* for these.) Right now there is one kind: the **law lock**. Treaty articles are written once, when the treaty is founded, and **can never be changed afterwards**. To change the terms, found a new treaty.

### Locked laws

A law lock names one **law** and the **options the treaty allows** for it. For example, a treaty might lock *Minimum Wage Policy* so that it must be either *Basic minimum wage* or *High living wage*, ruling out *No minimum wage*.

A few rules keep locks meaningful:

- A lock must **forbid at least one option**. An article that allows every option locks nothing, and is refused.
- A treaty can lock **each law only once**.
- A treaty holds **at most 20** treaty articles.

While your country is a member, **its parties cannot propose moving a locked law to a forbidden option**:

- In the proposal builder the forbidden options show as **disabled**, suffixed with *(locked by* and the treaty's name*)*, with a note linking to the treaty. A law whose every other option is locked is still listed, so the restriction stays visible.
- A bill that contains a forbidden option is refused if you try to save it or put it to the vote.
- A draft written *before* your country joined can still exist, but cannot be opened for a vote until you edit out the locked option.
- On your country's **Laws** page and in the **International Laws Explorer**, a law under a lock carries a **Treaty-locked** badge listing the treaties responsible.

If a country belongs to **several treaties** that lock the same law, only the options **every one of them allows** stay open.

Locks only restrict *bills that change a law*. They don't touch [constitutional changes](constitution.md) or [executive actions](executive-actions.md), and they only bind the members' own laws, never any other country's.

!!! note "Retired laws"
    If a locked law is later retired from the game, its treaty article becomes **inert**: it is shown struck through, locks nothing, and nobody is removed from the treaty because of it.

## Compliance: satisfying every treaty article

A country **complies** with a treaty when its current laws sit inside the allowed options of every treaty article. Compliance is checked whenever a country wants to found, join or accept, and the treaty page shows your country's report as a checklist, one line per treaty article, with what you would have to change.

### Open bills block joining

Compliance looks at your laws **and at your country's open bills**. If any bill that is open for voting, or has closed but not yet been counted, would move a locked law to a forbidden option, the country **cannot found, join or accept** until that bill has been decided or withdrawn. The treaty page names the bill.

The treaty never withdraws or freezes the bill: it simply waits. Note that this means any party can delay its country's accession by opening a breaching bill, so watch what your rivals are proposing when you are trying to join.

## Joining

**Open treaty.** The holder presses **Join** on the treaty's page. If your country doesn't qualify, the button is disabled and the reasons are listed.

**Closed treaty.** The treaty's founder sends your country an **invitation**, and the holder accepts it. A closed treaty shows "By invitation only" to countries without one.

Whichever way you join, your country is bound the moment it becomes a member, and the treaty's locks start to apply at once.

## Invitations

The **founder** (see [below](#founder-succession)) can invite any eligible country that is not already a member and has no invitation pending. Invitations work on both open and closed treaties. The founder can add an optional **message** (up to 500 characters).

- **Compliance isn't required to be invited.** The invitee can see exactly which laws it would have to change first.
- An invitation **expires after 90 game days**. The country is told when it does.
- The founder can **withdraw** a pending invitation at any time.
- The invited country's holder can **accept** (only while the country complies) or **decline**, optionally saying why. A decline reason is shown to the inviter. Accepting an invitation that the country can't yet satisfy is refused, and the invitation stays pending, so you can fix your laws and come back before it expires.
- An invitation also disappears if the treaty is dissolved.

Pending invitations show on the receiving country's page, in a **Treaties** card that everyone can read. Accept and Decline are visible to everyone but usable only by the holder of the treaty power, and greyed out with an explanation for everyone else.

## Leaving

The treaty power holder can **leave any treaty at any time**, with no cost, no cooldown and no approval. Every law the treaty locked is free again immediately. The leave button lists which laws will unlock.

Leaving is not a way round the rules: to rejoin, your laws have to satisfy the treaty again, and while you're a member you cannot open a bill that breaks it.

## Founder succession

The **founder** is the member country that runs the treaty: it sends and withdraws invitations, and it alone can dissolve the treaty. It starts as the country that created the treaty.

If the founder leaves (or is removed for breach, or its country is deleted), the **longest-standing remaining member** becomes the new founder, with every founder right. That country's holder is told. The original founder is kept on the treaty page for history only: if it returns later, it is an ordinary member.

Succession doesn't check who currently holds the new founder's treaty power. If its office is vacant, the founder's acts (inviting, withdrawing, dissolving) wait until the power has a holder again, but the other members can still leave.

## Dissolution

A treaty ends in one of two ways:

- **The founder dissolves it.** The founder's holder can do this at any time. Every member leaves at once, every lock lifts everywhere, and pending invitations are withdrawn. Every other member's holder is told.
- **The last member leaves.** With nobody left, the treaty dissolves.

A dissolved treaty isn't deleted: it stays on record, hidden from the default treaty list (use **Show dissolved** to see it), with its former members and how each left. Its name becomes free for a new treaty, which gets a fresh page.

## Breach

Members must **always comply**, and the treaty machinery guarantees it: a locked law can't be moved by an ordinary bill, and a bill that would break a treaty blocks joining in the first place.

The one route around that is a [Supreme Court](supreme-court.md) ruling. If the court orders a law changed to an option that a treaty forbids, the country is **removed from that treaty immediately**. There is no grace period and no "in breach" status. The country's holder and the treaty's founder are both notified, an email goes to the holder, and the press covers it.

A country removed for breach can rejoin as soon as its laws comply again, by the usual route. Removal for breach can pass the founder's role on, or dissolve the treaty, exactly like any other departure.

## Notifications

You'll hear about treaties in the following ways, depending on your role:

- **The treaty power holder** gets a **system message** for the events that concern their country: an invitation received, withdrawn or expired; an invitation they sent being accepted or declined (with the reason); a member leaving; a breach removal; the founder dissolving the treaty; becoming the new founder. An **email** goes out when an invitation arrives and when the country is removed for breach.
- **The holder also sees a to-do item** on the dashboard for pending invitations, and the International menu is flagged. System messages don't count towards the unread badge, so this item is the one to watch.
- **Everyone** can see treaty news: the country's press coverage reports treaties being founded, joined, left, dissolved and breached, and each treaty's page lists its members and history.

## Tips

!!! tip "Read the whole checklist before you commit"
    A treaty binds your country's law-making for as long as you're a member. Before you accept or join, look at every locked law and ask whether your party (and your rivals) will want to move it. Leaving is free, but only whoever holds the treaty power can do it, and that may not be your party.

!!! tip "Watch out for the bill that blocks you"
    An open bill that breaks a treaty article stops your country founding or joining until it's decided. If you're courting a treaty, tell your coalition partners not to open a conflicting bill.

!!! tip "The court can end a membership"
    A successful [Supreme Court](supreme-court.md) appeal against a locked law removes the country from the treaty the moment it lands, so opponents of a treaty have a way out that no vote can block. If you rely on a membership, remember that the court can undo it.

!!! tip "Own the power, own the treaties"
    The treaty power is one of the [constitution's](constitution.md) 18 powers. A party that holds it decides the country's foreign commitments, so it is worth bargaining for in [government formation](cabinet.md) and [constitutional changes](constitution.md).

!!! tip "Write your treaty in public"
    A public draft lets other players in your country improve your terms before the holder commits, and the holder can take it up and edit their own copy without losing the original.

## Next steps

- [Constitution](constitution.md): the treaty power and how powers are assigned.
- [Legislation & Voting](legislation.md): the proposals that locked laws restrict.
- [The Supreme Court](supreme-court.md): court orders, and how they can end a membership.
- [Communication & Coalitions](communication.md#international-blocs): international blocs, the party-level alliance.
