drac
====

Free, open-source, portable card game library that uses [SDL](http://libsdl.org/). It provides almost everything you need to create your very own card games. Drac is a set of C++ classes and functions that help simplify the development of card games. Any simple game specially solitaire games can be created using Drac with minimal effort. It can also be extended to accommodate more elaborate games such as [Tong-its](https://github.com/ricoz/tong-its/).

Features
========
* Card drag and drop support. Dragging cards around and dropping them to other destinations is a standard feature in most card games though this takes some effort to code, good thing Drac handles this for you. Not only that, Drac supports four types of dragging, you'll get to know them when you start using Drac in your card game projects. Also, dropping cards is as simple as setting flags that determine how a certain area accepts cards that are being dropped on it.
* Uses data structures to represent cards and card collections. Cards, card stacks, and card regions, including the game itself, is represented by a class. This greatly simplifies development since you only need to define what regions your game will need, and control those regions based on the rules of the game.
* Includes useful functions such as getting card information like card rank, suit, value, etc. Functions for overlapped cards and determining what card to accept based on the amount of area that overlaps are already built-in.
* To show how simple it is to use Drac, a sample game, the famous Klondike is included. The game was coded in just a few lines. A tutorial explaining how Klondike was made can be found here.
* Includes a simple animation that you can use whenever a player wins a game. Remember the animation you see whenever you win a solitaire game in windows, Drac also has one, and you can make your own too with a bit of coding effort.
* Portable. Has been proven to run on [Nokia Maemo platform](http://maemo.org/downloads/product/OS2008/maemodrac/) (now part of MeeGo), [Sega Dreamcast](http://www.dcemu.co.uk/vbulletin/threads/221403-KlondikeDC), [Popcorn Hour](http://www.networkedmediatank.com/showthread.php?tid=39054), [BeOS](http://www.bebits.com/app/3799) and [Haiku](http://haikuware.com/directory/view-details/games/cards/tong-its).

Acknowledgments
========
* Bitmap Font by [Marius](http://cone3d.gamedev.net/) (old dead link)
* [James Brown](http://www.catch22.net/) for his help and for his great program CardLib which inspired this project.
* [Oxymoron for the card images used](http://www.waste.org/~oxymoron/cards/)
* [Stephen Murphy's](http://www.telusplanet.net/public/stevem/) QCard32.dll for the card symbols used. (old dead link)