# Quonauts 8: Heav'd once more — Proposals

<a name='1'/>

## #1

remove the rule that lets people add rules

<a name='2'/>

## #2

Create a new rule "Quantities" (%quantities) in %player-state:
> A quantity is a named property with a numerical value for each player.
> 
> By default any unique quantity added to the game:
> * applies to all players.
> * is instantiated at zero.
> * must always be an integer.
> * must never have a negative value.
> 
> Quantities may be traded or exchanged in ways specifically allowed by the rules.
> 
> The following quantities exist:
> * 
> 
> When a new quantity is created, this rule should be edited to add it, along with a short description, to the above list. The description has no relevance to the game.

Create a new rule "#transactions" (%transactions-channel) in %channels:
> The #transactions channel may be used to modify quantities, but only as the rules allow them to be modified.

<a name='3'/>

## #3

Create a new rule "Not a loophole i swear" (%not-loophole) under every other currently existant rule:
> If the current amount of seconds since the UTC epoch is a prime number, illegal actions are inconsequential, otherwise are considered null. Actions that are considered null have a 50% chance of also being considered void, and a 50% chance of merely being null. If an action is null but not void, then it means nothing, however if it is void then the action goes through this sequence again.

