# **fantastic-bassoon**

## **Reinforcement Learning to play a game - Nim**

Applying Reinforcement Learning to play a simple game

**What is Nim?** Well, in the game Nim, we begin with some number of piles, each with some number of objects. Players take turns: on a player’s turn, the player removes any non-negative number of objects from any one non-empty pile. Whoever removes the last object loses.  

In this project, I have built an AI to learn the strategy for this game through reinforcement learning. By playing against itself repeatedly and learning from experience, eventually the AI will learn which actions to take and which actions to avoid.

In particular, I have used Q-learning for this project.
First, run the below commands to get to the correct directory:
```console
cd <directory where this repository exists>
```
```console
cd fantastic-bassoon/nim
```
Next, you have to run this command to play against the AI:
```console
python play.py
```
