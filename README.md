# Lawmaker Game Wiki

The official player manual for [Lawmaker](https://lawmakergame.com), the multiplayer political simulation game.

- **Read the wiki:** [wiki.lawmakergame.com](https://wiki.lawmakergame.com)
- **Play the game:** [lawmakergame.com](https://lawmakergame.com)
- **Chat with other players:** [Discord](https://discord.gg/gKAvGTFKzB)

## Help improve the wiki

The wiki is written for players, and the best people to improve it are the ones who play. You don't need to be a programmer, and you don't need to install anything. If you can edit a document, you can fix the wiki.

Useful contributions include:

- **Fixing mistakes**: a wrong number, an outdated rule, a broken link, a typo.
- **Making things clearer**: rewriting a confusing paragraph, or adding an example that would have helped you when you started.
- **Filling gaps**: a question you had to ask on Discord that the wiki should have answered.
- **Trimming**: cutting something that's out of date, repeated elsewhere, or that nobody needs.

Not sure whether something is worth changing? Ask on [Discord](https://discord.gg/gKAvGTFKzB), or open an [issue](https://github.com/hankhank10/lawmaker-wiki/issues) describing what's wrong.

## How to make a change

You'll need a free [GitHub](https://github.com) account. Everything happens in your web browser.

1. **Find the page.** Go to the [wiki source on GitHub](https://github.com/hankhank10/lawmaker-wiki/tree/main/docs). The folder mirrors the wiki: the page at `wiki.lawmakergame.com/gameplay/elections/` is the file `docs/gameplay/elections.md`. (See [Where things live](#where-things-live) below.)
2. **Start editing.** Open the file and click the **pencil icon** ("Edit this file") at the top right. If GitHub asks, choose to fork the repository. That just gives you your own copy to work in.
3. **Make your change.** The **Preview** tab shows how your text will look.
4. **Propose it.** Click **Commit changes...** (or **Propose changes**). In the box, write a short title, such as "Fix early election cost", and a sentence on what you changed and why. If you're correcting a fact, say where you checked it (for example, "I saw this in game on the Budget page").
5. **Open the pull request.** GitHub takes you to a **Create pull request** page. Click it, and you're done.

That's all. A maintainer will read your change and either merge it or leave a comment asking for something to be adjusted; you'll get an email either way. Once it's merged, it's copied into the game's main repository and appears on the wiki. You don't need to do anything else.

Want to change several pages at once, or add a new page? The same steps work, and you can add a note in the pull request explaining what ties the edits together. For a brand-new page, ask on Discord first so we can agree where it belongs.

## Where things live

| To change... | Edit this file (in `docs/`) |
| --- | --- |
| The home page, getting started, game concept, strategy | `index.md`, `getting-started.md`, `game-concept.md`, `strategy-guide.md` |
| Costs, timers and thresholds at a glance | `reference.md` |
| The 16 issues and the laws catalogue | `laws-and-policies.md` |
| Parties and characters | `gameplay/parties.md`, `gameplay/characters.md` |
| Laws, elections and voter demands | `gameplay/legislation.md`, `gameplay/elections.md`, `gameplay/demands.md` |
| Campaigns and messaging | `gameplay/campaigning.md`, `gameplay/communication.md` |
| Government, constitution and courts | `gameplay/cabinet.md`, `gameplay/constitution.md`, `gameplay/supreme-court.md`, `gameplay/executive-actions.md` |
| Economy, treaties and global decisions | `gameplay/economy.md`, `gameplay/treaties.md`, `gameplay/global-decisions.md` |
| Monarchy | `gameplay/monarchy.md` |
| Countries, and starting a country | `countries.md`, `countries/avalon.md`, `countries/running-a-country.md` |
| The FAQ, rules and roadmap | `faq.md`, `rules.md`, `roadmap.md` |

This table lists every page, but pages get added, so if you can't find where something is described, search the repository for a phrase from the wiki page.

## Writing guidelines

The wiki should help a player **decide what to do**. It isn't a list of every feature.

- **Explain rules and why they matter.** Costs, limits, how long things last, who pays, what happens next, and the trap a new player might fall into. Complicated mechanics still deserve a proper explanation, but keep it to a few clear sentences.
- **Don't describe screens.** Skip where a button is, what colour a badge is, or what a page shows. Players can see that in the game. Write "a proposal costs 30 PP", not "click the Propose button at the top right".
- **Check your numbers in the game.** Costs and timers change. If you aren't sure a figure is current, say so in your pull request and we'll check it.
- **Say things once.** If a rule is already explained on another page, give one sentence and link to it (for example, `[Elections & Voters](gameplay/elections.md)`). [`reference.md`](docs/reference.md) is the home for PP costs and timers.
- **Write plainly, and to the player.** Use "you" and short sentences, explain a term the first time you use it, and don't assume the reader has played before.
- **Keep it fictional.** The [game rules](docs/rules.md) apply here too: no real parties, countries or people, and nothing built around race or religion.

### Formatting cheatsheet

Pages are written in Markdown. You'll only need these bits:

| You want | You type |
| --- | --- |
| A heading | `## Heading` (`###` for a sub-heading) |
| **Bold** | `**bold**` |
| A bullet list | a line starting with `- ` |
| A link to another wiki page | `[link text](gameplay/elections.md)` from a page directly in `docs/`, or `[link text](elections.md)` from a page inside `gameplay/` (the path is relative to the page you're editing) |
| A link to a heading | `[link text](gameplay/elections.md#polling)` (add `#` and the heading in lowercase, with dashes for spaces) |
| A tip box | `!!! tip "Title"` on one line, then the text on the next line indented by four spaces (it shows as a box on the wiki, not on GitHub) |

Copy the style of the page you're editing; that's the easiest way to get it right.

> **Please don't rename headings.** The game links directly to some wiki headings (its "?" help icons), and pages link to each other's headings. Renaming one can break those links. Reword the text under a heading freely, but if a heading itself really needs changing, mention it in your pull request and we'll update the links.

## License

All contributions are licensed under the MIT License.

---

*Built with [MkDocs](https://www.mkdocs.org) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).*
