# Agentic AI for Blackjack Decision Support

---

## Team Members
- Mohamed Alhajji

## Project Idea
This project aims to develop an agentic AI system that assists users in making optimal decisions in blackjack. The system will analyze the current game state, including the player’s hand, the dealer’s visible card, and the remaining cards in the deck, and recommend the best possible action.

Unlike traditional static strategies, the system will adapt dynamically by tracking which cards have already been played. This allows it to provide more accurate and context-aware recommendations.

## Motivation
Blackjack is a game that requires decision-making under uncertainty. Many players rely on intuition or static strategy charts, which do not always reflect the actual state of the game. This often leads to suboptimal decisions.

The motivation behind this project is to build a system that can support decision-making in a dynamic environment. By adapting to changes in the deck and providing explanations for its recommendations, the system demonstrates how AI agents can improve decision quality in probabilistic scenarios.

## Problem Definition
Players often make incorrect decisions because they lack precise information about probabilities and changing conditions during gameplay. Static strategies do not account for cards that have already been played.

This project addresses the problem of making optimal decisions in a changing environment by developing a system that continuously evaluates the situation and recommends the best action.

## Field
- Artificial Intelligence  
- Data Science  
- Decision Support Systems  

## Note
This repository will be updated throughout the project with further details, implementation, and results.

---

## Upload #2 – Technical Plan

## System Overview
The system will be developed as an agentic AI that recommends optimal blackjack decisions based on the current game state and remaining deck composition.

The agent will:
- Observe the player’s hand and dealer’s visible card
- Track remaining cards in the deck
- Evaluate possible actions
- Recommend the best move

---

## Technical Approach

### 1. Core Logic
The system will be implemented in Python. It will include:
- Game logic for blackjack rules
- A deck tracking system that updates as cards are used
- A decision engine that evaluates possible actions

### 2. Simulation Engine
A Monte Carlo simulation approach will be used:
- The system will simulate many possible outcomes for each action (hit, stand, double)
- Each action will be evaluated based on expected value
- The best action will be selected based on simulation results

### 3. Strategy Baseline
A basic blackjack strategy will be used as a reference point to:
- Guide decision-making
- Compare against simulation results

---

## Tools and Frameworks
- Python
- Streamlit
- NumPy

---

## Dataset
No external dataset is required.

The system will generate its own data through:
- Simulations of blackjack games
- Dynamic deck tracking during gameplay

---

## Evaluation Plan
The system will be evaluated by:
- Comparing decisions with standard blackjack strategy
- Measuring expected value (EV) of actions
- Running multiple simulated games to test performance