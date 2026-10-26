# AI - ML

# 🚀 Ultimate Python, Data Engineering & GenAI Interview Portfolio

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-API-green)
![GenAI](https://img.shields.io/badge/Generative-AI-orange)
![RAG](https://img.shields.io/badge/RAG-LLM-red)
![LangChain](https://img.shields.io/badge/LangChain-AgenticAI-purple)
![Ollama](https://img.shields.io/badge/Ollama-OpenSourceLLM-black)
![FAISS](https://img.shields.io/badge/FAISS-VectorDB-yellow)
![SQL](https://img.shields.io/badge/SQL-Analytics-blue)
![Pandas](https://img.shields.io/badge/Pandas-DataAnalysis-darkblue)

### Complete Python • Data Engineering • FastAPI • RAG • LangChain • Ollama • AI Interview Preparation Repository

</div>

---

# 📖 About This Repository

This repository is a comprehensive collection of:

- Python Interview Preparation
- Data Structures & Algorithms
- Object-Oriented Programming (OOP)
- Pandas & Data Analysis
- SQL Interview Questions
- FastAPI Development
- Retrieval Augmented Generation (RAG)
- LangChain
- Ollama
- Vector Databases
- Large Language Models (LLMs)
- Agentic AI
- LLM Evaluation
- AI Solution Architecture

Designed for:

✅ Python Developers  
✅ Data Engineers  
✅ Data Scientists  
✅ AI Engineers  
✅ GenAI Engineers  
✅ Solution Architects  
✅ AI Architects  

---

# 📂 Repository Structure

```text
Ultimate-Python-GenAI-Portfolio/
│
├── notebooks/
│   ├── Ultimate_Python_GenAI_Portfolio.ipynb
│   ├── Python_GenAI_Interview_Prep.ipynb
│
├── datasets/
│
├── diagrams/
│
├── projects/
│
├── README.md
│
└── requirements.txt
```

---

# 🐍 Python Topics Covered

## Core Python

- Variables
- Data Types
- Operators
- Conditional Statements
- Loops
- Functions
- Modules
- Packages
- Exception Handling
- File Handling

---

## Advanced Python

- List Comprehensions
- Lambda Functions
- map()
- filter()
- reduce()
- Decorators
- Generators
- Iterators
- Context Managers
- Deep Copy vs Shallow Copy
- Mutable vs Immutable Objects
- *args and **kwargs
- Multithreading
- Multiprocessing
- Async Programming
- GIL

---

# 💻 Python Interview Coding Problems

## String Problems

- Reverse a String
- Palindrome Check
- Anagram Check
- Character Frequency
- Remove Duplicates
- First Non-Repeating Character
- Longest Substring Without Repeating Characters

## List Problems

- Find Duplicates
- Remove Duplicates
- Rotate Array
- Running Average
- Missing Number
- Second Largest Number
- Largest Number
- Common Elements

## Mathematical Problems

- Prime Number
- Fibonacci Series
- Factorial
- Armstrong Number
- Perfect Number
- HCF & LCM

## Search & Sort

- Linear Search
- Binary Search
- Bubble Sort
- Selection Sort
- Insertion Sort
- Merge Sort
- Quick Sort

## Advanced Problems

- Two Sum
- Sliding Window
- Top K Frequent Elements
- Group Anagrams
- Matrix Rotation
- Matrix Transpose
- Pascal Triangle
- LRU Cache

---

# 🏗️ Object-Oriented Programming

## OOP Concepts

### Encapsulation

```python
class Employee:
    def __init__(self):
        self.__salary = 50000
```

### Inheritance

```python
class Vehicle:
    pass

class Car(Vehicle):
    pass
```

### Polymorphism

```python
class Dog:
    def sound(self):
        print("bark")
```

### Abstraction

```python
from abc import ABC
```

---

# ⚡ Concurrency in Python

## Multithreading

Best For:

- API Calls
- Web Scraping
- Database Queries
- File Downloads

```python
import threading
```

---

## Multiprocessing

Best For:

- AI Models
- Data Processing
- Image Processing
- CPU Intensive Tasks

```python
from multiprocessing import Process
```

---

# 🔒 Python GIL

## What is GIL?

Global Interpreter Lock (GIL) allows only one thread to execute Python bytecode at a time.

### Suitable For

✅ I/O Bound Tasks

### Not Suitable For

❌ CPU Intensive Tasks

### Alternative

✅ Multiprocessing

---

# 📊 Pandas Data Analysis

## Covered Operations

### Reading Data

```python
pd.read_csv()
```

### Filtering

```python
df[df["salary"] > 50000]
```

### Group By

```python
df.groupby("department")
```

### Merge

```python
pd.merge(df1, df2)
```

### Pivot Tables

```python
df.pivot_table()
```

### Missing Values

```python
df.fillna(0)
```

---

# 🗄️ SQL Interview Preparation

## SQL Topics

### Joins

- Inner Join
- Left Join
- Right Join
- Full Join

### Window Functions

- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- LEAD()
- LAG()

### Aggregations

- SUM()
- COUNT()
- AVG()
- MAX()
- MIN()

### Advanced SQL

- CTE
- SubQueries
- Stored Procedures
- Indexing
- Optimization

---

# 🌐 FastAPI

## Features

✅ High Performance

✅ Async Support

✅ Swagger Documentation

✅ Pydantic Validation

✅ REST APIs

---

## CRUD Operations

### Create

```python
@app.post("/employees")
```

### Read

```python
@app.get("/employees")
```

### Update

```python
@app.put("/employees/{id}")
```

### Delete

```python
@app.delete("/employees/{id}")
```

---

# 🤖 Generative AI

## Topics Covered

- Prompt Engineering
- OpenAI
- Azure OpenAI
- Open Source LLMs
- Embeddings
- Fine Tuning
- RAG
- Agentic AI
- AI Governance

---

# 🧠 LangChain

## Components

### Prompt Templates

```python
PromptTemplate
```

### Chains

```python
LLMChain
```

### Memory

```python
ConversationBufferMemory
```

### Agents

```python
initialize_agent()
```

### Retrieval QA

```python
RetrievalQA
```

---

# 📦 Vector Databases

## FAISS

### Advantages

✅ Lightweight

✅ Fast Similarity Search

✅ Local Storage

---

## ChromaDB

### Advantages

✅ Metadata Support

✅ Persistent Storage

✅ Easy API

---

## Other Vector Databases

- Pinecone
- Weaviate
- Qdrant
- Milvus

---

# 🦙 Ollama

## Benefits

✅ Local Deployment

✅ Data Privacy

✅ Zero API Cost

✅ Offline Support

---

## Popular Models

- Llama 3
- Mistral
- Gemma
- Phi
- DeepSeek

---

## Run Locally

```bash
ollama pull llama3
ollama run llama3
```

---

# 🔍 Retrieval Augmented Generation (RAG)

## RAG Architecture

```text
User Query
     |
     ▼
Embeddings
     |
     ▼
Vector Database
     |
     ▼
Retriever
     |
     ▼
Relevant Chunks
     |
     ▼
LLM
     |
     ▼
Answer
```

---

## End-To-End Pipeline

### Step 1

Load Documents

```python
PyPDFLoader
```

### Step 2

Chunk Text

```python
RecursiveCharacterTextSplitter
```

### Step 3

Generate Embeddings

```python
OpenAIEmbeddings
```

### Step 4

Store Embeddings

```python
FAISS
```

### Step 5

Retrieve Context

```python
similarity_search()
```

### Step 6

Generate Answer

```python
RetrievalQA
```

---

# 📈 LLM Evaluation

## RAGAS Metrics

- Faithfulness
- Answer Relevancy
- Context Recall
- Context Precision

---

## DeepEval

- Correctness
- Latency
- Hallucination Score

---

## TruLens

- Groundedness
- Feedback Scores
- Evaluation Pipelines

---

# 🎯 LLM Metrics

| Metric | Description |
|----------|----------|
| Faithfulness | Is answer grounded in source? |
| Relevancy | Does answer satisfy query? |
| Context Recall | Any useful information missed? |
| Context Precision | Was irrelevant context retrieved? |
| Hallucination Rate | Fabricated information generated? |
| Latency | Response 

Ultimate Python, Data Engineering & GenAI Interview Portfolio
A complete repository for Python, Data Engineering, FastAPI, Generative AI, RAG, LangChain, Ollama, FAISS, ChromaDB, Agentic AI, and AI System Design interview preparation.

👨‍💻 About
This repository serves as a one-stop resource for:

Python Interview Preparation
Data Structures & Algorithms
Object-Oriented Programming (OOP)
Pandas & Data Analysis
SQL Interview Preparation
FastAPI Development
Generative AI
RAG (Retrieval Augmented Generation)
LangChain
Vector Databases
Ollama & Open Source LLMs
LLM Evaluation
Agentic AI
System Design
AI Solution Architecture
📚 Topics Covered
Python Fundamentals
Core Concepts
Variables
Data Types
Operators
Loops
Functions
Modules
Exception Handling
Context Managers
File Handling
Advanced Python
List Comprehensions
Lambda Functions
map()
filter()
reduce()
Generators
Iterators
Decorators
Context Managers
Deep Copy vs Shallow Copy
Mutable vs Immutable Objects
*args and **kwargs
Multithreading
Multiprocessing
Async Programming
GIL (Global Interpreter Lock)
🐍 Python Coding Interview Programs
String Problems
Reverse String
Check Palindrome
Check Anagram
First Non-Repeating Character
Character Frequency Count
Remove Duplicates from String
Longest Substring Without Repeating Characters
List Problems
Find Duplicates
Remove Duplicates
Rotate List
Reverse List
Common Elements
Missing Number
First Non-Repeating Element
Running Average
Largest Number
Second Largest Number
Mathematical Problems
Prime Number
Fibonacci Series
Factorial
Armstrong Number
Perfect Number
Leap Year
LCM & HCF
Searching
Linear Search
Binary Search
Sorting
Bubble Sort
Selection Sort
Insertion Sort
Merge Sort
Quick Sort
Advanced Interview Problems
Two Sum
Sliding Window
Top K Elements
Group Anagrams
Matrix Rotation
Matrix Transpose
Pascal Triangle
Leader Elements
Longest Consecutive Sequence
LRU Cache

