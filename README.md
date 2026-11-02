# Bayesian Analysis of Heart Disease Risk Factors

## Overview

This project investigates the association between demographic, lifestyle, and clinical factors and heart disease using Bayesian statistical inference.

The study applies conjugate Bayesian modelling and Bayesian regression to estimate disease prevalence across patient groups and examine the relationship between multiple risk factors and heart disease.

## Research Objectives

- Estimate heart disease prevalence using Bayesian inference.
- Compare disease prevalence between smokers and non-smokers.
- Investigate evidence for differences between patient groups.
- Study multiple risk factors simultaneously using Bayesian Logistic Regression.
- Quantify uncertainty using posterior distributions and credible intervals.

## Dataset

The project uses the Heart Disease dataset containing demographic, lifestyle, and clinical indicators.

Important variables include:

- Age
- Gender
- Blood Pressure
- Cholesterol Level
- Exercise Habits
- Smoking
- Family Heart Disease
- Diabetes
- BMI
- Heart Disease Status

The target variable is Heart Disease Status (Yes/No).

Dataset source and licensing information will be documented separately.

## Methodology

### 1. Exploratory Data Analysis

- Data cleaning and preprocessing.
- Distribution analysis.
- Missing-value investigation.
- Relationship between selected risk factors and heart disease.

### 2. Beta-Binomial Bayesian Inference

- Binomial likelihood.
- Beta prior distribution.
- Analytical posterior derivation.
- Posterior mean and variance.
- 95% credible intervals.
- Posterior predictive probability.

### 3. Bayesian Hypothesis Comparison

- Comparison of smokers and non-smokers.
- Posterior probability of higher disease prevalence.
- Posterior distribution of the risk difference.
- Optional Bayes factor analysis.

### 4. Bayesian Logistic Regression

- Bernoulli likelihood.
- Logistic link function.
- Prior specification.
- Posterior estimation using MCMC.
- Posterior odds ratios.
- Credible intervals and model diagnostics.

## Technologies

- Python
- NumPy
- Pandas
- SciPy
- Matplotlib
- Seaborn
- PyMC
- ArviZ

## Repository Structure

- `data/`: Dataset and source information.
- `notebooks/`: Step-by-step statistical analysis.
- `src/`: Reusable Python implementations.
- `results/`: Visualizations and analytical results.
- `report/`: Final project report.
- `presentation/`: Project presentation.

## Team

Developed as a collaborative academic project by three students.

## Limitations

The analysis is observational and does not establish causal relationships. Conclusions depend on the dataset quality, model assumptions, and prior specifications. The dataset's provenance and possible synthetic nature will be investigated before interpreting findings.

## Status

Project in progress.
