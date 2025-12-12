# shodh-AI
### Loan Approval Prediction using Deep Learning & Offline Reinforcement Learning

This project builds two different decision-making systems for loan approval:

Deep Learning (DL) Model

Supervised classification

Predicts whether a loan will default

Converts predictions into an approval policy

Offline Reinforcement Learning (RL) Agent

Learns approve/deny decisions directly

Optimizes expected financial profit

Uses real loan outcomes and reward engineering

The goal is to compare these two approaches and understand how prediction-based decisions differ from profit-optimized decisions.

### Project Objectives
✔ Train a Deep Learning model to classify loan outcomes
✔ Train an RL agent (Discrete CQL) to learn an approval policy
✔ Compute and compare model performance
✔ Analyze differences in policy behavior
✔ Identify scenarios where DL & RL make different approval decisions
✔ Evaluate financial impact of decisions

### Dataset Overview

The dataset contains ~2.2 million loans, with the following distribution:

Fully Paid: 86.6%

Defaulted: 13.4%

For faster training, a sample of 1,000,000 rows was used (optionally balanced).

## The target column:

loan_status_binary
0 = Fully Paid
1 = Defaulted

## Converted into RL/DL policy label:

1 = Approve
0 = Deny
