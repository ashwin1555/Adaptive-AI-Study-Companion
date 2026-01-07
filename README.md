# Adaptive AI Study Companion

## Overview
Adaptive AI Study Companion is an AI-assisted learning and interview preparation system.
It uses structured prompts to generate explanations, interview questions, and summaries
based on the user's skill level.

This project focuses on controlling AI output quality using prompt design rather than
model training.

---

## Features
- Level-based explanations (Beginner / Interview-ready)
- Automatic interview question and answer generation
- Concise topic summaries
- Reusable and structured prompt templates
- Consistent and clear AI responses

---

## How It Works
The system uses predefined instruction templates (prompts) to control:
- Explanation depth
- Output structure
- Tone and clarity
- Length constraints

---

## Prompt Structure

### Explanation Prompt
```text
You are an experienced technical instructor and interview coach.

Explain the given topic based on the specified difficulty level.
Use simple language for beginners and technical depth for interview level.

Topic: {TOPIC}
Level: {Beginner / Interview}

Output:
- Explanation
- Key points
- Real-world example
