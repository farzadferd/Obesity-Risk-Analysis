# Obesity Risk Factor Analysis with Bayesian Networks

## Overview

This project explores the UCI Obesity dataset using Bayesian networks to uncover probabilistic dependencies and interactions among lifestyle, demographic, and behavioral factors influencing obesity. By applying structure learning and inference techniques from the bnlearn Python package, the project highlights how probabilistic modeling can surface complex and interpretable relationships in health data.

## Objectives

Preprocess and discretize health and lifestyle data for probabilistic modeling.
Use Bayesian structure learning algorithms to uncover conditional dependencies.
Perform inference to understand how various factors affect obesity risk.
Interpret and visualize learned relationships for actionable health insights.

## Approach

1. Data Preprocessing

Cleaned and formatted the UCI Obesity dataset.
Handled missing values and encoded categorical variables.
Discretized continuous features (e.g., age, physical activity) using domain knowledge and distribution-based binning.

2. Bayesian Network Modeling

Applied structure learning algorithms:
Hill Climb Search (score-based)
Constraint-based methods (e.g., PC algorithm)
Learned conditional dependency structures to model relationships beyond pairwise correlations.

3. Inference

Used belief propagation for exact inference on the learned Bayesian network.
Queried the probability of obesity given evidence on variables like eating habits, screen time, or physical activity levels.
Identified both direct and indirect (mediated) influences on obesity.

## Key Learnings about the Data

Behavioral factors such as meal frequency, fast food consumption, screen time, and physical activity showed strong conditional dependencies with obesity levels.
Demographic variables like age and gender, while useful, had limited standalone predictive power compared to lifestyle features.

Certain behaviors (e.g., skipping meals, high-calorie food intake) formed clusters of reinforcing risk factors, often interacting with one another in subtle ways.
The dataset emphasized the importance of interactions over individual features, making it well-suited for multivariate probabilistic analysis.

## Key Learnings about the Approach

Learned to apply probabilistic graphical models to uncover interpretable structure in real-world health data.
Gained experience with structure learning, inference, and visualization using bnlearn.
Developed a stronger understanding of how to reason under uncertainty and make causal inferences based on observed evidence.
Recognized the value of interpretable machine learning in domains like healthcare, where actionable insights matter more than black-box predictions.


## Tools Used

Python

bnlearn for Bayesian networks

pandas, numpy for data preprocessing

networkx, matplotlib for visualization
