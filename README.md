# computorv1
make your math tools

## description
The goal of this project is to get acquainted with handling elementary math tools that may be helpful for other 42 projects. You will not “do math for doing math”, but to develop a progressive and relaxed approach to projects where these tools are needed. 

## what to do 
Write a program that solves a polynomial second or lower degree equation. = 2차 이하의 다항식\
You will have
to show at least:
- The equation in its reduced form. = 축소된 형태? '= 0' 
- The degree of the equation.
- It’s solution(s) and the polarity of the discriminant if it makes sens.

### example
```
$>./computor "5 * X^0 + 4 * X^1 - 9.3 * X^2 = 1 * X^0"
Reduced form: 4 * X^0 + 4 * X^1 - 9.3 * X^2 = 0
Polynomial degree: 2
Discriminant is strictly positive, the two solutions are:
0.905239
-0.475131

$>./computor "5 * X^0 + 4 * X^1 = 4 * X^0"
Reduced form: 1 * X^0 + 4 * X^1 = 0
Polynomial degree: 1
The solution is:
-0.25

./computor "8 * X^0 - 6 * X^1 + 0 * X^2 - 5.6 * X^3 = 3 * X^0"
Reduced form: 5 * X^0 - 6 * X^1 + 0 * X^2 - 5.6 * X^3 = 0
Polynomial degree: 3
The polynomial degree is strictly greater than 2, I can't solve.
```

### vocabulary
polynomial 다항식
degree of polynomial 다항식의 차수
real number 실수
