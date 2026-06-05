# DAY 016 – GOOGLE AI STUDIO & MERGE SORT TEST

## 📅 Date: 06-06-2026

---

# Part-A

## MARKS: 20

### 1. Which Google AI Studio feature enables real-time voice and video interactions?

A. NotebookLM
B. Live API
C. Gamma
D. Suno AI

---

### 2. What was the purpose of the AI Mock Interview Coach?

A. Email Automation
B. Resume Design
C. Interview Preparation and Feedback
D. File Management

---

### 3. Which application was created for Google Drive integration?

A. Inbox Intelligence
B. Sheet Review Analyzer
C. Automated Google Drive Assistant
D. AI Resume Builder

---

### 4. What is the primary function of the Sheet Review Sentiment Analyzer?

A. Generate Presentations
B. Analyze Reviews and Sentiments
C. Sort Data Automatically
D. Build Websites

---

### 5. Which Google service was connected with Inbox Intelligence?

A. Drive
B. Sheets
C. Gmail
D. Docs

---

### 6. What is the time complexity of Merge Sort?

A. O(n²)
B. O(log n)
C. O(n log n)
D. O(n³)

---

### 7. Merge Sort follows which algorithmic paradigm?

A. Greedy
B. Divide and Conquer
C. Dynamic Programming
D. Backtracking

---

### 8. What is the base condition in Merge Sort?

A. st > end
B. st == end
C. mid == end
D. n == 0

---

### 9. Which concept was used to count even and odd numbers?

A. Loops Only
B. Binary Search
C. Recursion
D. Sorting

---

### 10. Which statement is true about Recursion?

A. A function calls another file
B. A function calls itself
C. A loop calls itself
D. Python doesn't support recursion

---

# Part-B

## MARKS: 30

### Q11. Predict the Output

```python
l = [10, 15, 20, 25, 30]

def countEven(l, idx):
    if idx == len(l):
        return 0

    c = 0

    if l[idx] % 2 == 0:
        c = 1

    res = countEven(l, idx + 1)

    return c + res

print(countEven(l, 0))
```

A. 2
B. 3
C. 4
D. 5

---

### Q12. Predict the Output

```python
l = [10, 15, 20, 25, 30]

def countOdd(l, idx):
    if idx == len(l):
        return 0

    c = 0

    if l[idx] % 2 != 0:
        c = 1

    res = countOdd(l, idx + 1)

    return c + res

print(countOdd(l, 0))
```

A. 1
B. 2
C. 3
D. 4

---

### Q13. Predict the Output

```python
l = [2,8,1,4,9,8,2,6]
```

After Merge Sort execution, what will be the final output?

A. [9,8,8,6,4,2,2,1]

B. [1,2,2,4,6,8,8,9]

C. [2,8,1,4,9,8,2,6]

D. Error

---

### Q14. What will Recursive Binary Search return when the key is not found?

A. 0

B. False

C. -1

D. None

---

### Q15. Which application can summarize unread emails automatically?

A. AI Mock Interview Coach

B. Automated Google Drive Assistant

C. Inbox Intelligence

D. NotebookLM

---

# Programming Section

## Q16. Write a Python program to count even numbers in a list using recursion.

---

## Q17. Write a Python program to count odd numbers in a list using recursion.

---

## Q18. Write a Python program to implement Merge Sort.

---

# 🌟 Key Topics Covered

* Google AI Studio
* Live API
* Gmail AI Integration
* Google Drive Automation
* Google Sheets Sentiment Analysis
* Merge Sort
* Recursion
* Even/Odd Counting
* Problem Solving
