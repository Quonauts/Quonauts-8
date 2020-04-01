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

