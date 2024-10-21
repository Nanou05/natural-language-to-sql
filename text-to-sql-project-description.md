# Text-to-SQL Project: Natural Language to SQL Query Converter

By Naima OUBENALI


## Project Overview
In this week-long project, the objective is to develop a model that converts natural language questions into SQL queries. This task is fundamental in making databases more accessible to non-technical users and has applications in chatbots, voice assistants, and database interfaces.

## Objectives
1. Implementing a basic Text-to-SQL conversion system
2. Experimenting with different model architectures or fine-tuning strategies
3. Evaluating the model's performance on a standard dataset
4. Analyzing the strengths and weaknesses of the developed approach

## Dataset
Use the WikiSQL dataset, which contains:
- A large collection of tables
- Natural language questions about these tables
- Corresponding SQL queries

Alternative: If time permits, we may explore the Spider dataset, which is more complex and involves multiple tables.

## Project Steps

### 1. Data Exploration and Preprocessing
- Load and explore the WikiSQL dataset
- Analyze the structure of the questions, SQL queries, and tables
- Preprocess the data (tokenization, encoding, etc.)

### 2. Model Selection and Implementation
Choosing one of the following approaches:
a) Fine-tune a pre-trained language model (e.g., BERT, T5)
b) Implement a sequence-to-sequence model with attention
c) Develop a rule-based system combined with machine learning

Implementing the chosen approach, focusing on the core functionality.

### 3. Training and Initial Evaluation
- Set up the training pipeline
- Training the model on a subset of the data
- Performing initial evaluation and error analysis

### 4. Optimization and Final Evaluation
- Optimizing the model based on initial results
- Train on the full dataset (or a larger subset)
- Conduct a thorough evaluation, including:
  - Exact match accuracy
  - Execution accuracy (if possible)
  - Analysis of error types


## Additional Challenges 
- Implement a simple web interface for the Text-to-SQL system
- Explore handling more complex queries (e.g., joins, aggregations)
- Investigate techniques for making the model more interpretable
