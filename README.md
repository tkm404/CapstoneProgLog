# CapstoneProgLog
Progress Log for Epicodus Capstone Project
## Project Overview:
#### "Iconoclast" is a card game based loosely on the rules of Rock-Paper-Scissors 
* Two players are presented with three different faction choices, and each player will pick two of those factions to build their decks.
* Each faction comes with a pre-made 15 card deck scaling up from weak to powerful cards in decreasing quantity.
* The chosen factions' decks are shuffled together to make the 30 card player deck.
* Players play through a Round by flipping over the top card of both decks simultaneously.
* The player whose card has the higher stats (influenced by their faction type. I.E. Rocks are better against Scissors...) wins the Bout.
* The player who wins the best 3 out of 5 Bouts wins the Round and earns points based on how many Bouts were played (a player earns more points for a Round that goes to Bout 5, for instance).

#### Further Objectives:
* Each faction has a leader, whose ability a player may invoke once per Round. Player's first faction choice is their main leader, who may use this ability.
* Tie games will repeat their Bout until the tie is broken (I.E. the round will not go to Bout 3 for as long as Bout 2 results in a tie).
* The trailing player is allowed to bet points on the next Round before the next Round begins. If they win, they get that many points extra. If they lose, they lose those points
* A full game or "Set" is played out over the best 2 out of 3 Rounds.

### 7/7/2023
*  07:59 Research Unity / C# combination practices.
*  08:23 Setup C# program, begin translation from original JS file to C#.
*  08:44 Make Card model in C# GameManager file.
*  09:00 Probably should have either downloaded Unity to my work laptop, or VS Code to my home desktop... coffee break.
*  09:20 Downloading code visualizer on home PC because its faster than getting unity on my laptop. For now.
*  09:49 Back on track with Unity and VS Code talking to each other.
*  10:19 Begin creating Unity assets and visuals.
*  10:48 Creating basic card design visual.
*  11:08 Begin writing code to link card fields to visual.
*  11:38 Double-check fields, begin linking code to visual.
*  12:00 Find and fix errors, getting ArgOutOfRange error.
*  12:18 Fixed Arg... error. Display for individual basic card works!
*  13:23 Resume Coding. Researching Scriptable Objects re: Unity.
*  13:45 Some debate re: Scriptable Objects. Moving on. Setting placeholder images.
*  14:03 Add placeholder images, add Sprite field to Cards.
*  14:27 Scratch coding the deck element. Will adjust as needed for my game's mechanics.
*  14:45 Research period for best ways to make my decks work.
*  15:05 Returning to original source for now. More research.
*  15:23 Continue research on rendering deck in Unity.
*  15:45 Researching drag and drop Unity functionality.
*  16:05 Switching research sources. Researching best way to implement "turn" functionality.
*  16:34 Light refactor based on new research sources.
*  17:05 Write Capstone Proposal. Submit this repo to Epicodus.

### 7/14/2023
* 08:43 Technical difficulties. Projects on home computer not on cloud storage, so installing Unity on Laptop a good idea, but not immediately productive. Had to swing by home. Desktop being a pill.
* 09:00 Update cards text to scalable mesh as opposed to static text image.
* 09:34 Many null reference errors. Working on a fix.
* 09:51 Shifting gears. Trying a new approach based on what I know so far.
* 10:24 Hit a bit of a dead end. Backtracking.
* 10:58 Re-researching Scriptable Objects.
* 11:41 Scriptable Objects are SUPER USEFUL ACTUALLY!
* 12:07 About halfway through rebuilding database of scriptable cards.
