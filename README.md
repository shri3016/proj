 # Project

This is the *official* repo for our team, submitting to the "Who Wants To Be A Hackionaire" Hackathon :smile:

![alternate text](https://www.techiedelight.com/wp-content/uploads/2016/11/Snakes-And-Ladders-Problem.jpg)

 # SnakeMate Game
  
 We have built a "Snakes and Ladders" plus "Chess" board game.
 
 It is a multiplayer game that combine aspects of game mechanism from both traditional games, "Snakes and Ladders" and "Chess".
 
  # Game Rules
  
 ```
    1.Once the player is on the board, he will roll the dice again and will be assigned a chess piece 
      that may be a King, Knight, or a Rook.
      
    2.When you roll a 6, you get an extra turn.
      
    3.The following conditions are follwed by the various chess pieces:
        
        a.A King can move forward by one block irrespective of the number rolled by the dice.
        b.A Knight will move forward by three steps if the die rolled is 3,4 or 5. If the dice rolled is 6, 
          then it will move 6 steps, and if the dice is rolled lower than 3 then it will not move. 
        c.A Rook can move any number of steps forward in that particular row, and so it will move the number rolled by the dice.
    
    4.If the player reaches the ladder, then he will transported to the top of that particular ladder.
    
    5.If the player encounters a snake, then he will be transported to the tail of the Snake.
    
    6.The first Player to reach the top will be the winner.
```
            
# Setup Instructions:

Python IDE
You will need to install the Pygame package using `pip install -r requirements.txt`
to run the game follow these commands in terminal

```
cd SnakeMate
python SnakeMate.py

```
