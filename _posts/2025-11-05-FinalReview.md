---
title: Final Review
comments: True
layout: post
permalink: /finalreview
description: Trimester 1 Reflection and Analysis
author: Samhita Lagisetti
---


## Reflection Self-Review

# Beginning of the Year

At the start of the trimester, I was still dusting off cobwebs after taking a year off from the CSP/CSA pathway to focus on personal projects. It took me some time to adjust to Mr. Mortenson’s expectations and systems again since I had been used to working independently—either solo or with a mentor—on projects like my REHS internship benchmarking ML models and building a workflow for tracking module logs on UCSD’s Expanse supercomputer. I also worked on a personal project focused on promoting injury-free athletes.

# Growth and Collaboration

When I came into CSA, I quickly realized that success in this class depended heavily on collaboration. Unlike my previous projects, which were independent, this environment required teamwork, communication, and adaptability. Over the trimester, I’ve grown more comfortable sharing ideas, debugging with others, and contributing meaningfully to group discussions and projects.

# Next Steps for My Project

Given more time on my current project, I’d like to expand its functionality and improve the user experience. I also want to make the project more robust and scalable by refining the design and testing for edge cases.

# Future Goals in Computer Science

Next, I want to strengthen my understanding of algorithms and data structures while exploring more advanced areas like machine learning and software engineering principles. I’m especially interested in applying what I learn to create practical, data-driven solutions that make an impact.

## Practice Exam 1 MCQ

Results: 29/42
Time spent: 1:35:51

# Accuracy by Unit
![AccuracybyUnit](images/Screenshot 2025-11-06 014147.png)
Results show that I need to significantly improve in Unit 4, Data Collection. This is motivating as we haven't gone over it in class yet with team teaches, but means I need to pay extra attention when we cover it next trimester. The other 3 trimesters are high in accuracy, but Unit 1 isn't as high as I would want it considering the team teaches did review it.


# Corrections of all Problems
Q3: Creating a Painting Object
![Description](images/Screenshot 2025-11-05 132642.png)
Analysis:
The Painting constructor only accepts two parameters: an int and a String. My answer tried to pass three arguments, which doesn’t match the constructor.
Correction:
<pre>
```java
Painting p = new Painting(1939, "Frida Kahlo");
```
</pre>

Q8: Integer Division and Casting
![Description](images/Screenshot 2025-11-05 132746.png)
I misunderstood how casting affects division. I thought both expressions would give me the same result, but they don’t.
<pre>
```java
double w = 2.0;
double x = 5.0;
double y = (int) w / x;         // 0.4
double z = (int) (w / x);       // 0.0
```
</pre>

Q14: Boolean Expression Equivalence
![Description](images/Screenshot 2025-11-05 132904.png)
I messed up De Morgan’s Law. The original expression was:
<pre>
```java
!(isEven && isPositive) && isPrime

```
</pre>
The correct equivalent is:
<pre>
```java
(!isEven || !isPositive) && isPrime
```
</pre>

Q19: Random Number Range
![Description](images/Screenshot 2025-11-05 132942.png)
I thought this would generate a number between 10 and 16, but it actually gives a number between 10 and 15, inclusive.

Q29: Recursive Print Order
![Description](images/Screenshot 2025-11-05 133021.png)
I expected the output to be in the order of calls, but recursion prints in reverse. The deepest call finishes first, and then the stack unwinds.

Q35: ArrayList Traversal Behavior
![Description](images/Screenshot 2025-11-05 133051.png)
I thought the method checked for ascending order, but it was actually checking for descending. It returns true only if the list is sorted from greatest to least.

Q37: 2D Array Row Count
![Description](images/Screenshot 2025-11-05 133114.png)
I confused rows and columns. The method loops through a specific row, not a column.

Q38: Scanner File Parsing
![Description](images/Screenshot 2025-11-05 133139.png)
I tried to manually split the input, but the cleanest way was using split("_") to divide each string into two parts.

Q39: Recursive Binary Search
![Description](images/Screenshot 2025-11-05 133212.png)
I didn’t trace the recursive calls carefully. The target was found at index 2, but I expected something else.

Q40: Insertion Sort After 3 Passes
![Description](images/Screenshot 2025-11-05 133245.png)
I underestimated how much sorting happens in each pass. After three passes, the first three elements are sorted.

Q41: Scanner File Parsing
I tried to manually split the input, but the cleanest way was using split("_") to divide each string into two parts.

Q42: For Loop Equivalent to While Loop
![Description](images/Screenshot 2025-11-05 133245.png)


![Description](images/Screenshot 2025-11-05 133310.png)

Q42: For Loop Equivalent to While Loop
![Description](images/Screenshot 2025-11-05 133329.png)
I missed that the original while loop increments before adding to the sum. The correct for loop starts at 1 and goes to 6.

# Plan
1. Review and reinforce core java syntax like variable declarations. 
2. Also master insertion sort, binary search, recursion patterns.
3. Strengthening code comprehension 

## Night at the Museum Reflection
# Overview

Night at the Museum (N@tM) gave us the opportunity to present everything we’ve accomplished this trimester to teachers, parents, and visitors. My group showcased our Computer Science Portfolio Project, which organizes students’ coding work into an interactive and visually structured format. We wanted to highlight the progress we’ve made in both our technical and creative skills while demonstrating how the platform helps track and present our learning.

# Presenting to Parents and Guests

During the showcase, I described how each part of the portfolio represents different areas of computer science we’ve focused on this trimester—like frontend tools, backend logic, and data analytics. Visitors were interested in how the system tracks completion, generates certificates, and encourages consistent reflection. I also explained how building this platform helps students clearly see their growth over time and stay motivated.

Parents asked engaging questions about how this type of project could be useful for other classes or for building college portfolios. Several mentioned that they liked how it builds students’ confidence in presenting technical topics in a clear and creative way.

# Feedback and Interaction

After our presentation, I explored other groups’ projects and learned a lot from seeing how different teams approached their ideas. Some focused on AI, while others built data visualizations or tools with unique designs. Talking with them gave me ideas for improving our own project’s layout and interactivity. It was also interesting to notice how each group explained their process and design choices.

# Reflection

N@tM was a fun and motivating experience. It felt rewarding to see people take interest in our project and ask questions about how it works. I was proud of how our group collaborated and how much progress we’ve made since the start of the trimester. This event made me excited to keep building on our work and to find new ways to connect computer science with design, communication, and creativity.

# Pictures
![Description](images/Screenshot 2025-11-06 013307.png)
![Description](images/Screenshot 2025-11-06 013252.png)
![Description](images/Screenshot 2025-11-06 013241.png)

## Contributions and Achievements

# Certificate Module
![Description](images/about/Screenshot 2025-11-06 033149.png)
I worked on the frontend for our certificate system, designing and building the layout that displays verified modules like Frontend Development, Backend Development, Data Visualization, and more. I focused on creating a clean, organized interface with color-coded sections that made each certificate visually distinct and easy to navigate.


In addition to designing the interface, I also served as the integrator, making sure the frontend and backend systems communicated correctly and that all certificate data rendered as intended. 

![Description](images/about/Screenshot 2025-11-06 033646.png)

I tested features thoroughly, fixed display or data issues, and helped ensure the overall platform functioned reliably. I also provided feedback to other groups during development and testing, which helped me understand different approaches to user experience and problem-solving.

# Breakout Game
![Description](images/Screenshot 2025-11-06 031152.png)
![Description](images/Screenshot 2025-11-06 031303.png)
![Description](images/Screenshot 2025-11-06 031227.png)
![Description](images/Screenshot 2025-11-06 031323.png)

I also worked on the iteration process of our Breakout Game project. Throughout development, I implemented key features such as a score tracker, a lives system, and a game over sequence that reset the game once the player lost all lives. These additions helped make the game more interactive and complete.

Later in the trimester, when we transitioned into object-oriented programming (OOP), I revisited my code to apply class structures and better organization. I separated different parts of the game—like the paddle, ball, and bricks—into their own classes and managed their interactions through objects instead of one long procedural script. Updating the code in this way made it cleaner, more efficient, and easier to modify for future improvements.

Throughout this process, I realized how important it was to think about the audience—especially how younger students tend to be more interested in games and engaging, interactive content. That perspective made me more mindful of designing programs that aren’t just functional, but also fun and appealing to others.

Through this experience, I learned how OOP principles like encapsulation and modularity can make even small games more scalable and professional. It was satisfying to see the project evolve from a simple prototype into a well-structured program that reflected what we were learning in class.

# Team Teaches and Grading
![Description](images/about/Screenshot 2025-11-06 032404.png)
![Description](images/about/Screenshot 2025-11-06 032416.png)
Along with coding, I was able to coordinate between students and the teacher to ensure a streamlined workflow of grading, giving students responsiblity with grading, while making sure that the teacher is in the loop as well. We mapped out what games could cover which lessons to help students decide what aligned best with what they've done, giving them a better lesson to teach. Then, we created a sign up sheet as well as updated the calendar and a clear format students had to follow so they abided by our whole system framework.