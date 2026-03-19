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
<img width="1024" height="1536" alt="pipline" src="https://github.com/user-attachments/assets/9b7b085e-4969-4c2e-9d29-c28571bb3fa9" />

## Evaluation Metrics
- ROUGE
- BERTScore
- Preference Win Rate

## Environment
- Google Colab (GPU)
<img width="1536" height="1024" alt="expriement_setup7" src="https://github.com/user-attachments/assets/2c3d75f1-9124-4e4c-b20b-3ccb6d562a9d" />

## Results
The project demonstrates how different reward datasets would impact/change alignment performance.
