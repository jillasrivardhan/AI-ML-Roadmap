🤖 AI/ML Engineering Roadmap

A structured roadmap for learning Artificial Intelligence and Machine Learning Engineering from the fundamentals to modern Generative AI, RAG, Agentic AI, LLMs, and MCP.

«This roadmap is based on the "AI Engineering Sheet" (https://www.aimlroadmap.com/learning-ai), which is designed to provide a structured and free path for learning AI engineering.»

---

🎯 Goal

The goal of this roadmap is to understand not only how to train machine learning models, but also how modern AI systems are:

- Built
- Deployed
- Served through APIs
- Integrated with LLMs
- Connected to external knowledge
- Fine-tuned
- Evaluated
- Automated using AI agents

---

🗺️ Roadmap

Mathematics
     ↓
Python
     ↓
Machine Learning
     ↓
Deep Learning
     ↓
NLP
     ↓
Transformers
     ↓
LLMs
     ↓
Generative AI
     ↓
RAG
     ↓
Agentic AI
     ↓
MCP
     ↓
AI Engineering

The website organizes the learning path into the following areas:

Area| Importance| Topics
Mathematics Foundations| Optional| 3
Python Programming| Core| 5
Streamlit| Optional| 2
FastAPI| Core| 6
Machine Learning| Core| 5
NLP| Core| 5
Deep Learning| Core| 9
MLOps| Optional| 1
Transformers| Core| 6
Generative AI| Core| 6
GenAI with RAG| Core| 7
Agentic AI| Core| 6
LLMs & Fine-tuning| Core| 7
Model Context Protocol (MCP)| Core| 3

---

📚 1. Mathematics Foundations

Mathematics is marked as optional in the roadmap, but understanding the basics makes Machine Learning much easier.

Important areas:

- Linear Algebra
- Probability
- Statistics
- Calculus
- Optimization

Important concepts

Vector

A collection of numbers used to represent data.

[2, 5, 8]

Matrix

A two-dimensional collection of numbers.

[1  2]
[3  4]

Probability

Measures how likely an event is to occur.

Statistics

Helps us understand and analyze data.

Gradient

Represents the direction in which a function changes most rapidly. Gradients are heavily used when training neural networks.

---

🐍 2. Python Programming

Python is the primary programming language used throughout modern AI/ML.

Important libraries:

Python
 ├── NumPy
 ├── Pandas
 ├── Matplotlib
 ├── Seaborn
 ├── Scikit-learn
 ├── PyTorch
 └── Transformers

You should understand:

- Variables
- Functions
- Classes
- OOP
- Lists / dictionaries / sets
- File handling
- Exceptions
- Virtual environments
- Packages
- APIs

---

🤖 3. Machine Learning

Machine Learning allows computers to learn patterns from data instead of being explicitly programmed for every rule.

Main types

Machine Learning
│
├── Supervised Learning
│   ├── Regression
│   └── Classification
│
├── Unsupervised Learning
│   ├── Clustering
│   └── Dimensionality Reduction
│
└── Reinforcement Learning

Important concepts

- Train/Test Split
- Cross Validation
- Feature Engineering
- Data Preprocessing
- Encoding
- Scaling
- Overfitting
- Underfitting
- Bias
- Variance
- Hyperparameter Tuning
- Model Evaluation
- Pipelines

Common algorithms

- Linear Regression
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
- XGBoost
- KNN
- SVM
- K-Means
- PCA

---

🧠 4. Deep Learning

Deep Learning uses neural networks with multiple layers to learn complex patterns.

Basic structure:

Input
  ↓
Input Layer
  ↓
Hidden Layers
  ↓
Output Layer

Important concepts:

- Neural Networks
- Activation Functions
- Forward Propagation
- Backpropagation
- Loss Functions
- Optimizers
- Gradient Descent
- CNNs
- RNNs
- LSTMs
- Autoencoders

Popular frameworks:

- PyTorch
- TensorFlow
- Keras

---

🗣️ 5. Natural Language Processing (NLP)

NLP focuses on enabling computers to understand and process human language.

Examples:

- Text classification
- Sentiment analysis
- Named Entity Recognition
- Machine translation
- Text summarization
- Question answering

Traditional NLP concepts include:

- Tokenization
- Stop-word removal
- Stemming
- Lemmatization
- TF-IDF
- Word embeddings

---

🔄 6. Transformers

Transformers are one of the most important architectures behind modern LLMs.

The key idea is Attention.

Instead of processing every word independently, attention allows a model to determine which parts of the input are important to other parts.

Example:

"The animal didn't cross the road because it was tired."

                     ↓

Attention helps determine what "it" refers to.

Important concepts:

- Attention
- Self-Attention
- Multi-Head Attention
- Positional Encoding
- Encoder
- Decoder
- Tokenization

---

✨ 7. Generative AI

Generative AI refers to AI systems that can generate new content.

Examples:

- Text
- Images
- Audio
- Video
- Code

Prompt
  ↓
Generative AI Model
  ↓
Generated Output

Examples of applications:

- Chatbots
- Code assistants
- Content generation
- Image generation
- Summarization
- Question answering

---

📖 8. RAG — Retrieval-Augmented Generation

RAG combines an LLM with an external knowledge source.

Instead of relying only on what the model learned during training:

User Question
      ↓
Retrieve relevant information
      ↓
Add information to prompt
      ↓
LLM
      ↓
Answer

Why RAG?

LLMs may not know your private or newly created information.

For example:

Company Documents
       ↓
Vector Database
       ↓
Retriever
       ↓
Relevant Documents
       ↓
LLM
       ↓
Answer

RAG is commonly used for:

- Company knowledge assistants
- PDF question answering
- Documentation chatbots
- Research assistants
- Customer support systems

---

🧑‍💻 9. LLMs

LLM = Large Language Model

An LLM is a neural network trained on huge amounts of text to understand and generate language.

Examples of capabilities:

- Answer questions
- Generate code
- Summarize documents
- Translate text
- Extract information
- Reason over provided context

Important concepts:

- Tokens
- Context Window
- Embeddings
- Prompting
- Inference
- Temperature
- Fine-tuning
- Quantization
- Evaluation

---

🎯 10. Fine-Tuning

Fine-tuning means taking an existing pretrained model and training it further on a specific dataset/task.

Pretrained LLM
      ↓
Domain-specific Dataset
      ↓
Fine-tuning
      ↓
Specialized Model

For example, a general language model can be adapted for:

- Medical text
- Legal documents
- Customer support
- Coding
- Company-specific terminology

Important techniques include:

- Full fine-tuning
- LoRA
- QLoRA
- PEFT

---

🤝 11. Agentic AI

Agentic AI goes beyond simply generating an answer.

An AI agent can:

Understand Goal
      ↓
Plan
      ↓
Use Tools
      ↓
Observe Results
      ↓
Reason
      ↓
Take Action
      ↓
Repeat if necessary

For example, an AI agent could:

1. Receive a user's request.
2. Search the web.
3. Read information.
4. Use a calculator.
5. Analyze the results.
6. Generate a final response.

Agent vs Chatbot

Chatbot:

Question → Answer

Agent:

Goal
 ↓
Reason
 ↓
Plan
 ↓
Use Tools
 ↓
Observe
 ↓
Reason Again
 ↓
Action

---

🔌 12. MCP — Model Context Protocol

MCP = Model Context Protocol

MCP provides a standardized way for AI models/applications to interact with external tools and data sources.

Conceptually:

             ┌── Database
             │
LLM/Agent ─── MCP ─── API
             │
             ├── Files
             │
             └── Tools

Instead of building a completely different integration for every AI application, MCP provides a common protocol for connecting models to external capabilities.

---

🚀 13. FastAPI

FastAPI is a Python framework commonly used for building APIs.

It is especially useful when turning an ML model into a service.

Example architecture:

Frontend
   ↓
FastAPI
   ↓
ML Model
   ↓
Prediction

Example:

POST /predict

Input:
{
    "age": 25,
    "salary": 50000
}

Output:
{
    "prediction": 1
}

---

🎨 14. Streamlit

Streamlit allows you to quickly create web interfaces for Python and ML applications.

Example:

Python ML Model
      ↓
   Streamlit
      ↓
Web Application

It is useful for:

- ML demos
- Data dashboards
- AI prototypes
- Model demonstrations

The roadmap marks Streamlit as optional.

---

⚙️ 15. MLOps

MLOps applies software engineering and DevOps practices to Machine Learning.

Typical workflow:

Data
 ↓
Training
 ↓
Evaluation
 ↓
Deployment
 ↓
Monitoring
 ↓
Retraining

Important concepts:

- Model versioning
- Data versioning
- CI/CD
- Model deployment
- Monitoring
- Experiment tracking
- Model registry

The roadmap lists MLOps as optional.

---

🧩 Important AI/ML Terms

AI

Artificial Intelligence is the broader field of creating systems capable of performing tasks that normally require human intelligence.

---

ML

Machine Learning is a subset of AI where models learn patterns from data.

AI
└── Machine Learning

---

Deep Learning

Deep Learning is a subset of Machine Learning based primarily on neural networks.

AI
└── ML
    └── Deep Learning

---

Model

A model is a mathematical/computational representation learned from data.

---

Feature

A feature is an input variable used by a machine learning model.

Example:

Age
Salary
Experience

---

Label / Target

The value the model is trying to predict.

Example:

Features → Age, Salary, Experience

Target → Hired / Not Hired

---

Training

Training is the process of adjusting a model's parameters using data.

---

Inference

Inference means using a trained model to generate a prediction.

Training:
Data → Model

Inference:
New Data → Trained Model → Prediction

---

Epoch

One complete pass through the training dataset during neural-network training.

---

Batch

A smaller portion of the training dataset processed at once.

---

Learning Rate

Controls how large the model's parameter updates are during optimization.

Too high:

May overshoot the optimum

Too low:

Training can become very slow

---

Loss Function

Measures how far the model's prediction is from the expected answer.

Prediction
     ↓
Loss Function
     ↓
Error

The training process attempts to minimize this loss.

---

Overfitting

The model performs very well on training data but poorly on unseen data.

Training Accuracy → High
Test Accuracy     → Low

---

Underfitting

The model is too simple to learn the important patterns.

Training Performance → Poor
Test Performance     → Poor

---

Embedding

An embedding converts information such as text into numerical vectors that capture semantic relationships.

For example:

"King" → [0.21, 0.72, -0.14, ...]

"Queen" → [0.19, 0.69, -0.11, ...]

Embeddings are heavily used in semantic search and RAG.

---

Token

A token is a unit of text processed by an LLM.

A token can be:

- A word
- Part of a word
- Punctuation
- Special characters

---

Prompt

The input/instruction given to an AI model.

Prompt → LLM → Response

---

Context Window

The amount of information an LLM can consider within a single interaction.

---

Hallucination

When an AI model produces information that sounds convincing but is incorrect or unsupported.

RAG and good evaluation techniques can help reduce this problem, although they do not guarantee its elimination.

---

🏗️ From ML Engineer to AI Engineer

A useful progression is:

Python
   ↓
NumPy + Pandas
   ↓
Data Analysis
   ↓
Machine Learning
   ↓
Scikit-learn
   ↓
Deep Learning
   ↓
PyTorch
   ↓
NLP
   ↓
Transformers
   ↓
LLMs
   ↓
Generative AI
   ↓
RAG
   ↓
AI Agents
   ↓
MCP
   ↓
Production AI Systems

---

🛠️ Suggested Project Progression

Beginner

- House Price Prediction
- Student Placement Prediction
- Customer Churn Prediction
- Breast Cancer Classification

Intermediate

- End-to-end ML pipeline
- Fraud Detection
- Recommendation System
- NLP Sentiment Analysis
- Image Classification

Advanced

- PDF RAG chatbot
- AI research assistant
- Document Q&A system
- LLM-powered application
- AI Agent with tools
- Multi-agent application
- MCP-connected AI agent

---

📌 Core Principle

Don't learn AI only by watching tutorials.

Use this cycle:

Learn
 ↓
Understand
 ↓
Implement
 ↓
Build Project
 ↓
Evaluate
 ↓
Deploy
 ↓
Improve

The ultimate goal is not simply to know ML algorithms or LLM terminology.

The goal is to be able to take:

Problem
   ↓
Data
   ↓
Model
   ↓
Evaluation
   ↓
Application
   ↓
API
   ↓
Deployment
   ↓
Monitoring

and eventually build complete production-ready AI systems.

---

🔗 Reference

AI Engineering Sheet:

https://www.aimlroadmap.com/learning-ai

The roadmap currently contains core sections for Python, FastAPI, ML, NLP, Deep Learning, Transformers, Generative AI, RAG, Agentic AI, LLMs/Fine-tuning, and MCP, with Mathematics, Streamlit, and MLOps listed as optional areas.
