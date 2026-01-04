Urdu GLUE: Datasets & Fine-Tuning Code

This repository contains Urdu GLUE datasets curated by us, along with training code for multilingual transformer models. It supports benchmarking mBERT and XLM-RoBERTa on core Urdu NLU tasks using standard and parameter-efficient fine-tuning approaches.

Contents
Datasets (Urdu GLUE)

We provide four Urdu GLUE benchmark datasets covering grammaticality judgment, semantic textual similarity, natural language inference, and commonsense reasoning.

U-CoLA

Task: Grammatical acceptability classification

Labels: 0 (Ungrammatical), 1 (Grammatical)

U-STS-B

Task: Semantic textual similarity

Type: Regression

Score Range: 0 – 5

U-WNLI

Task: Pronoun resolution / inference

Labels: 0 (Not entailment), 1 (Entailment)

U-XNLI

Task: Natural language inference

Labels: entailment, neutral, contradiction

Models

mBERT (Multilingual BERT)

XLM-RoBERTa

Training Code

The repository includes standard fine-tuning, LoRA, QLoRA, and ADAPT implementations for both mBERT and XLM-RoBERTa.

ADAPT (Adaptive Dynamic Template Training) is a prompt-based fine-tuning strategy for masked language models that mitigates sensitivity to template selection by treating templates as stochastic training variables and incorporating multiple candidate templates during training.

Purpose

Enable Urdu NLP benchmarking using GLUE-style tasks

Support research in low-resource and multilingual settings

Compare full fine-tuning with parameter-efficient and prompt-based methods
