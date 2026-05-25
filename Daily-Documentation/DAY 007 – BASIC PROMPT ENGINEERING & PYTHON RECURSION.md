````md
# CRT DAY 007 – BASIC PROMPT ENGINEERING & PYTHON RECURSION

## 🚀 Day 7 of 100 Days AI-Abhiyan #CRT Journey

---

# 💼 AI SESSION – TRAINER: RAJESH ADAPA

## 📌 Topics Covered
- Basic Prompt Engineering
- Clear vs Vague Instructions
- Common AI Interaction Mistakes
- Effective Prompt Writing
- Daily Task Reminder in ChatGPT

### 🔑 Key Learnings
- ❌ Vague Prompt = Wrong Output
- ✅ Clear Prompt = Better Output

## ❌ Common AI Mistakes
1. Vague prompts  
2. Incorrect assumptions  
3. Human-like expectations  
4. Ignoring AI limitations  
5. Single chat usage  
6. Poor prompts  

## ✔ Good Prompt Attributes
- Clear instructions
- Proper context
- Specific requirements
- Iterative improvements

## 📌 Activity Done
Created a daily reminder in ChatGPT:
🕙 Daily Task Reminder – 10:10 AM

---

# 🐍 PYTHON SESSION – TRAINER: UMAR

## 📌 Topics Covered
- Power using Recursion
- Fibonacci using Recursion
- Count Digits using Recursion
- Day 4 & Day 5 Test Paper Discussion

---

# 📘 Power Program

```python
def power(b,e):
    if e==0:
        return 1
    res=b*power(b,e-1)
    return res

a=power(2,4)
print(a)
````

---

# 📘 Fibonacci Program

```python
def fib(n):
    if n==0:
        return n
    if n==1:
        return n
    res=fib(n-1)+fib(n-2)
    return res

a=fib(6)
print(a)
```

---

# 📘 Fibonacci Series

```python
def fibonacci(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    return fibonacci(n - 1) + fibonacci(n - 2)

n = 7
for i in range(n):
    print(fibonacci(i), end=" ")
```

---

# 📘 Count Digits Program

```python
def countt(n):
    if n==0:
        return 0

    temp=n%10
    remaining=n//10

    res=countt(remaining)

    return res+1

a=countt(123)
print(a)
```

---

# 🎯 Key Takeaway

Better prompts create better AI outputs, and strong recursion practice improves logical thinking and programming fundamentals.

```
```
