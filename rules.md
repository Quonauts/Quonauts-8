# Quonauts 8: Heav'd once more — Rules

## Table of contents

* [**1. Meta rules**](#meta-rules)
    * [**1.1. Glossary**](#glossary)
    * [**1.2. Accuracy**](#accuracy)
    * [**1.3. Precedence**](#precedence)
    * [**1.4. Disallowed by default**](#disallowed-by-default)
    * [**1.5. Rule violations**](#rule-violations)
        * [**1.5.1. Errors**](#errors)
        * [**1.5.2. Rule violation polls**](#rule-violation-polls)
            * [**1.5.2.1. Punitive action**](#punitive-action)
    * [**1.6. Timezones**](#timezones)
    * [**1.7. Bots**](#bots)
    * [**1.8. Style conventions**](#style-conventions)
        * [**1.8.1. Content**](#content)
        * [**1.8.2. Headers and tags**](#headers-and-tags)
        * [**1.8.3. Lists**](#lists)
        * [**1.8.4. Formatting**](#formatting)
* [**2. Player state**](#player-state)
    * [**2.1. Roles**](#roles)
* [**3. Channels**](#channels)
    * [**3.1. #proposals**](#proposals-channel)
    * [**3.2. #rules**](#rules-channel)
    * [**3.3. #polls**](#polls-channel)
* [**4. Proposals**](#proposals)
    * [**4.1. Proposal content**](#proposal-content)
        * [**4.1.1. Conflict resolution**](#conflict-resolution)
        * [**4.1.2. Dependency resolution**](#dependency-resolution)
    * [**4.2. Voting on proposals**](#voting-on-proposals)
    * [**4.3. Closing proposals**](#closing-proposals)
        * [**4.3.1. Passing and failing proposals**](#passing-and-failing-proposals)
    * [**4.4. Editing proposals**](#editing-proposals)
    * [**4.5. Deleting proposals**](#deleting-proposals)
* [**5. Winning**](#winning)
* [**6. The end**](#the-end)
* [**7. Proposal #28**](#proposal-35)
* [**8. Quantities**](#quantities)

## <a name='meta-rules'/> Meta rules

This section details how the rules are to be applied to the game.

### <a name='glossary'/> Glossary

The definitions for terms listed here take precedence over their normal English meanings, however any terms defined in a specific section of the rules override these in the section in which they are defined and any subsections of that section. A section may also define terms for use in the whole document.

* **The Game**: The instance of Nomic governed by this rules document.
* **Game Channel**: Any text or voice channel listed under the "Quonauts 8" category of the Discord server.
* **Game Action**: Any modification of game channels, their content, or the game state.
* **Game State**: Every current rule, every non-deleted proposal and its votes, every player's state, and any winners.
* **Recorded Game State**: The game state, as recorded in the game channels.
* **Legal Game State**: The true game state, unaffected by any rule violations. Rules that refer to the game state, or information that is part of the game state, refer to the legal game state or its information.
* **Player**: Any participant of the game.
* **Active Player**: Any player who has performed a game action in the preceding 72 hours.
* **Inactive Player**: Any player who is not an active player.
* **The Rules**: The rules of the game, which are described by this document.
* **Section**: A part of the rules contained under one header. Unless otherwise specified, this does not include its subsections.
* **Subsection**: A section contained within another another section.
* **Clause**: A single statement in the rules.
* **Limited scope** (of two clauses): The clause with the most constraints.

### <a name='accuracy'/> Accuracy

This document is not guaranteed to always be up-to-date as the game rules are modified, however it is the duty of all players to keep this document accurate as game rules are modified. Where this document disagrees with the game rules, players must follow the game rules as they are in the legal game state, rather than their description in this document.

### <a name='precedence'/> Precedence

In the case of a contradiction between clauses, the following criteria are to be considered in turn until a clear determination can be made as to which clause takes precedence:

* If one clause has a more limited scope than another, then the clause with the more limited scope takes precedence.
* The clause which appears last in the rules takes precedence.

### <a name='disallowed-by-default'/> Disallowed by default

Unless explicitly stated in the rules, all game actions are forbidden.

### <a name='rule-violations'/> Rule violations

A rule violation is a game action that is not permitted by the rules.

If a rule violation occurs, the relevant game action/s do not affect the legal game state, however, the recorded game state may have been modified.

Resolving a rule violation is the process of reversing the effects of that rule violation in the recorded game state, to the extent that it is feasible.

#### <a name='errors'/> Errors

An error is a rule violation made by a player either mistakenly or through ignorance. If a player causes a rule violation and is able to resolve the error, they may do so.

If a player resolves an error within 24 hours of making that error, and the resolution of the error leaves the recorded game state in such fashion that it is as if the error had never occurred, no punitive action can be taken against the player.

#### <a name='rule-violation-polls'/> Rule violation polls

If any player (hereby "the accusing player") believes that another player (hereby "the accused player") has violated the rules, then the accusing player may conduct a poll (a "rule violation poll") to determine whether the accused player has violated the rules.

In conducting a rule violation poll, the accusing player must describe which sections or clauses of the rules were violated and what illegal game action was taken by the accused player. Players should vote in favor of this poll only if they agree that the accused player violated the rules as described.

Any vote in such a poll cast by the accused player is not counted.

A rule violation poll must be available for voting for at least 24 hours before any action may be taken as a result.

A rule violation poll may not be started more than 7 days after the potential rule violation.

For any potential rule violation, only one rule violation poll may be conducted.

If a rule violation poll passes, then the accused player is convicted of violating the rules as described in the poll and the rule violation must be resolved, if it has not already.

##### <a name='punitive-action'/> Punitive action

If a player (hereby "the convicted player") is convicted of violating the rules, another player may conduct a poll (called a "punitive action poll") to determine whether punitive action should be taken.

Players should vote in favour of this poll only if they believe the convicted player violated the rules knowingly and with malicious intent.

Any vote in such a poll cast by the convicted player is not counted.

A punitive action poll must be available for voting for at least 24 hours before any action may be taken as a result.

If a punitive action poll passes, then the convicted player may not perform any game actions for 24 hours.

### <a name='timezones'/> Timezones

Unless otherwise specified, all times and dates are specified with respect to UTC.

### <a name='bots'/> Bots

Certain game functions may be performed automatically by automated "bots"; the behavior of such bots is not governed by the rules, and any function that bots may perform should be feasible, even if inconvenient, to do manually.

### <a name='style-conventions'/> Style conventions

This section and its subsections describe grammatical and stylistic conventions used throughout this ruleset.

Any player may edit the rules to conform to these style conventions. Edits made this way must otherwise be minimal; i.e. they may not change wording or meaning. Note that the meaning of other, linked rule sections must not be changed by such an edit.

#### <a name='content'/> Content

* All rules should be written in English using proper English grammar and spelling. American and British English spelling are both acceptable.
* Where applicable, rules should be written using gender-neutral language, with "they/them/their" as a third-person pronoun, both singular and plural.
* Sentences should be separated by a single space.
* Paragraphs should be separated by a blank line.
* Each paragraph or list element must be shorter than 1000 characters.
* Rules may not contain invisible characters besides newlines, normal spaces, and (in special cases) tabs. Non-ASCII characters should be used sparingly.
* Double quotes should be preferred instead of single quotes. ASCII-compatible straight quotes should be used instead of "smart" quotes.

#### <a name='headers-and-tags'/> Headers and tags

* Each section must have a header and a tag.
* Headers must use [sentence case](https://en.wiktionary.org/wiki/sentence_case), and must be a short, succinct word or phrase (not a complete sentence) describing the section.
* A section tag must be a string of text begin with a lowercase letter, end with either a lowercase letter or a number, and may contain only lowercase letters `a`-`z`, digits `0`-`9`, and hyphens `-`.
* A rule's tag should resemble its header.
* Tags must be unique; no two rule sections may have the same tag.

#### <a name='lists'/> Lists

* Unordered lists should use a single asterisk followed by a space (`* `) before each list element.
* Ordered lists should use a single number followed by a period and a space (`1. `) before each list element.
* The numbers of a ordered list should start at `1` and increase by `1` for each element.
* Lists should not be nested.
* Lists should be separated by the paragraphs above and below by a blank line.
* Two lists of the same type can not be adjacent. (This is treated as one list when converted to Markdown.)

Within a given list, all elements should have the same style, chosen from the following:

* Elements are words or phrases, and do not end with a period.
* Elements are clauses ending in a period (or other punctuation), and optionally followed by complete sentences.
* Elements are complete sentences ending in a period, and optionally followed by more complete sentences.

#### <a name='formatting'/> Formatting

From [GitHub's "Mastering Markdown" document](https://guides.github.com/features/mastering-markdown/), the following may be used:

* Emphasis (italics and bold, not including double underscore `__`)
* Unordered and ordered lists (not nested)
* Links
* Inline code
* Automatic linking for URLs
* Strikethrough

Additionally, square brackets `[]` containing a tag will be converted into links to another rule section; e.g. `[%rule-tag]`. Discord mentions (@username, @role, and #channel) may be used, however they are not readable in GitHub-flavored markdown.

## <a name='player-state'/> Player state

Each player has their own "Player state". The player state of each player is part of the overall game state. Each subsection of this rule is part of each player's state.

### <a name='roles'/> Roles

The game rules govern roles that have effect within the game.

Each subsection of this rule corresponds to a role; as the subsections are created, removed, or renamed, roles must be created/removed/renamed accordingly.

## <a name='channels'/> Channels

The game rules govern only messages and reactions in the "Quonauts 8" category of the Discord server.

Each subsection of this rule section corresponds to a game channel; as the subsections are created, removed, renamed, or reordered, game channels must be created/removed/renamed/reordered accordingly.

### <a name='proposals-channel'/> #proposals

The <#694977941150367784> channel is governed by [**4. Proposals**](#proposals).

### <a name='rules-channel'/> #rules

The <#694977952923779173> channel contains this rules document.

### <a name='polls-channel'/> #polls

A poll is a means of gathering the opinions of players on an issue. Players may conduct a poll by providing any necessary detail and posting a question in the <#694655170000453705> game channel.

Players may vote in favor of a poll by reacting to the poll with 👍. Players may vote against a poll by reacting to the poll with 👎.

The player that posted a poll may edit it freely, as long as such edits do not change the meaning/intent of any existing reactions to the poll.

## <a name='proposals'/> Proposals

Proposals can be made by posting them to the <#694977941150367784> game channel.

The first proposal is numbered #1 and each subsequent proposal's number is increased by 1. Deleted proposals retain their number.

A proposal is either open or closed. When it is first submitted a proposal is open. A closed proposal is either passed or failed. When a player closes a proposal, they must either pass it or fail it. A deleted proposal is closed, but does not pass or fail.

### <a name='proposal-content'/> Proposal content

A proposal must describe one or more actions that make changes to the game rules or otherwise alter the game state.

A proposal must not depend on information outside of the game state, or propose a rule that does so.

If a proposal describes a modification to the rules, it must unambiguously specify the rule section(s) to be modified and how they will be modified.

If a proposal describes the creation of a new rule section, it must specify its title, its location in relation to an existing one, and its content. If the proposal conflicts with an existing rule, the proposal must explicitly note which rule takes precedence in which situation.

#### <a name='conflict-resolution'/> Conflict resolution

If multiple proposals describe the modification or addition of sections, paragraphs, or sentences to the same part of the rules, conflicts should be resolved based on the age of the proposal, such that the newer proposal's effect overrides the older one's. For example, if proposal #10 adds a new section "A" to the bottom of the rules, and proposal #11 adds a new section "B" to the bottom of the rules, and both proposals pass, then regardless of which proposal passed first, section "B" will appear below section "A" in the rules.

#### <a name='dependency-resolution'/> Dependency resolution

A proposal may state that it depends on other proposals. If a proposal's dependencies fail, then the proposal dependent on them also fails.

A proposal may also state it is incompatible with other proposals, in which case that proposal will fail if any proposal it is incompatible with passes.

### <a name='voting-on-proposals'/> Voting on proposals

Each player may cast one vote on each open proposal.

Players may vote for or against a proposal. Players may also explicitly abstain from voting.

A player may change their vote on an open proposal at any time.

### <a name='closing-proposals'/> Closing proposals

Any player may close an open proposal if one or more of the following conditions is met:

* The proposal is at least 48 hours (2 days) old.
* All active players have cast a vote on the proposal.
* A majority of active players have voted in favour of the proposal, and there are more than 2 active players.
* A majority of active players have voted against the proposal, and there are more than 2 active players.

#### <a name='passing-and-failing-proposals'/> Passing and failing proposals

When a proposal is closed, it passes if it has more votes in favour than against; otherwise, it fails.

The player that authored a proposal may fail it at any time.

When a player passes a proposal, that player must carry out the effects of that proposal and its passing to the best of their ability.

### <a name='editing-proposals'/> Editing proposals

A player may edit a proposal they have submitted if that proposal is open for voting and has no votes cast by players other than its author.

The author of a proposal or the player passing a proposal may choose to add or remove whitespace and fix typos or grammar mistakes, as long as the meaning of the proposal and any dependent proposals remains unchanged. Clarifications or additional  details should always be added by a new proposal.

### <a name='deleting-proposals'/> Deleting proposals

The author of an open proposal may delete it at any time.

## <a name='winning'/> Winning

The game cannot be won.

## <a name='the-end'/> The end

The game does not end.

## <a name='proposal-35'/> Proposal #28

The passing of proposal #25 was/is/will be legal. **This overrides all other rules where applicable.** Gibson loses quonauts 8.

## <a name='quantities'/> Quantities

A quantity is a named property with a numerical value for each player.

    By default any unique quantity added to the game:
    * applies to all players.
    * is instantiated at zero.
    * must always be an integer.
    * must never have a negative value.

    Quantities may be traded or exchanged in ways specifically allowed by the rules.

    The following quantities exist:
    * 

    When a new quantity is created, this rule should be edited to add it, along with a short description, to the above list. The description has no relevance to the game.

