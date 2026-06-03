````md
# CRT DAY 014 – AI APP BUILDING, GEMINI GEMS & PYTHON MERGE/BINARY SEARCH

## 🚀 Day 14 of 100 Days AI-Abhiyan #CRT Journey

---

# 💼 AI SESSION – TRAINER: RAJESH ADAPA

## 📌 Topics Covered
- Ask Gemini
- Opal by Google
- Anara
- Gemini Gems
- AI App Creation
- Custom AI Mentor Creation

## 🔗 Tools Explored
- Opal: https://opal.google/
- Anara: https://anara.com/
- Gemini Gems: https://gemini.google/overview/gems/

---

## 1. Opal App Created

### App Name
**RoastPrep**

### Purpose
Prepare for tough interviews with a sarcastic, challenging hiring manager.

### Learning
- Built an AI interview practice app
- Learned how AI workflows can take user input and generate output
- Understood app-building using AI tools

---

## 2. Gemini Gem Created

### Gem Name
**RAG Team Mentor**

### Purpose
A beginner-friendly RAG mentor for our 9-member team.

### Project Guided
**Local Notes RAG Chatbot**

### Tech Stack
- Python
- Streamlit
- Gemini API
- LangChain
- FAISS / ChromaDB
- GitHub
- VS Code

### Key Features
- Explains RAG step by step
- Gives code implementation
- Creates GitHub issues
- Gives daily team tasks
- Helps debug errors
- Reviews README, commits, issues, and project structure

---

# 🐍 PYTHON SESSION – TRAINER: UMAR

## 📌 Topics Covered
- Merging Two Sorted Lists
- Recursive Binary Search
- List Traversal
- Searching Logic

---

## 1. Merge Two Sorted Lists

```python
l1=[10,12,14]
l2=[1,2,5]
l3=[]

i=0
j=0

n1=len(l1)
n2=len(l2)

while i<n1 and j<n2:
    if l1[i]<=l2[j]:
        l3.append(l1[i])
        i+=1
    else:
        l3.append(l2[j])
        j+=1

if i==n1:
    while j<n2:
        l3.append(l2[j])
        j+=1
else:
    while i<n1:
        l3.append(l1[i])
        i+=1

print(l3)
````

---

## 2. Merge Sorted Lists – Clean Version

```python
l1 = [2, 5, 7, 10]
l2 = [4, 8, 12, 15]

i = 0
j = 0

n1 = len(l1)
n2 = len(l2)

l3 = []

while i < n1 and j < n2:
    if l1[i] <= l2[j]:
        l3.append(l1[i])
        i += 1
    else:
        l3.append(l2[j])
        j += 1

while i < n1:
    l3.append(l1[i])
    i += 1

while j < n2:
    l3.append(l2[j])
    j += 1

print(l3)
```

---

## 3. Recursive Binary Search

```python
def BS(l,i,j,key):
    if i>j:
        return -1

    mid=(i+j)//2

    if l[mid]==key:
        return mid
    elif l[mid]>key:
        j=mid-1
        res=BS(l,i,j,key)
        return res
    else:
        i=mid+1
        res=BS(l,i,j,key)
        return res

l=[3,4,5,7,9,13,16]

a=BS(l,0,len(l)-1,19)

print(a)
```

---

## 4. Recursive Binary Search – Clean Version

```python
def BS(l, i, j, key):
    if i > j:
        return -1

    mid = (i + j) // 2

    if l[mid] == key:
        return mid
    elif l[mid] > key:
        return BS(l, i, mid - 1, key)
    else:
        return BS(l, mid + 1, j, key)

l = [3,4,5,7,9,13,16]

print(BS(l, 0, len(l)-1, 13))
```

---

# 🎯 Session Outcomes

## AI Session

* Explored Opal, Anara, and Gemini Gems
* Created RoastPrep interview app
* Created RAG Team Mentor Gem
* Understood AI workflow-based app building

## Python Session

* Practiced merging sorted lists
* Learned recursive binary search
* Improved list traversal and searching logic

---

# 🌟 Key Takeaway

AI tools help us build useful apps and custom mentors faster, while Python logic practice builds strong problem-solving fundamentals.

Keep learning. Keep building. Keep growing. 🚀

```
```
