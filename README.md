# CSCN8020 - Multi-Armed Bandit Workshop

**Author:** Ali Cihan Ozdemir  
**Student ID:** 9091405  

## Overview
This repository contains the completed Jupyter Notebook for the Multi-Armed Bandit (MAB) Casino Challenge. The project explores the exploration-exploitation trade-off using Reinforcement Learning techniques. The notebook has been strictly formatted to be highly synthetic, concise, and structured with clear bullet points.

## Strategies Implemented
- **Round 1 (Stationary Casino):** Decaying ε-greedy strategy. Optimizes early exploration and guarantees late exploitation.
- **Round 2 (Non-Stationary Casino):** Constant step-size (α) and fixed ε. Tracks drifting probabilities using an Exponential Moving Average (EMA).
- **Bonus:** UCB1 (Upper Confidence Bound) algorithm implemented to balance exploration and exploitation mathematically.

## Repository Contents
- `Casino_Challenge_MAB_Workshop.ipynb`: The main finalized notebook (includes Introduction, Reflect & Discuss, Talking Points, and Conclusion).
- `submissions_round1.csv` & `submissions_round2.csv`: Generated leaderboard results for both rounds.
