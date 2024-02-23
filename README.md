
# Chessy: An AI-Powered Chess Strategist

## Group Members
 - Ali Rahbar
 - Wilton
 - Christian
 - Danial

# Project Description:
Chess, with its complex strategy and vast number of possible moves, presents a significant challenge for artificial intelligence research. Our project goal is to develop Chessy, an AI that can play chess at a high level of competence, by learning from historical game data. This project aims to explore the intersection of machine learning and game theory, demonstrating how an AI can adapt to and anticipate an opponent's moves.

The foundation of Chessy's strategy is a decision tree algorithm, which will analyze over 3.5 million past chess games. This extensive dataset will allow Chessy to recognize patterns and strategies that have led to victory in a wide range of situations. By studying the outcomes of these games, Chessy aims to mimic the decision-making process of experienced chess players, from opening moves to endgame tactics.

The motivation behind Chessy is not only to create a challenging opponent for chess enthusiasts but also to advance the field of AI in understanding complex decision-making processes. This project stands at the confluence of data analysis, machine learning, and game strategy, showcasing the potential of AI to master tasks that require deep intellectual engagement and adaptability.

# Computational Plan for the Project
## Data Representation

Our project will utilize a dataset containing over 3.5 million recorded chess games, including player moves, game outcomes, and strategic annotations. This dataset will serve as the basis for training Chessy's decision-making algorithm.

## Trees and Graphs in Modeling

We will employ trees to model the decision-making process in chess, representing possible move sequences as branches. This decision tree will allow Chessy to evaluate potential moves based on historical outcomes and choose the path that maximizes its chances of winning.

## Sample Data

Each game in our dataset includes:

- Game ID
- Moves in Standard Algebraic Notation (SAN)
- Outcome (win/loss/draw)


Chessy will use machine learning algorithms to process the dataset and improve its decision tree over time. We plan to implement algorithms for data transformation/filtering/aggregation to refine the decision tree, focusing on moves and strategies that lead to success.

## Visualization and Interaction

Results of Chessy's decision-making will be displayed in real-time during games, with an interactive chessboard interface. Players will see Chessy's moves.

## Technical Requirement: Pygame

We will use pygame for developing Chessy's user interface, providing a graphical board where users can see the game unfold and make their moves. This will involve new uses of pygame beyond basic game development, such as integrating the decision tree's output to visually represent Chessy's thought process and potential moves. Pygame's capabilities for handling graphics and user input make it an ideal choice for this project component.


## List of Deliverables
- A fully functional chess AI, Chessy, capable of playing against human opponents.
- A graphical user interface for chess games against Chessy, developed with pygame.
- Documentation on the decision tree algorithm and adaptive strategy integration.
- A report on Chessy's performance, including analysis of its success against various strategies and player feedback.

## References
 - "Comprehensive Chess Dataset," https://www.kaggle.com/datasets/milesh1/35-million-chess-games/data.
