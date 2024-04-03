![image](https://github.com/6willum/battleship/assets/150245958/a37239e7-8d0e-40e9-a57a-5e7be4ec80ab)

Two game boards are created for each player and it creates empty lists to hold each players ship positions

![image](https://github.com/6willum/battleship/assets/150245958/07950218-781c-44d4-841c-b42ec656b459)

Checks who the opponent is based on current player.
Prints the players guesses and then prints the grid with the guesses using 'x' for a successful hit, 'o' for a miss and ' ' for an unmarked position.

![image](https://github.com/6willum/battleship/assets/150245958/c2e46fa9-9d14-46fb-8c07-2d50284cb0cd)

This asks the player to place their 4 ships by using a for loop. It checks whether the data is valid or not by checking whether there is already a ship there or if its actually within the grid.
If there is an error with the input then it prompts the player to reinput the data.

![image](https://github.com/6willum/battleship/assets/150245958/534b239a-34fe-43dc-876d-e6244b8bb93c)

It asks for an input to guess the location of the opponents ships and has some validation to ensure the data input works with the code, looping if the data is incorrect.
It checks if its within the bounds of the grid aswell
If the players guess was correct and it hits a ship then it prints 'Hit!', if it misses then it prints 'Miss!'. The grid is updated to have 'x' or 'o' based on the outcome.
There is also a check for whether the opponents final ship has been sunk using a Boolean Value.

![image](https://github.com/6willum/battleship/assets/150245958/63f67d5e-ca8b-43e3-88a5-ddff46aece9a)

There is an introduction message and the players are prompted to place their ships.
The game loop begins and player 1 is the first player.
The loop continues until either player has won.

![image](https://github.com/6willum/battleship/assets/150245958/8a2e6764-223c-43da-8d77-f629174ef1cb)

There is an input for the grid size.
The play() method is called and the game actually starts.


I also used these two websites as reference for some of my programming: 
1: https://codereview.stackexchange.com/questions/232013/a-simple-battleship-game
2: https://www.sourcecodester.com/python/15752/simple-battleship-gamevs-ai-python-free-source-code.html
