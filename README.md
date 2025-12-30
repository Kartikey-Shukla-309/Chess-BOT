# Chess-BOT

This is a Machine Learning project on a CNN based Chess Engine inspired by ideas behind Google DeepMind's AlphaZero like, using a neural-network for analysing a position and a policy-head for move selection. Being a college project its a very low-level implementation of that idea for my own learning. It is capable of playing moves like castling, captures, promotion etc.

CNN being used to identify patterns, identify good squares for pieces and prioritizing diffenent moves. The model can be treated analogous to the 'intution of the game' which can be developed (in humans also) by playing a lot of games. The intution is what helps in instant filtering of playable moves, which do not worsen the position immediately, from all possible moves.

Next comes the search algorithm which is similar to 'move calculation' which human players also perform to figure out the one best move from the moves filtered on intution.

Intution is neceessary for fast response to the position and Calculation takes time but guarantees the best(or good) move which may not always be the case with intutive moves.

This project is solely based on the intution part using CNNs. Applying 'Monte-Carlo Tree Search' is one the future aspect to strengthen the engine.

<img width="1359" height="773" alt="image" src="https://github.com/user-attachments/assets/aae813e2-4640-4821-be6e-736a61e2afae" />
<img width="1355" height="786" alt="image" src="https://github.com/user-attachments/assets/8e1463fe-b4cc-43ee-b2d5-4024939a436b" />
<img width="1356" height="779" alt="image" src="https://github.com/user-attachments/assets/99232bcc-abc2-41ac-9e47-36955b94fce3" />
<img width="1359" height="779" alt="image" src="https://github.com/user-attachments/assets/717f13ff-92e0-4d6d-84d1-12fd0c3de4e6" />




**DATASET -** 
Kaggle 'Chess Games' dataset: https://www.kaggle.com/datasets/arevel/chess-games

**PLAY WITH Chess_BOT -**
1. Click the link below to open the Kaggle notebook
2. On right panel of notebook go to 'Select options' and enable 'Internet on'
3. Run all cells and play!

  PLAY Chess_BOT - https://www.kaggle.com/code/kartikeyshukla309/chess-bot-3-final-gameplay

**REFERENCES -**
1. Research paper on "Predicting Moves in Chess using Convolutional Neural Networks" by Barak Oshri and Nishith Khandwala, Stanford University.
   https://cs231n.stanford.edu/reports/2015/pdfs/ConvChess.pdf

2. Chessprogramming wiki: https://www.chessprogramming.org/Main_Page

3. FreeCodeCamp's video on AlphaZero: https://www.youtube.com/watch?v=wuSQpLinRB4

4. Others:
     https://arxiv.org/pdf/1712.01815
