# Day 019 & Day 020 – KIET Admission Assistant Project & Python Inheritance

## 🚀 CRT Journey – Project Build Phase

---

# Day 019 – Project Selection

## Rajesh Adapa Sir Session

### Project Problem Statement Selected
**KIET Admission Assistant**

### Why We Selected This Project
Admission teams repeatedly answer the same questions about:

- Eligibility
- Fee structure
- Hostel details
- Required documents
- Scholarships
- Placement details
- Campus facilities
- Important dates

To solve this, we selected an AI-powered chatbot that can answer admission-related questions accurately from a prepared FAQ knowledge base.

---

# Day 020 – Project Development

## Project Name
**College Admission FAQ Chatbot**

## Industry
Education

## Difficulty
Beginner – Intermediate

## Goal
Build a chatbot that answers frequently asked admission questions using a structured FAQ knowledge base.

---

## Core Features

- Admission FAQ answering
- Eligibility details
- Fee structure information
- Hostel details
- Scholarship information
- Required documents
- Placement statistics
- Related question suggestions
- Unknown question handling

---

## Suggested Tech Stack

- Python
- Streamlit / Gradio
- Flask / HTML / CSS / JavaScript
- LLM API
- JSON Knowledge Base
- `.env` for API key security
- GitHub

---

## Team Role Split

### Member 1
Knowledge Base Creation

### Member 2
System Prompt Engineering

### Member 3
Chatbot UI Development

### Member 4
API Integration & Conversation Logic

### Member 5
Testing, Deployment & Documentation

---

## Expected Output

A working chatbot that answers only from the KIET Admission FAQ knowledge base and redirects unknown questions to the admission office.

---

# Python Session – Umar Sir

## Topic
Inheritance in Python OOP

---

## 1. Single Inheritance

```python
class carv1:
    def __init__(self):
        self.color="white"
        self.engine="v8"

    def engineOn(self):
        print("engine is in on mode")

class carv2(carv1):
    def __init__(self):
        super().__init__()
        self.bluetooth="Off"

audi=carv2()
audi.engineOn()
