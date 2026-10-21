# 🃏 Blackjack: Monte Carlo Prediction in Reinforcement Learning

This project implements a Blackjack game with an interactive user interface using Python and Google Colab. It demonstrates the fundamentals of **Reinforcement Learning (RL)** and the **Monte Carlo Prediction** method using Blackjack Example 5.1 from Sutton and Barto.

## 🎮 Interactive Blackjack Game

The game provides a simple, interactive UI where players can:
- **Hit:** Draw another card.
- **Stick:** Stop drawing cards and let the dealer play.
- **New Game:** Start a new round.

The interface displays the player's cards, the dealer's visible card, hand totals, and the final game result. It also calculates rewards based on the outcome: win (+1), loss (−1), or draw (0).

## 🧠 Monte Carlo Prediction

The project simulates Blackjack episodes to estimate state values under a fixed policy. The player sticks when the hand total is 20 or 21 and hits otherwise, while the dealer hits below 17 and sticks at 17 or above.

State values are estimated by averaging the observed returns for each state. Experiments with **10,000 and 500,000 episodes** generate 3D plots to visualize and compare the estimated values, including states with and without a usable Ace.

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- IPython Widgets
- Google Colab

## 🎯 Learning Objectives

- Understand states, actions, policies, rewards, and episodes.
- Explore how Monte Carlo methods estimate state-value functions.
- Compare estimates across different numbers of simulated episodes.
- Visualize state values using 3D graphs.

This project combines an interactive card game with a practical demonstration of Monte Carlo prediction in Reinforcement Learning.
