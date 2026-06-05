# 📘 Day-015 Test (With Answers)

## Part-A: Multiple Choice Questions

### 1. A student wants AI to explore multiple possible startup ideas before recommending the strongest one. Which prompting method supports this?

✅ **Answer: A) Tree of Thought**

---

### 2. A student wants to understand why a prompt performed well. Which prompting technique is most suitable?

✅ **Answer: A) Reverse Engineering Prompting**

---

### 3. A student uploads five semester PDFs and wants AI to answer questions only from those documents. Which tool is MOST suitable?

✅ **Answer: A) NotebookLM**

---

### 4. A student asks AI:

"Tell me the best career for me."

What is the MOST likely reason the response feels generic?

✅ **Answer: A) The student did not provide enough context**

---

### 5. A student wants AI to compare AI, Cybersecurity, and Data Science before recommending one field. Which prompting technique is MOST suitable?

✅ **Answer: B) Tree of Thought Prompting**

---

### 6. A student wants AI to ask follow-up questions before creating a personalized study plan. Which prompting method should be used?

✅ **Answer: D) Ask Me Back Prompting**

---

### 7. A student gives three examples of high-quality LinkedIn headlines before asking for a new one. Which technique is being used?

✅ **Answer: C) Few-Shot Prompting**

---

### 8. A student wants to create an original farewell song for classmates. Which AI tool is MOST suitable?

✅ **Answer: C) Suno AI**

---

### 9. A student keeps getting poor AI outputs. What is the BEST next step?

✅ **Answer: B) Prompt Debugging and Refinement**

---

### 10. A student wants AI to generate a presentation and automatically structure slides professionally. Which tool is MOST suitable?

✅ **Answer: A) Gamma**

---

### 11. A student asks:

"Explain Artificial Intelligence."

Another student asks:
"Explain Artificial Intelligence to a first-year engineering student using simple examples."

Who is more likely to get a useful response?

✅ **Answer: B) Second Student**

---

### 12. A student uploads lecture notes and wants AI to generate summaries, key points, and revision material. Which tool is MOST suitable?

✅ **Answer: B) NotebookLM**

---

### 13. A student wants to understand how a successful prompt was formed. Which prompting technique is MOST suitable?

✅ **Answer: A) Reverse Engineering Prompting**

---

### 14. A student wants to convert a research paper into a diagram showing relationships between concepts. Which tool discussed in the workshop is MOST suitable?

✅ **Answer: A) NotebookLM**

---

### 15. A student wants AI to create a revision structure:

Introduction → Key Points → Summary

What concept is being applied?

✅ **Answer: C) Output Constraint**

---

### 16. A student has uploaded lecture notes and wants AI to generate summaries, key points, and revision material from those notes. Which tool is MOST suitable?

✅ **Answer: B) NotebookLM**

---

### 17. A student asks:

"Suggest a low-investment AI startup idea for engineering students in India."

Then updates it to:

"Suggest a low-investment AI startup idea for engineering students in India with a team of 4 members and a ₹20,000 budget."

What improved?

✅ **Answer: B) Context and Specificity**

---

### 18. A student wants to create an original college anthem for an annual day celebration with AI-generated lyrics and vocals. Which tool is MOST suitable?

✅ **Answer: C) Suno AI**

---

### 19. Which statement demonstrates the strongest AI usage skills?

✅ **Answer: D) Combines context, verifies outputs, and refines prompts**

---

### 20. Which statement BEST reflects the overall learning from the workshop?

✅ **Answer: C) Better prompts, better tool selection, and verification lead to better outcomes**

---

# Part-B: Programming Answers

## Q1. Find Sum of Elements Using Recursion

```python
def recFun(l, idx):
    if idx == len(l):
        return 0
    return l[idx] + recFun(l, idx + 1)

l = [10, 20, 30, 40]
print(recFun(l, 0))
```

### Output

```text
100
```

---

## Q2. Find Frequency of an Element Using Recursion

```python
def recFun(l, idx, key):
    if idx == len(l):
        return 0

    count = 1 if l[idx] == key else 0

    return count + recFun(l, idx + 1, key)

l = [10, 20, 10, 30, 10]
print(recFun(l, 0, 10))
```

### Output

```text
3
```

---

## Q3. Find Product of All Elements Using Recursion

```python
def recFun(l, idx):
    if idx == len(l):
        return 1

    return l[idx] * recFun(l, idx + 1)

l = [2, 3, 4]
print(recFun(l, 0))
```

### Output

```text
24
```

# 📊 Score Key

* MCQ: 20 Marks
* Programming: 21 Marks
* Total: 41 Marks

**Full Score Answers Provided ✅**
