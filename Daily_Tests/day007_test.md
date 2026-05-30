
---

### `day007_test.md`

```md
# DAY 007 – MCQ & PYTHON LOGIC TEST

## MCQs

1. Vague prompts produce:
A) Better output
B) Weak output
C) Fast internet
D) AI models

Answer: B

---

2. Which framework was discussed?
A) MVC
B) 4W + 1H
C) SDLC
D) OSI

Answer: B

---

3. Good prompts require:
A) Random words
B) Clear instructions
C) No context
D) Empty prompts

Answer: B

---

## Python Logic

### Fibonacci Program

```python
def fib(n):
    if n<=1:
        return n
    return fib(n-1)+fib(n-2)

print(fib(6))
