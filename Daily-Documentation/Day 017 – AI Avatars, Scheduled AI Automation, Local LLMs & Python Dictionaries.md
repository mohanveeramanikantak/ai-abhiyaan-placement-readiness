# 🚀 Day 017 – AI Avatars, Scheduled AI Automation, Local LLMs & Python Dictionaries

## 📅 Date
06-06-2026

---

# 🎯 Objective

Explore advanced AI tools for automation, avatar creation, local AI execution, and strengthen Python fundamentals using Dictionaries and Merge Sort.

---

# 💡 Rajesh Adapa Sir Session

## Topic: Emerging AI Tools & Automation

Today we explored several powerful AI tools that can improve productivity, automation, and content creation.

---

## 🔹 Tool 1: Google AI Avatar

### Activities

- Created a personal AI Avatar
- Generated avatar-based videos
- Published avatar video on LinkedIn

### Learning

- AI-powered digital identity creation
- Video generation using avatars
- Personal branding using AI

---

## 🔹 Tool 2: Gemini Import Feature

### Platform

```text
gemini.google.com/import
```

### Learning

- Import external content
- Use documents as context
- Improve AI responses using uploaded data

---

## 🔹 Tool 3: Gemini Scheduled Actions

### Created Daily Automations

#### 1. Daily AI Tools & South India Tech Events

Features:

- Latest AI tools
- LLM updates
- GenAI trends
- South India tech events

#### 2. Daily Mobile News Updates

Features:

- Smartphone launches
- Android updates
- iOS updates
- Hardware leaks

### Learning

- AI-powered task scheduling
- Automated daily research
- Personalized information delivery

---

## 🔹 Tool 4: Napkin AI

### Learning

- Convert ideas into diagrams
- Generate visual explanations
- Create flowcharts instantly

### Use Cases

- Project Architecture
- AI Workflows
- Documentation

---

## 🔹 Tool 5: Ollama

### Learning

Run AI models locally without internet.

### Advantages

- Privacy
- Offline AI
- Local LLM deployment
- Faster experimentation

### Example Models

- Llama
- Mistral
- Gemma

---

## 🔹 Tool 6: Sarvam AI

### Learning

- Indian AI ecosystem
- Multilingual AI
- Voice AI solutions
- Indian language support

---

# 📚 Key Learnings

✅ AI Avatars

✅ AI Video Creation

✅ AI Task Scheduling

✅ Local AI using Ollama

✅ Diagram Generation

✅ Indian AI Platforms

---

# 🐍 Umar Sir Session

## Topic: Python Dictionaries

---

### Program 1: Dictionary Operations

```python
marks_dict = {}

marks_dict["M1"] = 90
marks_dict["M2"] = 85
marks_dict["os"] = 80
marks_dict["python"] = 87
marks_dict["java"] = 82
marks_dict["CN"] = 91

marks_dict["CN"] = 80

del marks_dict["java"]

for subject, marks in marks_dict.items():
    print(f"{subject} : {marks}")
```

### Concepts Covered

- Dictionary Creation
- Insert
- Update
- Delete
- Traversal

---

### Program 2: Search Element in Dictionary

```python
marks_dict = {
    "java": 90,
    "M2": 85,
    "os": 80,
    "python": 87,
    "CN": 80
}

subject_name = input("Enter subject name: ")

if subject_name in marks_dict:
    print(f"{subject_name}:{marks_dict[subject_name]}")
else:
    print("Subject doesn't exist")
```

### Concepts Covered

- Searching in Dictionary
- Key Lookup
- Membership Checking

---

### Program 3: Merge Sort Revision

```python
def mergeSort(l,st,end):
    if st==end:
        return

    mid=(st+end)//2

    mergeSort(l,st,mid)
    mergeSort(l,mid+1,end)

    i=st
    j=mid+1

    l2=[]

    while i<=mid and j<=end:
        if l[i]<=l[j]:
            l2.append(l[i])
            i+=1
        else:
            l2.append(l[j])
            j+=1

    if i>mid:
        while j<=end:
            l2.append(l[j])
            j+=1

    elif j>end:
        while i<=mid:
            l2.append(l[i])
            i+=1

    for i in range(st,end+1):
        l[i]=l2.pop(0)

l=[2,8,1,4,9,8,2,6]

mergeSort(l,0,len(l)-1)

print(l)
```

### Output

```text
[1,2,2,4,6,8,8,9]
```

---

# 📝 Concepts Practiced

### AI Concepts

- AI Avatar Creation
- AI Automation
- Scheduled Actions
- Local LLMs
- AI Diagram Generation
- Indian AI Ecosystem

### Python Concepts

- Dictionaries
- CRUD Operations
- Search Operations
- Merge Sort Revision

---

# 🌟 Biggest Takeaway

AI is becoming increasingly personalized.

From AI avatars and scheduled research tasks to local AI models running offline, today's tools are helping users automate learning and productivity like never before.

At the same time, strong Python fundamentals such as Dictionaries and Sorting Algorithms remain essential for becoming a better developer.

---

# 📊 Day 17 Progress Summary

| Area | Status |
|--------|--------|
| AI Avatar Creation | ✅ |
| Gemini Scheduled Actions | ✅ |
| Napkin AI | ✅ |
| Ollama | ✅ |
| Sarvam AI | ✅ |
| Python Dictionaries | ✅ |
| Merge Sort Revision | ✅ |

---

# 🎯 Day 17 Completion Status

✅ Learned

✅ Practiced

✅ Automated

✅ Improved

**Day 17 of 100 Completed Successfully 🚀**
