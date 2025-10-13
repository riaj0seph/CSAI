# CSAI

# Deep Reinforcement Learning for Atari Breakout

This repository contains the implementation and experimentation of **Deep Q-Network (DQN)**, **Proximal Policy Optimization (PPO)**, and **Advantage Actor-Critic (A2C)** algorithms for the **Atari Breakout** environment.  
The project is part of a research paper exploring the performance and learning dynamics of different deep RL methods on high-dimensional visual inputs.

---

## Table of Contents

- [Introduction](#introduction)
- [Setup & Requirements](#setup--requirements)
- [Results](#results)
- [License](#license)

---

## Introduction

This project focuses on training a reinforcement learning (RL) agent to achieve superhuman performance in the classic Atari game, Breakout. Using the Arcade Learning Environment (ALE) through the Gymnasium interface, we implemented and fine-tune deep RL algorithms, namely, vanilla DQN, PPO and A2C, that learn directly from pixel inputs. The research done compares the three different algorithms - Value-based, Policy-based and their hybrid to gain insight into their strengths and weaknesses. This repository contains all the code used for producing the results in the paper

---

## Setup & Requirements

### 1. Open the Colab Notebook
Open the notebook file `Breakout_RL.ipynb` in Google Colab.

### 2. Install dependencies
Run the following cell at the top of the notebook to install all required packages as stated in the requirements.txt file.

### 3. Run the notebook
After installing the packages, run the notebook cells sequentially to train and evaluate the DQN, PPO, and A2C algorithms. Tweak the parameters accordingly if you wish to produce different results.

## Results

Here are the final performances of the agents as referred to in the research paper. 
