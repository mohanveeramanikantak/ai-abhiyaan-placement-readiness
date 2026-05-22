# CRT DAY 004 – RECURSION, LINKEDIN JOB STRATEGIES & LLM FUNDAMENTALS

## 🚀 Day 4 of 100 Days AI-Abhiyan #CRT Program

---

# 🐍 PYTHON SESSION – TRAINER: UMAR

## 📌 Topics Covered
- Introduction to Recursion
- Function-Based Programming
- Pattern Programs
- Problem Solving Logic
- Programming Fundamentals
- Calculator Program using Functions

### 🔑 ATS Keywords
Python Programming, Recursion, Functions in Python, Pattern Programs, Problem Solving, Coding Logic, Placement Preparation, Competitive Coding, Loop Concepts, Modular Programming

---

# 📘 1. INTRODUCTION TO RECURSION

## 🔹 What is Recursion?
Recursion is a programming technique where a function calls itself repeatedly until a stopping condition is reached.

### ✔ Key Concepts
- Base Condition
- Recursive Call
- Function Stack
- Breaking problems into smaller subproblems

### ✔ Importance in Placements
Recursion is commonly asked in:
- Coding rounds
- Technical interviews
- DSA preparation
- Competitive programming

---

# 📘 2. PYRAMID PATTERN PROGRAM

```python
n=4
for i in range(n+1):
        print(" "*(n-i),end="")
        print("*"*(i*2+1))
```

# ✔ Concepts Used
- Nested loops
- Space management
- Pattern logic
- Row and column understanding     

# 📘 3. FULL PYRAMID USING NESTED LOOPS
```python
n=4
for i in range(4):
  for j in range(n-i-1):
        print(" ",end="")
  for j in range(2*i+1):
        print("*",end="")
  print()
```
# ✔ Learning Outcome
- Loop execution flow
- Pyramid pattern understanding
- Better logical thinking

# 📘 4. CHARACTER PATTERN PROGRAMS
## Pattern 1
```python
n=5
for i in range(n):
  for j in range(n):
    if i==0 or j==0 or i==n//2 or j==n-1 :
      print("*",end=" ")
    else:
      print(" ",end=" ")
  print()
```
## Pattern 2
```python
n=5
for i in range(n):
  for j in range(n):
    if i==0 or j==0  or j==n-1 or i==n-1:
      print("*",end=" ")
    else:
      print(" ",end=" ")
  print()
```
## Pattern 3
```python
n=5
for i in range(n):
  for j in range(n):
    if (i==0 and j==n-1) or (i==n//2 and j==n-1) or (i==n-1 and j==n-1):
        continue
    if i==0 or j==0 or i==n//2 or j==n-1 or i==n-1:
      print("*",end=" ")
    else:
      print(" ",end=" ")
  print()
```
## Pattern 4
```python
n=5
for i in range(n):
  for j in range(n):
    if (i==0 and j==0) or (i==n-1 and j==0):
        print(" ",end="")
        continue
    if i==0 or j==0 or i==n-1:
        print("*",end=" ")
    else:
        print(" ",end=" ")
  print()
```
## Pattern 5
```python
n=5
for i in range(n):
  for j in range(n):
    if (i==0 and j==0) or (i==n-1 and j==0):
        print(" ",end="")
        continue
    if i==0 or j==0 or i==n-1:
        print("*",end=" ")
    else:
        print(" ",end=" ")
  print()
```
## Pattern 6
```python
n=5
for i in range(n):
  for j in range(n):
    if i==0 or j==0 or i==n//2 or i==n-1 :
      print("*",end=" ")
    else:
      print(" ",end=" ")
  print()
```
## Pattern 7
```python
n=5
for i in range(n):
  for j in range(n):
    if i==0 or j==0 or i==n//2 or i==n-1 :
      print("*",end=" ")
    else:
      print(" ",end=" ")
  print()
```
## Pattern 8
```python
n=5
for i in range(n):
  for j in range(n):
    if (i==0 and j==0) or (i==n-1 and j==0):
        print(" ",end="")
        continue
    if i==0 or j==0 or i==n-1 or(i==n//2 and j>=n//2) or(j==n-1 and i>=n//2):
        print("*",end=" ")
    else:
        print(" ",end=" ")
  print()
```
# 📘 5. FUNCTION PROGRAMS
## Sum of Numbers (Using Print)
```python
def sum():
  sum=0
  for i in range(1,11):
    sum+=i
  print(sum)

sum()
```
## Sum of Numbers (Using Return)
```python
def sum():
  sum=0
  for i in range(1,11):
    sum+=i
  return sum

print(sum())    
```
## Sum Up To N
```python
def sum_up_to(a):
  total=0
  for i in range(1,a+1):
    total+=i
  return total

a=sum_up_to(10)
print(a)
```

# 📘 6. PRIME NUMBER CHECKING PROGRAM
```python
def check_prime(n):

    if n <= 1:
        return "Not Prime"

    for i in range(2, n):

        if n % i == 0:
            return "Not Prime"

    return "Prime"

num = int(input("Enter a number: "))

result = check_prime(num)

print(result)
```

## ✔ Concepts Used
- Conditional statements
- Loop logic
- Prime number checking

# 📘 7. REVERSE A NUMBER PROGRAM
```python 
def reverse(n):
  r = 0
  while n != 0:
     t = n % 10
     r = r * 10 + t
     n = n // 10
  return r

res = reverse(1234)
print(res)
```
## ✔ Learning Outcome
- Digit extraction logic
- While loop understanding
- Mathematical operations

# 📘 8. CALCULATOR PROGRAM USING FUNCTIONS
```python 
def add(a,b):
    return a+b

def sub(a,b):
    return a-b

def mul(a,b):
    return a*b

def div(a,b):
    return a//b

a=int(input())
b=int(input())

sym=input("Enter operation:")

if sym=="+":
    res=add(a,b)
    print(res)

elif sym=="-":
    res=sub(a,b)
    print(res)

elif sym=="*":
    res=mul(a,b)
    print(res)

elif sym=="/":
    res=div(a,b)
    print(res)

else:
    print("Enter a valid symbol")

```

## ✔ Concepts Used
- Functions
- User input
- Conditional execution
- Arithmetic operations
- Modular programming

## 🎯 PYTHON SESSION OUTCOME
- Improved pattern logic understanding
- Learned recursion basics
- Practiced function-based programming
- Strengthened coding fundamentals
- Improved problem-solving approach

## 💼 LINKEDIN & AI SESSION – TRAINER: RAJESH ADAPA
### 📌 Topics Covered
- LinkedIn Easy Apply Strategy
- LinkedIn URL Techniques
- Smart Job Search Methods
- Fundamentals of LLMs
- APIs vs LLMs vs MCP
- Modern AI Systems
- 🔑 ATS Keywords

#### inkedIn Networking, Job Search Strategy, LLM Fundamentals, API Integration, MCP Architecture, AI Engineering, Generative AI, Career Development

## 📘 9. LINKEDIN EASY APPLY HACK
### 🔹 Key Insight

- Changing the LinkedIn job filter timing in the URL to seconds helps discover newly posted jobs quickly.

### ✔ Benefits
- Apply before most candidates
- Better recruiter visibility
- Increased interview opportunities

### ✔ Important Understanding

- Early applications increase the chances of profile visibility.

### 📘 10. LLM vs API vs MCP
#### 🔹 API

- An API performs a specific task and returns a result.

##### Example:

- Weather API → returns weather information.

### 🔹 LLM

- LLMs understand prompts, generate content, and perform reasoning tasks.

#### Examples:
- ChatGPT
- Claude
-  Gemini

###🔹 MCP (Model Context Protocol)

#### MCP enables AI systems to:
- Use tools
- Access memory
- Connect with external systems
- Execute workflows dynamically

###📘 11. MODERN AI PRODUCT EVOLUTION
- ✔ Discussion Topics
- Cursor AI
- Claude AI
- AI Coding Assistants
- MCP-first AI systems
- ✔ Important Understanding

#### Modern AI products are shifting:

- From API-first architecture
- Toward MCP-first intelligent systems


##🎯 LINKEDIN & AI SESSION OUTCOME
- Learned smart LinkedIn job application strategies
- Understood AI fundamentals
- Improved awareness of LLMs and MCP
- Gained professional networking knowledge
- Understood modern AI workflow systems


##📌 CRT DAY 004 TASKS
###🐍 Python Practice
- Practice recursion basics
- Solve pattern programs daily
- Build function-based mini programs
- Improve coding logic consistency

## 💼 LinkedIn Tasks
- Apply to jobs daily
- Use LinkedIn filter techniques
- Maintain job application tracker
- Build professional AI network


## 🤖 AI Learning Tasks
- Learn LLM fundamentals
- Understand APIs
- Explore MCP architecture
- Research AI product workflows

# 🚀 END OF DAY 004 – CRT PROGRESSION
## 📈 Focus Areas
- Recursion fundamentals
- Pattern programming
- Function-based coding
- LinkedIn optimization
- AI workflow understanding
- Professional networking

# 🌟 KEY TAKEAWAY

Consistency in coding, networking, and AI learning is building a strong foundation for placements, software engineering roles, and future AI Engineering opportunities.