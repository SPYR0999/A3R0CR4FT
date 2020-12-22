Left click with a wooden axe of any block to place yout first marker on it (no you won't see it).
Right click with a wooden axe of any block to place yout second marker on it.

Here's some standard parameters :

```
x,y,z
```
>This argument refers to a specified location on the map.

```
pattern
```
>This argument represents the name or ID of a block ([here](https://minecraft-ids.grahamedgecombe.com)'s a list with the different IDs).

Here's a couple of basic commands (arguments in [] are modifiers and optionnal. The command works without them):

```
/unstuck
```
>Escape from being stuck inside a block

```
//wand
```
>This command gives you a wooden axe.

```
//undo
```
>undo the last operation

```
//redo
```
>redo the last undone operation

```
//search [-bi] [-p <page>] query
```
- //L and //searchitem works with same syntax and give the same result.
>search in the pattern list to find the ID of a specific item.
- -b (optional): Only search for blocks.
- -i (optional): Only search for items.
- -p <page> (optional): Search at a specific page.
- query: The item to look for.

```
//pos1 x,y,z
```
>This command places your first marker at the specified x,y,z coordinates.

```
//pos2 x,y,z
```
>This command places your second marker at the specified x,y,z coordinates.

```
//set pattern
```
>This command fills the marked area with the selected pattern.

```
//replace pattern1 pattern2
```
>This command replaces every block matching the pattern1 with the pattern2.

```
//walls pattern
```
>This command works the same as the //set command except it only fills the outer layer of the selected zone.

```
//cyl [-h] pattern radius [height]
```
>This command creates a cylinder around the player. It's base is at the same level at the feet of the player.
- -h (optional): makes the cylinder hollow.
- radius: the desired radius of the cylinder.
- height (optional): thedesired height of the cylinder. Leaving this argument empty will result in a height of 1.






[Here](https://worldedit.enginehub.org/en/latest/commands/#generation-commands) is a more complete list of the various commands and their syntax.
