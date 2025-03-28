# Introduction_to_computing, Practice #1
========================================

## Developer Tools

* [Visual Studio Code](https://code.visualstudio.com/)
* [Python v.3.10](https://www.python.org/downloads/release/python-3107/)
* [Git version control system](https://git-scm.com/downloads)
* [GitHub](https://github.com/login)
* [Google Authentificator](https//play.google.com/store/apps/details?id=com.google.android.apps.authentificator2) - Установите на Ваш мобильный телефон.

## Important Notes

Решите несколько задач, представленных ниже. Для решения каждой задачи используйте отдельный файл.

---

## Lab Tasks

Complete the following programming exercises with your lab instructor or on your own.

### Problem #1: Hello, World

Write a program that outputs the `hello, world` message to the screen.

#### Sample Output

```
Hello, world

```

### Problem #2: A Message in a Rectangle

Create a program that prints the `hello, world` message surrounded by asterisk symbols.

#### Sample Output

```
**************
*hello, world*
**************

```

### Problem #3: What is Your Name?

Write a program that reads a user's full name from the console, then constructs and prints a greeting message for that user.

#### Sample Input and Output

```
What is your name? John Doe
Hello, John Doe!

```

### Problem #4: Operations on Two Integer Numbers

Create a program that reads two integer numbers from the user and calculates their sum, difference, product, quotient, and remainder.

#### Sample Input and Output

```
Enter the first integer: 5
Enter the second integer: 2
5 + 2 = 7
5 - 2 = 3
5 * 2 = 10
5 / 2 = 2
5 % 2 = 1

```

### Problem #5: Operations on Two Real Numbers

Create a program that reads two real numbers from the user and computes their sum, difference, product, quotient, and remainder. Use the `fmod` function from the `cmath` header to find the remainder.

#### Sample Input and Output

```
Enter the first double: 5.1
Enter the second double: 2.6
5.1 + 2.6 = 7.7
5.1 - 2.6 = 2.5
5.1 * 2.6 = 13.26
5.1 / 2.6 = 1.96154
5.1 % 2.6 = 2.5

```

### Homework Problem #6: 

Write a program that displays the pattern mentioned in the sample below. The output format here differs from the one in the book. Your output must be precise up to the last character as demonstrated below. Do not use loops or selection constructs yet.

#### Sample Output

```
*        *********
***        *******
*****        *****
*******        ***
*********        *

```

### Homework Problem #7: Exercise 1.6

Write a program that displays the sum of the first ten odd numbers.

$1 + 3 + 5 + 7 + 9 + 11 + 13 + 15 + 17 + 19$

Note that you must create an integer variable `sum` to store the final result. You also have to instruct the computer to calculate the mathematical expression. You can't just hardcode the answer into your code. Do not use loops or selection constructs yet.

#### Sample output

```
100

```

### Homework Problem #8: Exercise 1.7

Write the code that computes the following two equations to approximate the value of $\pi$:

$\pi = \sqrt{6 \times (1 + \frac{1}{4} + \frac{1}{9} + \frac{1}{16} + \frac{1}{25})}$

$\pi = \sqrt{6 \times (1 + \frac{1}{4} + \frac{1}{9} + \frac{1}{16} + \frac{1}{25} + \frac{1}{36})}$

Try to reuse intermediate results from the first expression in the second one.

Note that you must create `double` variables `pi1` and `pi2` to store the final results. You also have to ensure the computer calculates the mathematical expressions. You can't just hardcode the answers into your code. You must use the `sqrt` function from the `cmath` header to find the square root. Do not use loops or selection constructs yet.

#### Sample Output

```
2.96339
2.99138

```

### Homework Problem #9: Exercise 1.4

Write a program that calculates the value of a variable named `p`.

Note that you must create a variable or variables to store the values of every row. Try to minimize the number of variables by reusing them. It's essential to ensure the computer calculates the values before formatting and outputting the answers to the screen. You can't just hardcode the answers into your code. You must use the `setw` manipulator from the `iomanip` header to format the output. The first column must be aligned to the left, and the other two columns must be aligned to the right using the `left` and `right` manipulators. The output format here differs from the one in the book. You must follow the output format specified below precisely. Do not use loops or selection constructs yet.

#### Sample Output

```
p       p*5     p*10
5        25       50
10       50      100
25      125      250
50      250      500

```

### Homework Problem #10: Exercise 1.11

The U.S. Census Bureau projects the population based on the following assumptions:

* One birth every 7 seconds
* One death every 13 seconds
* One new immigrant arriving every 45 seconds

Write a program to display the population for each of the next five years. Assume that the current population is 312,032,486, and that one year has 365 days.

Note that you must create variables to store intermediate or final results. You also need to ensure the computer calculates the mathematical expressions—you can't just hardcode the answers into your code. Use `double` for calculations. At the end, round the answer using the `round` function from the `cmath` header. You will need to figure out on your own how to format the output correctly. Utilizing certain manipulators such as `fixed`  and `setprecision` from `iomanip` might be one of the possible solutions. Do not use loops or selection constructs yet.

#### Sample Output

```
314812583
317592679
320372776
323152873
325932970

```

---

## Expected Repository Structure

Upon completion of all assignments, your repository should look like this:

```
. (.idea, .gitignore, CMakeLists.txt, Readme.md)
├── p01.py
├── p02.py
├── p03.py
├── p04.py
├── p05.py
├── p06.py
├── p07.py
├── p08.py
├── p09.py
└── p10.py
```

If the files with assignments are named incorrectly, you will be penalized.

---
