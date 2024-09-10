# STCA
Results and Analysis of Single-Turn Crescendo Attacks (STCA) on Large Language Models: Evaluating vulnerabilities in content moderation through adversarial techniques.

# Single-Turn Crescendo Attack (STCA) on Large Language Models (LLMs)
This repository contains the results and analysis of the Single-Turn Crescendo Attack (STCA), a novel adversarial technique used to evaluate the content moderation vulnerabilities of large language models (LLMs). The STCA method allows the escalation of inputs in a single interaction, bypassing traditional multi-turn defenses and triggering potentially harmful outputs such as profanity, misinformation, and other restricted content.

# Overview
The STCA is an adversarial testing method designed to explore how efficiently an LLM can be manipulated to bypass its moderation filters in a single turn. Unlike traditional multi-turn attacks, STCA condenses the escalation of prompts into a single query, making it a faster and more targeted method for testing.

This repository includes:

A CSV file with the test results of several LLMs, including GPT-4, LLaMA, and Gemini models.
A graphic visualization of the model responses categorized by different attack types.
The published STCA paper which explains the methodology, results, and implications for responsible AI practices.
Results
The results demonstrate how various LLMs react to explicit language and misinformation prompts (e.g., conspiracy theories). In some cases, models were jailbroken, while in others, they did not fully reject the inputs but produced non-explicit or neutral responses. This highlights gaps in content moderation.

# Test Results
The CSV file stca_results.csv contains the following columns:

# Models: The LLM being tested.
Test Prompt: The specific prompt used (e.g., explicit language, misinformation).
Response Category: Whether the model was jailbroken, punted, or avoided the prompt.
Attack Type: The type of attack used (e.g., profanity, misinformation).
You can find the full test results here.

# Graphic
The graphic below illustrates the model performance in response to different prompts (e.g., profanity vs. misinformation). It compares the rate of jailbreaks, model punts, and safe responses.

# Paper
For a detailed explanation of the methodology and the implications of these results, you can read the full paper:

STCA Paper: Single-Turn Crescendo Attack on LLMs

# Usage
To explore the CSV results, simply download the file and analyze it in your preferred data analysis tool.

bash
Copy code
git clone https://github.com/your-repo-url.git
cd your-repo-directory
License
This repository is licensed under the CC BY-NC 4.0 License, meaning it is open for non-commercial use. Please contact us for commercial use inquiries.

