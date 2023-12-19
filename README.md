# Tic-Tac-Toe_AI
Welcome to my Project 'Tic-Tac-Toe_AI', an exciting project where the classic game of Tic-Tac-Toe and Reinforcement Learning are brought together to fight my inability to make friends. This AI, utilizes reinforcement learning to develop optimal strategies and policies to engage in strategic gameplay against human opponents.

- - - - 

## Features 🔑
* __Reinforcement Learning__ : Utilizes Q-leanring to evolve AI's decision making prowess.
* __Human vs AI Duel__ : Challenge yourself against the AI in intense Tic-Tac-Toe battles.
* __Light Execution__ : Rather than using a deep-learning model, this model simply utilizes previous experiences to create a Q-Table.

## Prerequisites 📚
Ensure that the following libraries are installed.
* Install Colorama : `python -m pip install colorama`
* Install Termcolor : `python -m pip install termcolor`

## Run 🏃
* Clone repository on Local Device.
* Run following command at stored destination : `python TIC_TAC_TOE.py`

## Creating Custom Policy 📄
Q-learning Utilizes policies(Rules created by model during training/Table consisting of best possible move for a situation the model has seen) to run model when working against human players. Custom Policies can be created using 'PolicyMaker.py', by changing the training rounds for model - an easier or harder policy can be created proportional to the rounds trained on. 

Different policies can be used by providing different policy in 'loadPolicy' function after created Player as 'Computer'.
