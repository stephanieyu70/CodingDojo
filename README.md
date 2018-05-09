# Tutorials

Problems

Loops
Easy difficulty: Given the number of days, calculate the amount of money a person would make if they received 5c on the first day, 10c on the second, 15c on the 3rd etc.
Testing example: Given 3 days the result would be 30c
                 Given 15 days the result would be 600c
                 
Medium difficulty: Reverse Factorial. Given number, calculate if it would be a potential resultant of a factorial calculation.
E.g. 5! -> 5 x 4 x 3 x 2 x 1 -> 120
Reverse:
120/1 -> 120/2 -> 60/3 -> 20/4 - > 5/5 -> 1 = 5!
Testing examples: Given 120 result is 5!. Given 40320 result is 8!. Given 150, result is none.

Medium difficulty: Binary Gap. Given a number, convert it to its binary format. Taking this binary work out its largest gpa between two separate 1s and result the length of that gap.
Testing examples: Given 25 (00011001) result would equal 2. Given 85 (01010101) result would be 1. Given 16 (00010000) result would be 0. Given 137 (10001001) result would be 3.

Hard difficulty: Queens. Given 1 digit and 1 character, representing the location of one queen. Output a 8x8 array of 0s, 1d where 1 is the location of the where the queen would be, making sure no queen can be attacked by any other queen.
Testing example: Based on the image if given *8,c) on the left the solution would be:
[{0,0,1,0,0,0,0,0},   
{0,0,0,0,0,1,0,0},     
{0,0,0,1,0,0,0,0},       
{0,1,0,0,0,0,0,0},      
{0,0,0,0,0,0,0,1},      
{0,0,0,0,1,0,0,0},       
{0,0,0,0,0,0,1,0},      
{1,0,0,0,0,0,0,0}]


Arrays
Easy difficulty: Given an array, reverse the order of the array.
Testing examples: Given {1,2,3} result is {3,2,1}. Given {"bread", "butter","bacan"} the result is {"bacon","butter","bread"}
