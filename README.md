# Spotify Premium Churn Prediction

Data Science case study focused on identifying Spotify Premium users who may cancel their subscription within the next 90 days.

## Project Overview
The project translates a business problem into a structured Data Science problem.

The objective is to identify Premium users with a high risk of cancellation so that retention strategies can be applied proactively.

Potential retention actions include:
- Personalized promotions or discounts
- Content and playlist recommendations
- Engagement notifications or emails

## Problem Definition
**Instance:** Individual Spotify Premium user

**Target:** Whether the user cancels Premium within the next 90 days

This is formulated as a supervised binary classification problem.

## Proposed Input Features
User characteristics and behavioral features include:
- Gender
- Age
- Country
- Session duration
- Skip rate
- Number of streams per week
- Repeat plays
- Weekly usage frequency
- Subscription plan type

## Proposed Modeling Approach
Logistic Regression was selected as an interpretable baseline model for binary classification.

The model converts a linear combination of user features into a cancellation probability using the sigmoid function.

Binary Cross-Entropy was considered as the loss function.

## Business Application
Predicted churn probabilities could be used to identify high-risk users and support proactive retention strategies.

## Tools & Concepts
- Data Science
- Problem Framing
- Binary Classification
- Logistic Regression
- Customer Analytics
- Churn Analysis

## Key Learning
This project strengthened my understanding of:
- translating business problems into Data Science tasks
- defining instances, features, and target variables
- selecting an appropriate machine-learning approach
- connecting model outputs to business decisions
