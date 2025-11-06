---
title: Final Review
comments: True
layout: post
permalink: /finalreview
description: Trimester 1 Reflection and Analysis
author: Samhita Lagisetti
---

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

