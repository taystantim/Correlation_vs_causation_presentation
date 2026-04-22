# Correlation, Causation & Confusion Why Most ‘Insights’ Are Illusions
Guest Lecture | University of Lagos | April 2026

This repository contains materials from a guest lecture I delivered for the Department of Statistics at the University of Lagos.

## Overview 

This project explores common pitfalls in data analysis and how misleading insights can arise when correlation is mistaken for causation.

Through a series of examples and case studies, this project demonstrates how strong statistical relationships can appear convincing but fail to represent real-world truth.

The goal is to highlight the importance of critical thinking, data validation, and understanding how data is generated when drawing conclusions.

## Key Concepts Explored

### Anscombe’s Quartet

All four of the datasets below have the same mean, variance, correlation, and regression line. 

<img src="Images/anscombes_quartet.png" width="500">

Even when datasets share identical statistical summaries, they can have completely different underlying structures.

As shown in this example, relying only on summary statistics can hide important patterns in the data.

### Spurious Correlations

A spurious correlation occurs when two variables appear related but have no real causal connection.

<img src="Images/cheese-bedsheets.png" width="500">

- Cheese consumption vs deaths from bedsheets
- Strong correlation (~94%) but no logical relationship

This example came from a process called data dredging. Thousands of variables were compared. Some relationships will appear statistically significant purely by chance.

Sporious Correlations arise from:

- Random coincidence
- Confounding Variable

Statistical significance does not guarantee a meaningful relationship.

#### Correlation With Confounders

Observational studies found that green tea drinkers had better health outcomes.

However, this does not mean green tea causes better health.

<img src="Images/cheese-bedsheets.png" width="500">

The study found that green tea drinkers also had higher socioeconomic statuses, ate healthier diets, had more access to healthcare, exercised more, and were more health-conscious.

Lifestyle factors are confounders that influence both:

- Green tea consumption
- Health outcomes

The correlation between green tea consumption and health outcomes may reflect underlying differences between groups. From this observational study, we are not able to deduce that drinking green tea lowers the risk of heart disease and increases lifespan.

### Simpson's Paradox
When a trend within groups reverses or disappears when the data is combined

### Causal Myths in Big Data:
Common misconceptions such as “more data means more truth” and the belief that machine learning automatically uncovers causation

### Observational Data traps:
How the way data is collected can lead to misleading conclusions (e.g., selection bias, measurement bias, reverse causality)

### How Statisticians Avoid these Traps:
Approaches like careful study design, controlling for confounders, and applying skepticism to produce more reliable insights

## Key insight

Not all statistically significant patterns reflect real-world relationships.
Careful reasoning and skepticism are essential when interpreting data.

## Author 
Tayla Stanley-Timla
Statistics Graduate | Data Analyst
