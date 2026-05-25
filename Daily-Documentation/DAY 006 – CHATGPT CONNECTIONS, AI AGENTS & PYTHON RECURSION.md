````md id="b9f2qt"
# CRT DAY 006 – CHATGPT CONNECTIONS, AI AGENTS & PYTHON RECURSION

## 🚀 Day 6 of 100 Days AI-Abhiyan #CRT Journey

---

# 💼 AI SESSION – TRAINER: RAJESH ADAPA

## 📌 Topics Covered
- ChatGPT Connections
- GitHub Integration
- Figma Integration
- Softr AI Workflow
- AI Agent Creation using Mistral AI

### 🔑 Key Learnings
- AI workflow automation
- Connected AI systems
- Productivity integrations
- No-code AI tools

## 🤖 AI Agent Created
### Daily Task Tacker – Mohan AI Workflow Assistant

### ✔ Features
- Daily task management
- Workflow organization
- Productivity tracking
- AI-based assistance

---

# 🐍 PYTHON SESSION – TRAINER: UMAR

## 📌 Topics Covered
- Python Recursion
- Recursive Functions
- Factorial Program
- GCD Program

---

# 📘 Sum of N Numbers using Recursion

```python
def sum(n):
  if n==1:
    return 1
  res=n+sum(n-1)
  return res

sum(5)
````

---

# 📘 Factorial Program

```python id="wff8s0"
def fact(n):
  if n == 0:
    return 1
  else:
    res = n * fact(n-1)
    return res

a=fact(5)
print("Factorial of 5 :",a)
```

---

# 📘 GCD Program – Method 1

```python id="v9jmh7"
def gcd(a, b):
    if a<=b:
      b=b%a
      if b==0:
         return a
      else:
        return gcd(b,a)
    else:
      a=a%b
      if a==0:
         return b
      else:
        return gcd(a,b)

gcd(24,36)
```

---

# 📘 GCD Program – Method 2

```python id="jlwmvc"
def GCD(a,b):
    if a<=b:
        b=b%a
        if b==0:
            return a
        else:
            res=GCD(a,b)
            return res
    else:
        a=a%b
        if a==0:
            return b
        else:
            res=GCD(a,b)
            return res

res=GCD(24,36)
print(res)
```

---

# 🎯 Key Takeaway

Modern AI systems are becoming workflow-driven and automation-focused, while recursion strengthens programming logic and problem-solving skills essential for software engineering and AI development.

```
```
