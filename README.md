AI-Powered Assignment Evaluation System using n8n + Groq Llama Models
📌 Project Overview

The AI-Powered Assignment Evaluation System is an interactive GenAI workflow automation project built using n8n, Groq-hosted Llama models, and prompt-engineered AI evaluation pipelines.

This system automates the process of evaluating student assignments in real time by analyzing responses submitted through a form and generating:

AI-based scores
strengths and weaknesses analysis
technical evaluation
final feedback
pass/fail status

The project demonstrates practical implementation of:

Generative AI workflows
LLM integration
AI-powered automation
real-time user interaction
workflow orchestration
🚀 Features
1. Real-Time AI Assignment Evaluation

 Students submit answers through an interactive form and instantly receive AI-generated evaluation results.

2.  AI-Based Scoring System

The workflow evaluates submissions based on:

Technical Understanding
Clarity
Accuracy
Completeness

and generates:

Score: X/10

✅ Strengths & Weakness Analysis

The AI identifies:

conceptual strengths
missing technical depth
clarity issues
improvement areas

✅ Final AI Feedback Generation

The system produces personalized feedback to help students improve their responses.

✅ Dynamic Pass / Needs Improvement Status

Based on evaluation score:

Pass
Needs Improvement

is automatically generated.

✅ Interactive User Experience

Instead of backend-only processing, the AI evaluation is displayed directly on the form completion screen after submission.

🧠 Problem Statement

Manual evaluation of assignments is time-consuming, repetitive, and inconsistent in large educational environments.

This project automates assignment assessment using Large Language Models (LLMs) to:

reduce manual effort
provide instant feedback
standardize evaluation
improve academic workflow efficiency

⚙️ Tech Stack
Workflow Automation
n8n
LLM / AI Model
Groq Cloud
Llama 3.1 Models
AI Techniques
Prompt Engineering
AI Evaluation Logic
Dynamic Response Generation
Frontend Interaction
n8n Interactive Form UI


🏗️ Workflow Architecture

Student Form Submission
        ↓
Data Preprocessing
        ↓
Assignment Text Extraction
        ↓
Groq Llama Model Evaluation
        ↓
AI Scoring & Feedback Generation
        ↓
Interactive Result Display

🔄 Workflow Explanation

1️⃣ Form Submission

Students submit assignment answers using the n8n form interface.

2️⃣ Data Processing

The workflow extracts and formats assignment text using the Edit Fields node.

3️⃣ AI Evaluation

The assignment is sent to the Groq-hosted Llama model through the Basic LLM Chain node.

The AI evaluates:

technical understanding
clarity
completeness
conceptual depth

4️⃣ Response Generation

The LLM generates:

score
strengths
weaknesses
feedback
status


5️⃣ Interactive Display

The generated evaluation is instantly shown to the user through the form completion screen.

🧾 Sample AI Output
AI Assignment Evaluation Result

Score: 8/10

✅ Strengths
- Good conceptual understanding
- Clear explanations

⚠ Weaknesses
- Needs more technical depth
- Missing practical examples

💬 Final Feedback
The student demonstrates good foundational understanding but should provide more detailed technical explanations.

📌 Status
Pass
📂 Repository Structure
AI-Assignment-Evaluation-System/
│
├── workflow/
│   └── ai_assignment_evaluation.json
│
├── screenshots/
│   ├── workflow.png
│   ├── evaluation_output.png
│
├── architecture/
│   └── workflow_architecture.png
│
└── README.md
