## Day 2 — Lab 2A: Six-Pattern Drills

**Student Question:** Explain Big-O notation for a placement interview.

---

# Pattern 1 — PERSONA

## Prompt

You are a senior placement coach at Aditya University. You have prepared 200 B.Tech CSE students for TCS, Infosys, and Cognizant placement interviews. A 3rd-year CSE student with 7.5 CGPA asks you about Big-O notation. Explain it the way you would in a 1-on-1 prep session — concrete, conversational, exam-relevant.

## Output

Big-O notation is a way to describe how an algorithm's running time or memory usage grows as the input size increases. Interviewers ask it because they want to know whether you can evaluate algorithm efficiency, not just write code.

For example, if you search an element in an unsorted array using a loop, you may need to check every element once. If there are n elements, the time complexity is O(n). A nested loop over the same array usually results in O(n²).

In placement interviews, remember common complexities: O(1), O(log n), O(n), O(n log n), and O(n²). Always explain how many times your loops run and how that affects performance.

### Self Score

5/5

### Peer Score

9/10

---

# Pattern 2 — FEW-SHOT

## Prompt

Here are example explanations from a placement coach:

Q: What is recursion?
A: A function calling itself with a smaller problem. Like Russian dolls — open one, find a smaller one inside. Stops at base case. Example: factorial.

Q: What is a stack?
A: LIFO data structure. Push to add, pop to remove. Like a stack of plates — you take from the top.

Q: What is Big-O notation?
A:

## Output

Big-O notation measures how an algorithm's running time grows as input size increases. Think of it like estimating travel time: walking through one street is faster than checking every street in a city. For example, a single loop over n elements is O(n), while two nested loops are O(n²). It helps interviewers compare algorithms and choose the most efficient solution.

### Self Score

4/5

### Peer Score

8/10

---

# Pattern 3 — CHAIN-OF-THOUGHT

## Prompt

Explain Big-O notation to a placement interview candidate.

Step 1: Define Big-O in one sentence.

Step 2: Give one concrete example with code.

Step 3: Explain why interviewers ask about it.

Step 4: Synthesise into a 3-sentence summary.

## Output

### Step 1

Big-O notation describes how the performance of an algorithm changes as input size grows.

### Step 2

```python
for i in range(n):
    print(arr[i])
```

The loop runs n times, so the complexity is O(n).

### Step 3

Interviewers use Big-O to evaluate whether candidates understand efficiency and scalability.

### Step 4

Big-O notation measures algorithm growth as data increases. A single loop is usually O(n), while nested loops often become O(n²). Understanding Big-O helps you compare solutions and discuss optimization confidently during interviews.

### Self Score

5/5

### Peer Score

9/10

---

# Pattern 4 — STRUCTURED OUTPUT

## Prompt

Explain Big-O notation for a placement interview.

Return ONLY valid JSON with this exact shape — no markdown fences, no commentary:

{
"definition": "one-sentence definition",
"intuition": "concrete analogy",
"code_example": "Python snippet showing O(n) and O(n²)",
"common_pitfall": "what students get wrong",
"interview_test_question": "a follow-up question an interviewer might ask"
}

## Output

{
"definition": "Big-O notation describes how algorithm performance grows with input size.",
"intuition": "Searching one shelf is easier than searching every shelf in a library.",
"code_example": "for i in range(n): pass # O(n)\nfor i in range(n):\n for j in range(n): pass # O(n^2)",
"common_pitfall": "Students focus on exact execution time instead of growth rate.",
"interview_test_question": "Why is binary search O(log n)?"
}

### Self Score

5/5

### Peer Score

10/10

---

# Pattern 5 — SYSTEM PROMPT

## System Prompt

You are a senior placement coach for B.Tech CSE students at an Indian engineering college. You prepare students for TCS / Infosys / Cognizant interviews. You explain technical concepts in 50-80 words max, conversationally, with one concrete code example.

## User Prompt

Explain Big-O notation.

## Output

Big-O notation tells us how an algorithm's running time grows as input size increases. For example, a loop that scans an array once is O(n).

```python
for x in arr:
    print(x)
```

Interviewers ask Big-O to check whether you can compare solutions and choose efficient algorithms. Focus on common complexities like O(1), O(log n), and O(n).

### Self Score

4/5

### Peer Score

8/10

---

# Pattern 6 — PROMPT CHAINING

## Conversation 1 (Extract)

Prompt:
List the 5 most important sub-concepts a B.Tech student must understand about Big-O notation. Just the list, no explanation.

Output:

1. Definition of Big-O
2. Common Time Complexities
3. Comparing Algorithms
4. Time vs Space Complexity
5. Importance in Interviews

---

## Conversation 2 (Expand)

Prompt:
For each of these 5 sub-concepts of Big-O notation, write a 1-paragraph explanation tailored to a 3rd-year B.Tech CSE student preparing for placement interviews.

Output:

(Generated five detailed paragraphs covering each concept.)

---

## Conversation 3 (Polish)

Prompt:
Synthesise these 5 paragraphs into ONE concise 80-word interview-prep explanation of Big-O notation. Preserve all 5 sub-concepts. Conversational tone. End with one practice question.

Output

Big-O notation explains how an algorithm scales as input size grows. Learn common complexities like O(1), O(log n), O(n), and O(n²), and use them to compare different solutions. Understand that time complexity measures execution growth while space complexity measures memory growth. Interviewers ask Big-O because efficient problem-solving is important in software development. Practice Question: Why is binary search O(log n) while linear search is O(n)?

### Self Score

5/5

### Peer Score

10/10

---

# Summary Reflection

For my placement-prep students, the patterns I will use most are Structured Output and Prompt Chaining.

Structured Output helps generate consistent, machine-readable responses that are easy to validate, compare, and reuse in learning platforms. Prompt Chaining produces higher-quality explanations by breaking complex tasks into smaller stages (extract → expand → polish). For interview preparation, these two patterns provide the best balance of accuracy, clarity, and scalability while remaining easy for students to understand and practice.
