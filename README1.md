
# Chessy: An AI-Powered Chess Strategist

## Group Members
 - Ali Rahbar
 - Wilton James Miller
 - Christian Fisla
 - Daniel Rafailov

# Executive Summary
The Chess Engine Project, initiated as a computer science course endeavor, is designed to merge the realms of traditional chess strategy with advanced computational algorithms. Our mission is to construct a chess engine that not only challenges but also serves as a learning tool for both the developers and its users. The core functionality of our engine revolves around a sophisticated tree structure that maps all potential moves up to four moves ahead, evaluating each based on piece positioning and control. Additionally, our engine is uniquely empowered with access to a database containing 3.5 million historical chess games, enabling it to reference and draw insights from past successful strategies.

The project will be developed in Python, leveraging the Python Chess Library for game management and move generation. A significant milestone will be the development of APIs to integrate our model with popular chess platforms, allowing for real-time play against human opponents. In its subsequent phase, the project will explore the incorporation of a neural network to enhance decision-making processes, utilizing the vast database of games for training purposes.

Set within a tight timeframe of three weeks, our team is committed to delivering a robust, intelligent chess engine. This project not only aims to showcase the practical application of complex algorithms and machine learning in game strategy but also to inspire innovation in the intersection of computer science and traditional board games.


# Project Overview
Chessy is an AI powered chess engine desinged to play chess rapidly on platforms like chess.com. 


## Objective
To develop a chess engine that utilizes a tree structure to map out possible moves ahead (e.g., depth 4 for four moves ahead) and uses an algorithm to evaluate each move based on board positioning and piece values. The engine will leverage a database of 3.5 million games for decision-making, with future phases to include API development for playing on chess platforms and possibly integrating a neural network for decision-making.
## Goal
To learn and challenge the capabilities of tree structures, algorithms, and potentially neural networks in game strategy development.
# Scope

# Phase 1: Development of Chess Engine and Database Integration
Create a tree structure to map out possible moves ahead.
Develop an algorithm to evaluate moves and assign points.
Integrate the chess engine with a database of 3.5 million games for enhanced decision-making.
Develop APIs for the model to play on online chess platforms.

## Phase 2: Integration of Neural Network for Decision Making (Optional)
Develop a decision-making process using a neural network.
Train the neural network with the 3.5 million game database.
# Resources

## Team
Assume a small team of students with roles divided based on programming, algorithm development, database management, and testing.
Technology Stack: Python, Python Chess Library, appropriate database management system for 3.5 million games, and potential neural network frameworks (e.g., TensorFlow, PyTorch) for phase 2.
## Budget
Primarily time and effort, with potential minimal costs for cloud services or computing resources if needed.

# Timeline (3 Weeks)

## Week 1: Setup and Initial Development
Setup project environment and review Python Chess Library.
Start developing the tree structure for mapping moves.
## Week 2: Algorithm Development and Database Integration
Develop and test the evaluation algorithm.
Integrate the chess engine with the game database and implement search functionality.
## Week 3: API Development and Testing
Develop APIs for playing on chess platforms.
Conduct extensive testing and debugging.
__Optional:__ Start planning for phase 2, including research on neural networks.

# Risks and Mitigation Strategies

- Complexity of Tree Structure
May require simplification or optimization strategies to manage computational complexity.
- Database Integration Challenges
Ensure proper indexing and search algorithms to efficiently query the large game database.
- Time Constraints
Prioritize core functionalities to meet the 3-week deadline, with optional features as secondary.

# Stakeholders

- Primary Stakeholders: Course instructors and team members.
- Secondary Stakeholders: Potential users on chess platforms (for API integration).
Documentation and Reporting

# Documentation
Maintain comprehensive documentation of the development process, code, algorithms, and API usage.
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

# Progress Reporting
Weekly meetings to discuss progress, challenges, and next steps. The team will aloso write weekly reports to make sure the project is gooing as planned

# Phase 2 Considerations (Optional)

Assess the feasibility, required resources, and additional time needed to integrate a neural network for decision-making based on the outcomes of phase 1.
This project management plan provides a structured approach to developing your chess engine, emphasizing learning, algorithmic challenge, and potential scalability. As the project progresses, it's important to remain flexible and adjust the plan based on lessons learned and any unforeseen challenges.
