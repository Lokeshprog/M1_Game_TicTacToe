
# TEST PLAN

## Table No 1: High level test plan

| Test ID | Description | Exp I/P | Exp O/p |
| ------- | ----------- | ------- | ------- |
| H_01 | Check if the graph for playing is being drawn or not. | No input. | 3X3 graph is drawn. |
| H_02 | Check if player/computer got 3 of his inputs in vertical, horizontal or diagonal format. | 'X' or 'O' i/p from the user/computer. | The user/computer won the game. |
| H_03 | Check for draw. | 9 inputs from (user+computer). | The game is over. |

## Table No 2: Low level test plan

| Test ID | Description | Exp I/P | Exp O/p |
| ------- | ----------- | ------- | ------- |
| L_01 | Checking for the basic requirement to the game, i.e., a 3X3 graph is drawn or not. This 3X3 graph is the basic need to play the game as it is like a game board for the game. |	Not input expected from the user.	| 3X3 graph is drawn. |
| L_02 |	Play proceeds with the user/computer alternately placing their marks in any unoccupied cell. Check if any player/computer finishes with 3 marks in a row(vertical, horizontal or diagonal). |	'X' or 'O' i/p from the user/computer. |	The user/computer won the game. |
| L_03 |	Check if a total of 9 moves have been made( combining that of user and computer), the game ends up in a draw when neither the user nor the computer is able to get 3 marks in a row. |	9 inputs from (user+computer). |	The game is over. Somebody won or the game ended as a draw. |

# OUTPUT

- **Below output shows the menu to select X/ O/ Exit**

  ![output](https://user-images.githubusercontent.com/82743874/143025412-26490292-5640-4ea9-8efc-4518e3e6f479.JPG)

- **Below output is shown when the player wins**

![output2](https://user-images.githubusercontent.com/82743874/143025857-afb5c608-4369-4c05-9379-9952ff972cc1.JPG)

- **Below output is shown when the computer wins**

![output4](https://user-images.githubusercontent.com/82743874/143025901-cd6576e3-7ff7-4f07-95e0-703b0ff58848.JPG)

- **Below output is shown when the game is draw**

![output3](https://user-images.githubusercontent.com/82743874/143025938-f63ce05e-a7b7-4983-b991-ffd5edeab350.JPG)

