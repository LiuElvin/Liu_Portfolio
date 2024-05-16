# Elvin Liu's ePortfolio

Welcome! The assortment of projects below are part of my ePortfolio for the Statistics Honors Program. As of right now, this is merely a draft with 3 completed projects. Some plans for the last 2 projects are listed at the bottom.

Ideally, the finished product will end up with 5 (or more projects), most of them applied.

# [Project 1: Ad hoc Network](https://github.com/LiuElvin/302_Final_Project)
1. Through R, randomly generates $n$ nodes for an ad hoc network according to some pre-specified node density (generally determined by the geographical information).

2. Finds the smallest $R_c$ such that the nodes are connected through paths in the network.

3. Repeats several times for each $n$.

4. Included graphical analysis of the distribution of $R_c$. Produces some plots for networks corresponding to minimum, mean, median, and maximum values of $R_c$ to verify the helper methods successfully created the sparsest path.

# [Project 2: Classify High-Dimensional Data](https://github.com/LiuElvin/class_high_dim)
- In machine learning, classification is a task that assigns a class label to examples from the problem domain. However, high dimensionality poses significant statistical challenges and renders many traditional classification algorithms impractical to use.

- In this project, I learnt some classical supervised classification techniques and discussed the curse of dimensionality. After that, I explored Penalized Discriminant Analysis (PDA), which is designed to classify high-dimensional data as an extension of the classical Linear Discriminant Analysis. It classifies data by finding the optimal lower-dimension projections that reveal “interesting structures” in the original dataset.

- Afterwards, I implemented PDA to analyze a real-life colon cancer dataset alongside a simple toy example with large dimension count but small sample size.

# [Project 3: eBay 2023 University Machine Learning Competition](https://github.com/LiuElvin/ebay_comp)
1. Built a model that can accurately extract and label the named entities in the dataset of item titles on eBay.
2. Our team `jookisthebest` placed 12th out of 887 teams.
3. The model trains a token classification model using Hugging Face's Transformers library. Here's a more in-depth summary of what the code does:
 * Hugging Face's transformers library loads a pre-trained token classification model, Facebook's roBERTa.

 * The model is trained in a training loop using PyTorch, the torch library used for neural network operations.

 * Experiment logging is performed using weights & biases with Wandb.

# Project 4: Confidence Intervals on Asymmetric Distributions
* Tentative details:
* Undergraduate research with Ranjini on Confidence Intervals

# Project 5: SPA DRP
* Tentative details:
* Another credit of SPA DRP on an applicational use of Statistics

# (Additional Tentative Plans)
* DataFest 2025
* Winter STAT 498 Special Topics Project w/ Wadsworth
* Tango Dancing Project or Survey Project w/ Prof. Emanuela Furfaro
