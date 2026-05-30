
---

### `day006_test.md`

```md
# DAY 006 – MCQ & PYTHON LOGIC TEST

## MCQs

1. Which platform was used to create the AI Agent?
A) Gemini
B) GitHub
C) Mistral AI
D) Docker

Answer: C

---

2. Which tool is mainly used for UI/UX design?
A) Python
B) Figma
C) Linux
D) SQL

Answer: B

---

3. ChatGPT connections help in:
A) Automation
B) Gaming
C) Hardware
D) Networking

Answer: A

---

## Python Logic

### GCD Program

```python
def gcd(a,b):
    if b==0:
        return a
    return gcd(b,a%b)

print(gcd(24,36))
