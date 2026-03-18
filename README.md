# RLHF Language Model Alignment ProjectImplementing Reinforcement Learning with Human Feedback (RLHF) for Language Model Alignment

## Overview
This project implements a RLHF pipeline using:
- open-source models and 
- datasets

## Model
- Qwen2.5-0.5B-Instruct

## Datasets
- Anthropic HH-RLHF
- NVIDIA HelpSteer2
- Databricks Dolly-15k

## Pipeline
1. Supervised Fine-Tuning (SFT)
2. Reward Model Training
3. PPO Reinforcement Learning

## Evaluation Metrics
- ROUGE
- BERTScore
- Preference Win Rate

## Environment
- Google Colab (GPU)

## Results
The project demonstrates how different reward datasets would impact/change alignment performance.