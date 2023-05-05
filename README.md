Download Link: https://assignmentchef.com/product/solved-csl101-assignment-3
<br>
1 Consider an employee details are being stored through a C structure that contains the name of the employee, his/her employee ID and the salary. Write a C program that prints the employee names whose salary is less than a target salary (user input).

Q.2   Define a structure named census with the following three members:

<ol>

 <li>A character array city [ ] to store the city name</li>

 <li>An integer to store the population of the city</li>

 <li>A float member to store the literacy level Write a program to do the following:</li>

 <li>To read the details of 5 cities using an array of structures.</li>

 <li>To sort the records based on literacy level and display.</li>

</ol>

Q.3 Write a C program to create a menu driven program (using switch case) that depicts the working of a library. Create a structure called library to hold the accession number, title of the book, author name, price of the book, and flag indicating whether book is issued or not. Write the functions to:

<ol>

 <li>Add book information</li>

 <li>Display all books information</li>

 <li>List all books of given author</li>

 <li>List the count of books currently available in the library of the given title.</li>

 <li>Exit</li>

</ol>

<strong> </strong>

Note: Google might help you to understand menu driven program.

<ul>

 <li>Define a structure to store the name, an array marks [ ] which stores the marks of five different subjects and a character grade. Write a program to read and display the details of the student whose name is entered by the user.</li>

 <li>Modify Q.4 to print each student’s average marks, subject-wise class average (that includes average of all the students’ marks).</li>

 <li>Given the details of <em>n </em>employees (employee name and salary), write a C program which sorts the employee names according to the length (no of characters) of their names. If the lengths of employee names are same, then break the tie by alphabetical order. Finally, display the details of employees in the above mentioned order. You are free to use library functions under “string.h”.</li>

 <li>Define a structure that can describe a point in 2-D. A circle in 2D can be specified by its centre (a point) and radius. Define a structure that can describe a circle in 2D. Write a C function that does the following. It accepts a circle and a point as arguments. It returns 1 if the point lies inside the circle but returns 0 otherwise.</li>

</ul>

<strong> </strong>

<ul>

 <li>Construct a structure variable <em>pt </em>which represents a point in Cartesian xy-plane. Using <em>pt</em>, construct a structure variable tri which represents a triangle in the xy-plane. Write a C function which accepts a triangle as argument and returns the perimeter of the triangle. Pick the endpoints of each side and calculate, d =</li>

</ul>

√(x1 − x2)2 + (y1 − y2)2 The distance between those endpoints gives you the length of that side. When you have the lengths of all three sides, add them together to get the perimeter. Write the separate function to calculate the distance d between two co-ordinates.

<ul>

 <li>A polynomial can be represented in a structure with the following members:</li>

</ul>

<ol>

 <li>a float array to store the coefficients</li>

 <li>an integer to store the degree of the polynomial (highest power in polynomial)</li>

</ol>

<strong> </strong>

For example, a polynomial 2.3 x<sup>4</sup> – 4x + 1.6 has degree, d = 4 and coefficients are {2.3, 0, 0, -4, 1.6} to be stored in an array. The missing term’s coefficients are denoted by zero in this array. Represent this structure in C language.

<strong> </strong>

<ul>

 <li>Write a function to read and store the polynomial using structure defined above.</li>

</ul>

This function should return the polynomial read.

<ul>

 <li>Write a function to add two polynomials p and q represented in the same structure. Assume both p and q have same degree.</li>

 <li>Write a function which takes as parameters a polynomial and value of x and evaluates the polynomial using Horner’s rule: a<sub>0 </sub>x<sup>0</sup> + a<sub>1 </sub>x<sup>1</sup> + a<sub>2 </sub>x<sup>2</sup> + a<sub>3 </sub>x<sup>3</sup> + a<sub>4 </sub>x<sup>4</sup> = a<sub>0 </sub>+ x (a<sub>1 </sub>+ x (a<sub>2 </sub>+ x (a<sub>3 </sub>+ x (a<sub>4</sub>)))) and so on. The function should return the result calculated from the right hand side expression.</li>

</ul>

Q.10 Create a database of (at least 5) students using structures, where in each entry of the database will have the following fields:

<strong> </strong>

<ol>

 <li>a name, which is a string with at most 128 characters</li>

 <li>their marks in physics which is an int between 0 and 100</li>

 <li>their marks in chemistry which is an int number between 0 and 100 4. their marks in mathematics which is an int number between 0 and 100</li>

</ol>

You have to output a list of students in the following order.

<ol>

 <li>if a student ‘A’ has lower marks in physics than a student ‘B’, then A’s data is listed before B.</li>

 <li>If A and B have the same physics marks and A has lower chemistry marks than B, then A is listed before B.</li>

 <li>If A and B have the same marks in physics and chemistry, and A has lower marks in mathematics than B, then A is listed before B.</li>

 <li>If all marks are equal and A’s name precedes B’s name in the dictionary order, then A is listed before B.</li>

</ol>

<strong> </strong>

Note: You are free to use library functions under “string.h”. Maintain the separate function to sort/decide ordering.

<strong> </strong>