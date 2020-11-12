# prog-time-voyage
Project - text quest in Python

Structurally, the game can be divided into three parts:

1. Preface. It tells one day in the life of the protagonist, how and on what he decided to go on a journey that preceded it. In the course of this, the player is invited to independently choose the names of the characters, the city of departure and the arrival of the main character.
2. The main part. It consists of a choice of actions of the main character. Depending on the options chosen, he meets different people, communicates with them. If the hero, controlled by the player, does something wrong, behaves inappropriately, or answers illogically, then this results in a message indicating the player’s error and the end of the game. Thus, it is necessary not to make mistakes and move further along the plot.
3. Additional part. This section is highlighted in a separate menu item - “Easter eggs search”. The game contains five Easter eggs to quite well-known things in various areas of human activity. That is, each person will be able to find the first few easter eggs, more known to him. Finding a player even two Easter eggs is already considered an excellent result. And after finding them all, the player is given a special title and congratulations on the 100% passing of the game.

For convenience, the game is divided into functions responsible for the menu, the launch of the game, the display of messages and questions, the launch of the Easter eggs search. It also allows you to go back to the menu from any part of the game. Messages and questions for the main part are stored in a csv-file and displayed using the Pandas library. In the future, it is planned to supplement the plot of the main part, perhaps add a graphical interface.

Screenshots:
https://yadi.sk/i/iHZJUgm7IMbxaQ
https://yadi.sk/i/2q0AjQgeE1NznQ
https://yadi.sk/i/l3GhYjb3O0b99A
