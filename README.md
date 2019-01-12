# prog-time-voyage
Project - text quest in Python

Python text quest development

Romanov A.O.

Supervisor - engineer of the NIISI RAS Zotov Y.A.

Stupino branch of the MAI, department "System modeling and information technology"

The modern simplified name of the “text quest” game genre is derived from the English “interactive fiction”, which literally is an interactive fiction. Such literary works allow the reader to participate in the formation of the plot. On paper, such literature began to appear in the 1950s, first for educational purposes and then artistic and entertaining. Currently, it is called books-games (from the English. Gamebook). That book-games, at one time, became the prototype of computer text quests.

Text quests can be effective for students, and, last but not least, fascinating practice in language learning. They allow you to use in the development of the game a lot of operators to work with numbers, text, graphics, etc. Also, they can be a good starting point in the truly immense world of modern programming and really major developments.

The main objective of our work is to demonstrate the game in the genre of text quest, working in the programming language Python. The game involves many algorithms studied by students in higher education in the first year.

Structurally, the game can be divided into three parts:

1. Preface. It tells one day in the life of the protagonist, how and on what he decided to go on a journey that preceded it. In the course of this, the player is invited to independently choose the names of the characters, the city of departure and the arrival of the main character.
2. The main part. It consists of a choice of actions of the main character. Depending on the options chosen, he meets different people, communicates with them. If the hero, controlled by the player, does something wrong, behaves inappropriately, or answers illogically, then this results in a message indicating the player’s error and the end of the game. Thus, it is necessary not to make mistakes and move further along the plot.
3. Additional part. This section is highlighted in a separate menu item - “Easter eggs search”. The game contains five Easter eggs to quite well-known things in various areas of human activity. That is, each person will be able to find the first few easter eggs, more known to him. Finding a player even two Easter eggs is already considered an excellent result. And after finding them all, the player is given a special title and congratulations on the 100% passing of the game.

For convenience, the game is divided into functions responsible for the menu, the launch of the game, the display of messages and questions, the launch of the Easter eggs search. It also allows you to go back to the menu from any part of the game. Messages and questions for the main part are stored in a csv-file and displayed using the Pandas library. In the future, it is planned to supplement the plot of the main part, perhaps add a graphical interface.

Screenshots:
https://yadi.sk/i/iHZJUgm7IMbxaQ
https://yadi.sk/i/2q0AjQgeE1NznQ
https://yadi.sk/i/l3GhYjb3O0b99A
