# Lab 8 The cool kid phase 1(UML diagram)

This project takes you through the process of developing a console-based game named “The cool Kid” using C++, focusing on object-oriented principles. Encapsulation and Information hiding, abstraction, Inheritance, and polymorphism will be used to enable the different components of the game of interacting with each other.

## What to submit for this phase:

A UML diagram for all the classes you identify in the game description. The UML diagram should be created on lucidchart.com

## Phase 1: Planning and setup(100 points)

    Identify Classes: Outline the core classes required to represent the game  and create a UML class diagram for all the classes you find in the description below using Lucidchart.com (sign up and choose the start free option). The class diagram should show all the classes below, attributes, functions, access modifiers and return types.

## Rules for “The cool Kid” game.

    Objective: The first player to reach the finish space wins.
    Equipment: A game board, 2 number dice, 1 operation die (+ or -), and 2  player tokens.

## Game description.

    The cool Kid game is a race for two players across a board to reach the finish line. Each player has a unique token to represent their position on the board. The game is played on a game board that consists of a linear series of numbered spaces, starting at the Start and ending at the Finish.
    During a player's turn, they roll three dice: two number dice and one operation die. The two number dice each have faces numbered from 1 to 6. The operation die has faces marked with either a plus + or a minus – (will always subtract the small m=number from the larger number). After rolling, the player performs a mathematical operation using the numbers and the operator, then moves their token forward the number of spaces equal to the result.
    However, the track is full of surprises. Some spaces on the game board are special.
    If a player lands on an Even/Odd space, they must roll a single number die. If the die roll matches the condition of the space (e.g., an even number on an "Even" space), they get to move forward that amount again. If it doesn't match(either by getting odd on even or if the spaces left on the board are less than the roll result), they must wait until their next turn.
    Other spaces contain a specific number, such as [N5], which we will call Number spaces. If a player lands on a Number space, they roll only the operation die. If they roll a + operation, they move forward the number on the space. If they roll a - operation, they must move backward that many spaces.

 

    There are also Shortcut spaces, which move the player instantly to a new, specified location further ahead on the board.
    The most dreaded spaces are the Endless Loop spaces. If a player lands on one, they are trapped, moving in a small circle of [L] spaces until they roll the exact number needed to escape onto the [Exit] space.
    The game continues with each player taking turns until one player successfully lands on or passes the Finish space and is declared the winner.
    36 spaces board is a reasonable board size that keeps the game interesting is 36.
    Suggested board layout

 Board Layout (36 Spaces)

#
	

Space Type
	

Notes

1
	

Start
	

Players begin here

2
	

Normal
	

3
	

Number [N3]
	

Roll + or –

4
	

Even
	

Roll even to move again

5
	

Normal
	

6
	

Shortcut → 12
	

Jump ahead

7
	

Odd
	

Roll odd to move again

8
	

Normal
	

9
	

Number [N5]
	

10
	

Even
	

11
	

Normal
	

12
	

Shortcut landing
	

13
	

Normal
	

14
	

Number [N4]
	

15
	

Normal
	

16
	

Odd
	

17
	

Normal
	

18
	

Normal
	

19
	

Number [N6]
	

20
	

Even
	

21
	

Normal
	

22
	

Shortcut → 26
	

Small jump

23
	

Normal
	

24
	

Odd
	

25
	

Normal
	

26
	

Loop entrance (L1)
	

Start of loop

27
	

Loop (L2)
	

28
	

Loop (L3)
	

29
	

Loop (L4)
	

30
	

Exit (X)
	

Roll exact number to leave

31
	

Normal
	

32
	

Number [N5]
	

33
	

Normal
	

34
	

Even
	

35
	

Normal
	

36
	

Finish
	

Winner! 🏁
