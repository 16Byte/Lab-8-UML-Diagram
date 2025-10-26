# Lab 8: The Cool Kid - Phase 1 (UML Diagram)

## About

UML class diagram for "The Cool Kid" - a two-player board game where players race to the finish by rolling dice and navigating special spaces.

## What's Included

- UML diagram showing all game classes
- Attributes, methods, and access modifiers
- Inheritance relationships between classes

## Classes Designed

Main Classes:
- Game, Board, Player, Token

Dice:
- Die (abstract), NumberDie, OperationDie

Spaces:
- Space (abstract)
- NormalSpace, StartSpace, FinishSpace
- EvenOddSpace, NumberSpace, ShortcutSpace
- LoopEntranceSpace, LoopSpace, ExitSpace

## Next Phase

Implement the game in C++ using this UML design.
