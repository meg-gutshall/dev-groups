---
description: 10/21/20
---

# Stacks and Queues + Types of Technical Interviews

## Technical Interview Taxonomy

### Online Assessment

* Follow a link to an online assessment site and solve the assessment within a time limit
* Multiple questions
* Can be coding or multiple choice
* Each company chooses their questions
* Closed book \(means you can't go anywhere but the page you're on\)

**How to prepare:**

* Practice coding questions
* Brush up on fundamental language concepts
* Practice certifications on hiring sites
  * LinkedIn Skills Assessments
  * HackerRank Skills Certifications: [https://www.hackerrank.com/skills-verification](https://www.hackerrank.com/skills-verification)
* Check which resources you're allowed to use before you take the test

### Take Home Interview

* Given a "fill in the blank" application with a written document describing what you need to do
* A few days to complete as much as you can or have time for
* Meet with an interviewer to discuss your solution \(the actual interview\)

**How to prepare:**

* Make sure you are familiar with running the stack in the job description
  * Set up your environment before you start the take home
* Check with your recruiter or interviewer which resources you can use

### In-Person or Virtual Technical Interview

* Traditional technical question in your domain
  * "Implement/solve X"
  * "Show me how you would Z"
* Design question
  * System or architecture design
  * Object-oriented \(OO\) design
  * API design
  * Web/mobile application design
  * Devops or process design

**How to prepare:**

* Practice coding problems
* Mock interview
* Review books, videos, blogs, tech talks, etc. on design topics

### Behavioral or Soft Skills Interview

* Will you be a good fit for the company?
* Will hiring you improve the company culture?
* "Tell me about a time when..."
* "How do you handle a situation where..."
* "How do you lead/mentor/grow your teammates?"
* "What do you see your role as \[leadership position\] being?"

**How to prepare:**

* Write down an example of how you display each of the company values
* Write down an example of how you display each non-technical skill in the job description
* Practice the STAR method to talk about yourself
  * STAR \(Situation, Task, Action, Result\): [https://www.indeed.com/career-advice/interviewing/how-to-use-the-star-interview-response-technique](https://www.indeed.com/career-advice/interviewing/how-to-use-the-star-interview-response-technique)

## Stacks and Queues

### Recap: Lists

* A list is a linear, ordered collection of elements
* Stacks and queues are often built with lists

**Common Concepts**

* Stacks and queues have a more restricted set of operations than lists
* Both are represented as lists
* The implementation of the push operation is the difference\*

### Stacks

* LIFO: Last in, first out
* Push operation adds item to top
  * Mutates the stack
* Pop removes top
  * Mutates the stack
* Peek returns top
  * Does not mutate the stack

### Queues

* FIFO: First in, first out
* Push operation adds item to back
  * Mutates the queue
  * Enqueue = push
* Pop removes front
  * Mutates the queue
  * Dequeue = pop
* Peek returns front
  * Does not mutate the queue

### Priority Queues

* Priority queues are queues that do not follow FIFO
* The highest priority item is always popped or peeked
* On push, the item is inserted at its priority location\*
* Often implemented with heaps
* An example of this usage is alphabetizing
  * Sort on push or pop

### When to Use Stacks and Queues

* Graph search and tree traversal algorithms
* Traversing lists back and forth
  * Example: Days until higher temperature
* Tracking state at each iteration
  * Example: Min or max value stack
* Symmetry or matching
  * Example: Bracket matching, palindrome

## Meetup Notes



