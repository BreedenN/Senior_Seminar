<H1>Senior Thesis 2023</H1>

<H2>Use Cases</H2>

<div>1.0 Use Case Intro
  
Actor: Player

Overview: Greet player, display rules, ask player/bot count

Typical course of events
1. Intro is presented
2. Display rules to player
3. Ask player how many players there are
4. If there are any available spots, ask how many bots player would like present\\

2.0 Generate game

Actor: Player

Overview: The board and pieces will be generated

Typical course of events
1. Board will first be generated (Will be comprised of many smaller pieces that are then set next to eachother to generate an interactable board)
2. Player/bot pieces will then be generated and placed on their sides

3.0 Player order is determined

Actor: Player

Overview: Player can determine order, or can select choose random order

Typical course of events
1. Player manually selects who goes first
2. Then second
3. Then third
4. Then fourth

3.1
Alternate course of events
1. Player selects for a random order to be generated
2. First is randomly determined
3. Then second
4. Then third
5. Then fourth

4.0 Game begins

Actor: Player/Bot

Overview: Once player order is determined, the game is allowed to begin, and whoever is first takes their turn

Typical course of events
1. Player determines what direction they want to move, or if they want to place a wall
2. Once that action is choosen, it is then represented on the board

4.1
Alternate course of events
1. If bot is choosen to go first, algorythm will be run to determine what the best option is
2. This will then determine if it wants to place a wall, or move first

5.0 Game is played

Actor: Players/Bots

Overview: After initial move is taken, the rest of the turn order is followed each player/bot makes a moves onto the game is over

Typical course of events
1. Turn order is followed
2. Next player/bot chooses to move

Alternate course of events
1. Turn order is followed
2. Next player/bot places a wall

6.0 Game is finished

Actor: Players/Bots

Overview: When there is only 1 player/bot not finished, game is then determined as over and finished order is displayed

Typical course of events
1. First player/bot finishes
2. Game is played until there is 1 player/bot not finished
3. Finishing order is displayed and player is prompted to restart game</div>
