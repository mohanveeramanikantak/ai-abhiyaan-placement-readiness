````md
# CRT DAY 013 – NOTEBOOKLM USE CASES, AI CONTENT TOOLS & PYTHON SORTING LOGICS

## 🚀 Day 13 of 100 Days AI-Abhiyan #CRT Journey

---

# 💼 AI SESSION – TRAINER: RAJESH ADAPA

## 📌 Topics Covered
- NotebookLM Use Cases
- Song Creation using Suno and Gemini
- Presentation Creation using Gamma
- Basic Portfolio Creation from LinkedIn Profile PDF

---

## 📘 Key Learnings

### 1. NotebookLM Use Cases
- Organize learning materials
- Upload documents as knowledge sources
- Summarize important content
- Prepare faster using AI-generated insights

### 2. Song Creation using AI
- Used Suno AI and Gemini to create songs
- Learned how prompts can generate creative outputs
- Understood AI usage in content creation

### 3. Gamma for Presentations
- Created presentations using Gamma
- Learned AI-based slide generation
- Improved presentation-building workflow

### 4. Portfolio from LinkedIn Profile
- Used LinkedIn profile PDF as input
- Created a basic portfolio structure
- Learned how AI can help in personal branding

---

# 🐍 PYTHON SESSION – TRAINER: UMAR

## 📌 Topics Covered
- Bubble Sort
- Minimum Element Index
- Minimum Element using Recursion
- Linear Search using Recursion

---

## 1. Bubble Sort Program

```python
l=[5,9,4,10,3]
n=len(l)

for j in range(n-1):
    for i in range(0,n-1):
        if l[i]>l[i+1]:
            temp=l[i]
            l[i]=l[i+1]
            l[i+1]=temp

print(l)
````

---

## 2. Find Minimum Element Index

```python
l=[6,9,5,2,1,3]
n=len(l)

minn=l[0]
mIdx=0

for i in range(1,n):
    if l[i]<minn:
        minn=l[i]
        mIdx=i

print(mIdx)
```

---

## 3. Find Minimum Element using Recursion

```python
l=[6,9,4,8,3]
n=len(l)

def findMin(l,idx):
    if idx==len(l)-1:
        return l[idx]

    res=findMin(l,idx+1)

    if l[idx]<res:
        return l[idx]
    else:
        return res

a=findMin(l,0)
print(a)
```

---

## 4. Minimum Value and Index

```python
l=[5,1,9,2,10,3]

min_val=l[0]
mIdx = 0
n = len(l)

for i in range(1,n):
  if l[i] < min_val:
    min_val = l[i]
    mIdx = i

print(f"Minimum value: {min_val}, Index: {mIdx}")
```

---

## 5. Linear Search using Recursion

```python
def ls(l,key,idx):
    if idx==len(l):
        return -1

    if l[idx]==key:
        return idx

    else:
        res=ls(l,key,idx+1)
        return res

l=[7,6,0,9,8,4]

a=ls(l,4,0)

print(a)
```

---

# 🎯 Session Outcomes

## AI Session

* Learned practical use cases of NotebookLM
* Explored AI song generation
* Used Gamma for AI presentations
* Understood portfolio creation from LinkedIn data

## Python Session

* Practiced sorting logic
* Learned minimum element logic
* Practiced recursion-based list problems
* Strengthened problem-solving skills

---

# 🌟 Key Takeaway

AI tools help us create, organize, and present ideas faster, while Python logic practice builds strong problem-solving fundamentals.

Keep learning. Keep building. Keep growing. 🚀

```
```
