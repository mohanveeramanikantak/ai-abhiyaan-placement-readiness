# 🚀 Day 015 of 100 Days AI-Abhiyan #CRT Journey

**Date:** 05-06-2026

---

# 🎯 Objective

Explore various AI tools and understand their strengths, use cases, and real-world applications while continuing Python recursion practice.

---

# 💡 Rajesh Adapa Sir Session

## Topic: Exploring the AI Ecosystem

Today's session focused on understanding different AI platforms and identifying which tool is best suited for specific tasks.

### 🔹 AI Tools Explored

* ChatGPT
* Gemini
* Claude
* Grok
* DeepSeek
* Mistral AI
* Meta AI
* Manus
* Qwen
* Kimi
* Genspark

---

## 📚 Key Learnings

### ✅ Different AI Models Have Different Strengths

| Tool       | Best Use Cases                 |
| ---------- | ------------------------------ |
| ChatGPT    | Coding, Learning, Productivity |
| Gemini     | Research, Google Ecosystem     |
| Claude     | Long-form Analysis             |
| DeepSeek   | Programming & Logic            |
| Grok       | Real-Time Information          |
| Mistral AI | Open-Source AI                 |
| Meta AI    | Social & Productivity          |
| Manus      | AI Automation                  |
| Kimi       | Long Context Processing        |
| Qwen       | Multilingual Tasks             |
| Genspark   | AI Search & Research           |

---

### 🎯 Key Takeaways

* No single AI tool solves every problem.
* Choosing the right AI tool improves productivity.
* AI tools can accelerate learning, coding, research, and content creation.
* Staying updated with emerging AI platforms is essential.

---

# 🐍 Umar Sir Session

## Topic: Recursion Practice

### 1️⃣ Count Even Numbers Using Recursion

```python
def countEven(l,idx):
    if idx==len(l):
        return 0

    c=0

    if l[idx]%2==0:
        c+=1
        res=countEven(l,idx+1)
        return c+res
    else:
        res=countEven(l,idx+1)
        return res

l=[4,5,1,6,2,4]

a=countEven(l,0)

print(a)
```

### Output

```text
4
```

---

### 2️⃣ Count Odd Numbers Using Recursion

```python
l = [10, 15, 20, 25, 30]

def countOdd(l, idx):
    if idx == len(l):
        return 0

    c = 0

    if l[idx] % 2 != 0:
        c = 1

    res = countOdd(l, idx + 1)

    return c + res

print(countOdd(l, 0))
```

### Output

```text
2
```

---

### 3️⃣ Recursive Counting Logic Practice

```python
def countEven(l,idx):
    if idx==len(l):
        return 0

    c=0

    if l[idx]%2!=0:
        c+=14

        res=countEven(l,idx+1)

        return c+res
    else:
        res=countEven(l,idx+1)

        return res

l=[4,5,1,6,2,4]

a=countEven(l,0)

print(a)
```

### Output

```text
28
```

---

# 📝 Day 15 Test Topics

### Part A – AI Tools & Prompt Engineering

* AI Tool Selection
* NotebookLM
* Gamma
* Suno AI
* Prompt Refinement
* Reverse Engineering Prompts
* Context-Aware Prompting
* Research Workflows

### Part B – Recursion Programs

* Sum of Elements in a List
* Frequency of an Element
* Product of Elements

---

# 🌟 Biggest Takeaway

AI tools are becoming specialized.

The future is not about using one AI tool for everything.

The future is about:

✅ Knowing the right tool
✅ Asking the right prompts
✅ Applying the right workflow

At the same time, strong Python fundamentals like recursion continue to build logical thinking and problem-solving skills.

---

# 📌 Day 15 Summary

### Rajesh Sir

* Explored 10+ AI platforms
* Compared AI capabilities
* Learned tool selection strategies
* Understood AI productivity workflows

### Umar Sir

* Practiced recursion
* Counted even numbers recursively
* Counted odd numbers recursively
* Strengthened problem-solving skills

---

# 🚀 Progress Tracker

**Day:** 15 / 100

✅ AI Tools Exploration
✅ Prompt Engineering Concepts
✅ Recursion Practice
✅ Logic Building
✅ Daily Learning Consistency

**Learn → Build → Practice → Improve** 🚀
