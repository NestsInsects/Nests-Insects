Nests & Insects
===============
X:https://x.com/NestsInsects
This is the repository for AI the rulebooks and code of Nests & Insects, a Roguelike
different worlds different universes Roleplaying Game
![image](https://github.com/user-attachments/assets/719f87eb-ec80-4e31-ad49-7b2b35767d09)

Nests & Insects is loving ly crafted by hand in a text-based format with custom
layout code and glorious ASCII.

![image](https://github.com/user-attachments/assets/830de7fa-6b41-4721-8ce2-62ac044c0726)

Figure 1: The Nests & Insects rulebooks in vim with syntax highlighting.

Nests & Insects is still a work in progress, in the early stages of design and
playtesting. To see how much is done and how much remains to be done, check out
the TODO file and `changelog.md`.
![image](https://github.com/user-attachments/assets/dccd52d6-1605-4aa3-99c6-7dbafaa708ef)

![image](https://github.com/user-attachments/assets/5fae5f64-24af-46ec-9123-4f6ae17306b9)

The Game
--------
<img width="497" alt="image" src="https://github.com/user-attachments/assets/66240a62-9260-48d1-8e26-8630c5cc3c03" />


Nests & Insects is a tabletop roleplaying game (TTRPG) for 2 to 7 players. One
player assumes the role of the Game Queen and describes the game world to the
other players. The other players control characters who explore, and interact
with, the game world.

### Characters

Players' characters are arthropods that belong to one of six classes: Spider,
Wasp, Scorpion, Ladybug, Beetle and Ants (plural). The characters are
mercenaries, assassins, and thugs, hired to invade a Nest and carry out a Job on
behalf of some arthropod client. Nests are the homes of eusocial insects: the
nests of Bees, Ants and Termites. Common Jobs are to assasinate the Queen, or
the King; steal nectar, honey, honeydew, aphids or mealybugs (farmed by ants) or
fungi (cultivated by termites); steal, or kill, larvae; deliver, or pick up a
message; or sabotage the Nest.

### The Nest

At the beginning of a new game the players' characters enter a Nest to carry out
their Job armed with their natural weapons and armour: mandibles, pincers,
stingers, carapaces, wings, venom, webs. During a Job characters must survive
combat with the soldier castes guarding the Nests. They must also hunt or forage
for food to avoid weakening and starving to death. While foraging, characters
may find food items, such as nectar and fungi, that can be consumed to provide
not only sustenance but also healing, enhanced physical and mental abilities and
other benefits.

### A tabletop roleplaying game

Nests & Insects is a tabletop roleplaying game: the players say what their
characters want to do and roll the dice to see what happens. Then the Game Queen
describes the results of the characters' actions. Nests & Insects' roleplaying
system is a percentile system where a composite, "percentile" die (d100) is
rolled to determine the outcome of actions and composite "decile dice" (d20,
d40, d60, d80, d120 and the d100 itself) are rolled to quantify the results of
actions. The system is designed to remove all mental arithmetic from "action
resolution" and to encourage the players to use their imagination to help their
characters achieve their goals. Everything characters encounter in Nests &
Insects is procedurally generated: the Nest, its guardians, items, all
challenges and rewards.

### A roguelike tabletop roleplaying game

Nests & Insects is a "Roguelike" TTRPG: it is inspired by Roguelike Computer
RPGs (CRPGs) such as Nethack, Angband, Moria, ADoM and newer games like Diablo
and Darkest Dungeon. From Roguelike CRPGs it borrows: procedural generation;
hack-and-slash, dungeon-crawling gameplay; lethal combat; hunger mechanics; and
a focus on exploration and experimentation with the game world. From TTRPGs it
borrows: weird dice; tortuous terminology with Pompous Capitalisation;
over-engineered rules; unclear motivation to learn yet another roleplaying
system; and crunch Crunch CRrRUNCH!

Reading the rulebook
--------------------

The text-based rulebook is in the following path:
```
<project root>/game/rulebook/txt/nests_and_insects.txt
```

_The text-based version is the only version of the rulebook._

To read the text-based rulebook, you can open the rulebook file in your
favourite text editor. On Windows, Notepad and Notepad++ work fine. On Windows
and everywhere else, vim, emacs and friends should work as well as usual.

Once you open the file, you should be greeted by the glorious ASCII of the
rulebook cover. 

Alternatively, in your system's terminal navigate to the rulebook's directory
and open it with a pager like less or more etc. For instance, using less:

```
cd .../game/rulebook/txt/
less -z 50 nests_and_insects.txt
```

Calling less with the argument "-z 50" sets the number of lines per page to 50,
as in the rulebook's page height. This lets you page up and down by pressing z
or w, even if your terminal's screen height is not exactly 50 rows.

Preferred fonts
---------------

The rulebook, and, in particular, its cover page, are best rendered in the free
font DejaVu Sans Mono. You can download it from here:

https://dejavu-fonts.github.io/

Running the code
----------------

The ironically named /codez directory contains Prolog code used to manage game data and
generate characters, character sheets etc. Also, to lay-out the text-based rulebooks. It
is not necessary to peruse the codez directory to play the game- it is only included for
the game developer's convenience.

Reporting Errors
----------------

The text-based rulebook is formatted with the code in the Prolog module
`codez/src/layout.pl`. This, too, is a work in progress. If you find major formatting
errors, or any errors, in the rulebook, please report it by emailing the game's author
at `(https://x.com/NestsInsects )`. You're welcome to send a pull request instead.


