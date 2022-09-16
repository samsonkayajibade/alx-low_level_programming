
Ebi-Tech
/
alx-low_level_programming
Public
Code
Issues
Pull requests
Actions
Projects
Security
Insights
alx-low_level_programming/0x04-more_functions_nested_loops/
Latest commit
@Ebi-Tech
Ebi-Tech
…
on Jun 21
Git stats
Files
Type
Name
Commit time
. .
0-isupper.c
3 months ago
0-isupper.c
1-isdigit.c
3 months ago
1-isdigit.c
10-print_triangle.c
3 months ago
10-print_triangle.c
100-prime_factor.c
3 months ago
100-prime_factor.c
101-print_number.c
3 months ago
101-print_number.c
2-mul.c
3 months ago
2-mul.c
3-print_numbers.c
3 months ago
3-print_numbers.c
4-print_most_numbers.c
3 months ago
4-print_most_numbers.c
5-more_numbers.c
3 months ago
5-more_numbers.c
6-print_line.c
3 months ago
6-print_line.c
7-print_diagonal.c
3 months ago
7-print_diagonal.c
8-print_square.c
3 months ago
8-print_square.c
9-fizz_buzz.c
3 months ago
9-fizz_buzz.c
README.md
3 months ago
README.md
main.h
3 months ago
main.h
README.md
isupper mandatory Write a function that checks for uppercase character.
Prototype: int _isupper(int c); Returns 1 if c is uppercase Returns 0 otherwise FYI: The standard library provides a similar function: isupper. Run man isupper to learn more.

isdigit mandatory Write a function that checks for a digit (0 through 9).
Prototype: int _isdigit(int c); Returns 1 if c is a digit Returns 0 otherwise FYI: The standard library provides a similar function: isdigit. Run man isdigit to learn more.

Collaboration is multiplication mandatory Write a function that multiplies two integers.
Prototype: int mul(int a, int b);

The numbers speak for themselves mandatory Write a function that prints the numbers, from 0 to 9, followed by a new line.
Prototype: void print_numbers(void); You can only use _putchar twice in your code

I believe in numbers and signs
Write a function that prints the numbers, from 0 to 9, followed by a new line.

Prototype: void print_most_numbers(void); Do not print 2 and 4 You can only use _putchar twice in your code

Numbers constitute the only universal language
Write a function that prints 10 times the numbers, from 0 to 14, followed by a new line.

Prototype: void more_numbers(void); You can only use _putchar three times in your code

The shortest distance between two points is a straight line
Write a function that draws a straight line in the terminal.

Prototype: void print_line(int n); You can only use _putchar function to print Where n is the number of times the character _ should be printed The line should end with a \n If n is 0 or less, the function should only print \n

I feel like I am diagonally parked in a parallel universe
Write a function that draws a diagonal line on the terminal.

Prototype: void print_diagonal(int n); You can only use _putchar function to print Where n is the number of times the character \ should be printed The diagonal should end with a \n If n is 0 or less, the function should only print a \n

You are so much sunshine in every square inch
Write a function that prints a square, followed by a new line.

Prototype: void print_square(int size); You can only use _putchar function to print Where size is the size of the square If size is 0 or less, the function should print only a new line Use the character # to print the square

Fizz-Buzz
The “Fizz-Buzz test” is an interview question designed to help filter out the 99.5% of programming job candidates who can’t seem to program their way out of a wet paper bag.

Write a program that prints the numbers from 1 to 100, followed by a new line. But for multiples of three print Fizz instead of the number and for the multiples of five print Buzz. For numbers which are multiples of both three and five print FizzBuzz.

Each number or word should be separated by a space You are allowed to use the standard library

Triangles
Write a function that prints a triangle, followed by a new line.

Prototype: void print_triangle(int size); You can only use _putchar function to print Where size is the size of the triangle If size is 0 or less, the function should print only a new line Use the character # to print the triangle

The problem of distinguishing prime numbers from composite numbers and of resolving the latter into their prime factors is known to be one of the most important and useful in arithmetic
The prime factors of 1231952 are 2, 2, 2, 2, 37 and 2081.

Write a program that finds and prints the largest prime factor of the number 612852475143, followed by a new line.

You are allowed to use the standard library Your program will be compiled with this command: gcc -Wall -pedantic -Werror -Wextra -std=gnu89 100-prime_factor.c -o 100-prime_factor -lm

Numbers have life; they're not just symbols on paper
Write a function that prints an integer.

Prototype: void print_number(int n); You can only use _putchar function to print You are not allowed to use long You are not allowed to use arrays or pointers You are not allowed to hard-code special values
