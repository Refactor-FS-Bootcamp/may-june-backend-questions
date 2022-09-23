# Assignment 1

### Q1. <u>Node.js JSON Cleaning Suggested:</u>

<b>Problem Statement:</b> Remove all keys that have values of N/A, -, or empty strings. If one of these values appear in an array, remove that single item from the array. Then console log the modified object as a string.

<b>Example Input</b>
<br>
{"name”: {"first":"Daniel","middle":"N/A","last":"Smith"},"age":45}

<b>Example Output</b>
<br>
{"name”: {"first":"Daniel","last":"Smith"},"age":45}
<br>
### Q2. <u>Triple Double:</u>

<b>Problem Statement:</b> Triple Double (num1, num2) take both parameters being passed, and return 1 if there is a straight triple of a number at any place in num1 and also a straight double of the same number in num2.
<br>
For example: if num1 equals 451999277 and num2 equals 41177722899, then return 1 because in the first parameter you have the straight triple 999 and you have a straight double, 99, of the same number in the second parameter. If this isn't the case, return 0.


<b>Example Input:</b>
<br>
num1 = 465555
<br>
num2 = 5579

<b>Example Output</b>
<br>
1

<b>Example Input:</b>
<br>
num1 = 67844
<br>
num2 = 66237

<b>Example Output</b>
<br>
0