# Chessy: An AI-Powered Chess Strategist

## Group Members
 - Ali Rahbar
 - Wilton James Miller
 - Christian Fisla
 - Daniel Rafailov

# Execitive Summary

# Project Overview
Chessy is an AI powered chess engine desinged to play chess rapidly

## Objective
To develop a chess engine that utilizes a tree structure to map out possible moves ahead (e.g., depth 4 for four moves ahead) and uses an algorithm to evaluate each move based on board positioning and piece values. The engine will leverage a database of 3.5 million games for decision-making, with future phases to include API development for playing on chess platforms and possibly integrating a neural network for decision-making.

## Goal
To learn and challenge the capabilities of tree structures, algorithms, and potentially neural networks in game strategy development.

# Scope
## Phase 1: Development of Chess Engine and Database Integration
Create a tree structure to map out possible moves ahead.
Develop an algorithm to evaluate moves and assign points. The porgram will use commonly knowen algorithims such as the Minimax algortithem, the alpha-beta pruning algorithm and a Quiescence Searching algorithim. More details of this impleimentations is available in this article by the cornell university:
- https://www.cs.cornell.edu/boom/2004sp/ProjectArch/Chess/algorithms.html#board
  
Firthuremore,  we will integrate the chess engine with a database of 3.5 million games for enhanced decision-making. and next to all of these, we will develop APIs allowing our models to play on chess websites with ordinery people to test its functionality. 

## Phase 2: Integration of Neural Network for Decision Making (Optional)
Develop a decision-making process using a neural network.
Train the neural network with the 3.5 million game database.

# Resources

## Team
The team of 4 people are required for the job. Team members can poarticipate in a veriaty of tasks while also each being incharge of delivering a part of the system. Potential Roles can be: Project Manager, Algorithm Designer, API manager, AI Developer etc...

## Budget
Primarily time and effort, with potential minimal costs for cloud services or computing resources if needed.

## External resources
- Python Documentation
- ChatGPT (Used to look up algorithms and syntax help)
- Azure Cloud Servicers
- Github (File sharing and project managment)

# Timeline (3 Weeks)

## Week 1: Setup and Initial Development
- Setup project environment and review Python Chess Library.
- Start developing the tree structure for mapping moves.
- Create a basic chess playing model
## Week 2: Algorithm Development and Database Integration
- Develop and test the evaluation algorithms.
- Integrate the chess engine with the game database and implement search functionality.
- Add the graphics functionality to show the chess game
## Week 3: API Development and Testing
- Develop APIs for playing on chess platforms.
- Conduct extensive testing and debugging.
- Completing documentation
- __Optional:__ Start planning for phase 2, including research on neural networks.


# Risks and Mitigation Strategies

- Complexity of Tree Structure
May require simplification or optimization strategies to manage computational complexity.
- Complexity of Algorithms
May require simplificartion or using external resources 
- Database Integration Challenges
Ensure proper indexing and search algorithms to efficiently query the large game database.
- Time Constraints
Prioritize core functionalities to meet the 3-week deadline, with optional features as secondary.

# Documentation
Maintain comprehensive documentation of the development process, code, algorithms, and API usage.

## Comment at the begining of files
```python
"""
File Name: Name of File
Discription: Discription of Function/Method
Date Last Modified: Feb 29, 2024
"""
```
## Sample Docstring:
```python
"""
File Name: Name of File
Class/Method Name: name of method
Discription: Discription of Function/Method
Date Last Modified: Feb 29, 2024

:pram: name_of_parameter: discription of parameter
:returns: name_of_what_is_returned: discription of what it is

Developed By: name of developer
Date: Date last edited
---
Modified By: Name of Other developer
Date:  Date last edited

"""
```

## FileName.md file:
The FileName.md file is an external documentation of what the given file will be doing. Here is an example structure for the file
```
File Name: Name of the file
Programmer: Name 1, Name 2, ...

PesudoCode for file:
...

Diagrams and graphs if required
```

## test_FileName.py: 
This file includes the test cases for each file if required in the form of a pytest class. 

# Progress Reporting
Weekly meetings to discuss progress, challenges, and next steps. The team will aloso write weekly reports to make sure the project is gooing as planned

# Phase 2 Considerations (Optional)

Assess the feasibility, required resources, and additional time needed to integrate a neural network for decision-making based on the outcomes of phase 1.
This project management plan provides a structured approach to developing your chess engine, emphasizing learning, algorithmic challenge, and potential scalability. As the project progresses, it's important to remain flexible and adjust the plan based on lessons learned and any unforeseen challenges.

