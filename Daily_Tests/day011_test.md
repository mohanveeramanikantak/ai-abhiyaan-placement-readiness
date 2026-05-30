# DAY011_TEST.md

# Part-A

## Marks: 10

### 1. What is the primary function of Large Language Models (LLMs)?

A. Managing internet speed
B. Predicting the next likely words based on patterns in data
C. Managing databases
D. Hardware optimization

---

### 2. Which statement BEST describes Generative AI?

A. AI that stores information
B. AI capable of creating outputs like text, images, audio, and video
C. AI designed only for coding
D. AI that works without prompts

---

### 3. Why can two AI tools generate different answers for the same prompt?

A. Every AI tool is trained differently
B. Internet speed changes the answers
C. AI works only by guessing
D. Keyboards affect AI reasoning

---

### 4. Which mode is MOST suitable for getting the latest real-time information from the web?

A. Deep Research Mode
B. Image Generation Mode
C. Web Search Mode
D. Canvas Mode

---

### 5. A student wants detailed research with source references and deeper analysis. Which option is MOST suitable?

A. Image Generation Mode
B. Deep Research using Perplexity or Gemini
C. Study Mode only
D. Canvas Mode only

---

### 6. What is an AI Hallucination?

A. Perfect information
B. AI generating false or assumed information
C. AI deleting prompts automatically
D. AI shutting down unexpectedly

---

### 7. Which factor MOST improves AI output quality?

A. Providing proper context and clear instructions
B. Using only short prompts
C. Repeating the same question multiple times
D. Ignoring AI limitations

---

### 8. Which prompt BEST represents a structured prompt?

A. "Tell me something"
B. "Write about startups"
C. "Act as a startup mentor and explain 5 AI startup ideas for engineering students in bullet points."
D. "Explain AI."

---

### 9. Which of the following is an example of a constraint in prompting?

A. "Act as a teacher."
B. "Write the answer in bullet points."
C. "Explain AI."
D. "Tell me something interesting."

---

### 10. What is the MAIN purpose of Role-Based Prompting?

A. To increase internet speed
B. To give AI a specific expertise or perspective
C. To reduce prompt quality
D. To stop follow-up questions

---

# Part-B

## Marks: 33

### Q1. What is the output?

```python
a = [10, 20, 30]

print(a[-2])
```

A) 10
B) 20
C) 30
D) Error

---

### Q2. What is the output?

```python
a = [1, 2, 3]

a.append([4, 5])

print(a)
```

A) [1, 2, 3, 4, 5]
B) [1, 2, 3, [4, 5]]
C) [[1], 2, 3, [4, 5]]
D) Error

---

### Q3. What is the output?

```python
a = [1, 2, 3]

a.extend([4, 5])

print(a)
```

A) [1, 2, 3, [4, 5]]
B) [1, 2, 3, 4, 5]
C) Error
D) [4, 5]

---

### Q4. What is the output?

```python
a = [1, 2, 3]

print(a[1:3])
```

A) [1, 2]
B) [2, 3]
C) [2, 3, 4]
D) Error

---

### Q5. What is the output?

```python
a = [1, 2, 3]

print(a[::-1])
```

A) [3, 2, 1]
B) [2, 3]
C) Error
D) [1, 0, 6]

---

### Q6. What is the output?

```python
a = [1, 2, 3]

b = a

b.append(4)

print(a)
```

A) [1, 2, 3]
B) [1, 2, 3, 4]
C) [4]
D) Error

---

### Q7. What is the output?

```python
a = [1, 2, 3]

b = a.copy()

b.append(4)

print(a)
```

A) [1, 2, 3, 4]
B) [1, 2, 3]
C) [4]
D) Error

---

### Q8. What is the output?

```python
a = [[1, 2], [3, 4]]

print(a[1][1])
```

A) 1
B) 2
C) 3
D) 4

---

### Q9. What is the output?

```python
a = [1, 2, 3]

b = [1, 2, 3]

print(a is b)
```

A) True
B) False
C) Error
D) None

---

### Q10. What is the output?

```python
a = [1, 2, 3]

print(a * 2)
```

A) [1, 2, 3]
B) [2, 4, 6]
C) Error
D) [1, 2, 3, 1, 2, 3]

---

### Q11. What is the output?

```python
a = [10] * 3

print(a)
```

A) [10]
B) [3]
C) [10]
D) Error

---

### Q12. What is the output?

```python
a = [10] * 3

a[0][0] = 1

print(a)
```

A) Changes only first element
B) Changes all
C) Becomes 10 Error
D) Last row only

---

### Q13. What is the output?

```python
a = [1, 2, 3]

print(3 in a)
```

A) Error
B) []
C) None
D) 10

---

### Q14. What is the output?

```python
a = [1, 2, 3]

print(a[-5])
```

A) Error
B) []
C) [1, 2, 3]
D) None

---

### Q15. What is the output?

```python
a = [[1, 2], [3, 4]]

b = a.copy()

b[0][0] = 100

print(a)
```

A) [[100], [2], [3, 4]]
B) [[1, 2], [3, 4]]
C) Error
D) [[100], [2], [3], [4]]

---

### Q16. What is the output?

```python
a = [1, 2, 3]

print(a.append(4))
```

A) [1, 2, 3, 4]
B) 4
C) None
D) Error

---

### Q17. What is the output?

```python
a = [1, 2, 3]

b = a

a = [4, 5]

print(b)
```

A) [4, 5]
B) [1, 2, 3]
C) Error
D) None

---

### Q18. What is the output?

```python
a = [[1], [2], [3]]

b = a

b[0].append(100)

print(a)
```

A) [[100], [2], [3]]
B) [[1], [2], [3]]
C) Error
D) None

---

### Q19. What is the output?

```python
a = [1, 2, 3]

print(a[4])
```

A) [1, 2, 3]
B) []
C) Error
D) None

---

### Q20. What is the output?

```python
a = [1, 2, 3, 4, 5]

print(a[::2])
```

A) [1, 3, 5]
B) [2, 4]
C) [1, 2, 3]
D) Error

---

### Q21. What is the output?

```python
a = [1, 2, 3, 4, 5]

print(a[1::2])
```

A) [1, 3, 5]
B) [2, 4]
C) [1, 2, 3]
D) Error

---

### Q22. What is the output?

```python
a = [1, 2, 3, 4, 5]

print(a[::-2])
```

A) [1, 3, 5]
B) [5, 3, 1]
C) [2, 4]
D) Error

---

### Q23. What is the output?

```python
a = [1, 2, 3]

a.insert(10, 100)

print(a)
```

A) Error
B) [100, 1, 2, 3]
C) [1, 2, 3, 100]
D) None

---

### Q24. What is the output?

```python
a = [1, 2, 3]

a.remove(5)

print(a)
```

A) [1, 2, 3]
B) Error
C) None
D) []

---

### Q25. What is the output?

```python
a = [1, 2, 3]

print(a.pop())
```

A) 1
B) 2
C) 3
D) Error

---

### Q26. What is the output?

```python
a = [1, 2, 3]

print(bool(a))
```

A) True
B) False
C) Error
D) None

---

### Q27. What is the output?

```python
a = [1, 2, 3]

print(a == [1, 2, 3])
```

A) True
B) False
C) Error
D) None

---

### Q28. What is the output?

```python
a = [1, 2, 3]

print(a == [1, 2])
```

A) True
B) False
C) Error
D) None

---

### Q29. What is the output?

```python
a = [1, 2, 3]

b = [1, 2, 3]

print(a is b)
```

A) True
B) False
C) Error
D) None

---

### Q30. What is the output?

```python
a = [1, 2, 3]

b = a

b = b + [4]

print(a)
```

A) [1, 2, 3]
B) [1, 2, 3, 4]
C) Error
D) None

---

### Q31. What is the output?

```python
a = [1, 2, 3]

for i in a:
    print(i)
```

A) 1 2 3
B) 1 2
C) Error
D) 3 6 9

---

### Q32. What is the output?

```python
a = [1, 2, 3]

for i in range(len(a)):
    print(a[i], end=" ")
```

A) 1 2 3
B) 1 2
C) Error
D) 3 6 9

---

### Q33. What is the output?

```python
a = [1, 2, 3]

for i in a:
    print(i * 2, end=" ")
```

A) 2 4 6
B) 1 2 3
C) Error
D) 3 6 9
