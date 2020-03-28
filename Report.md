![gne](https://user-images.githubusercontent.com/59995295/77767494-2c931300-7067-11ea-9b1f-136608912a79.jpg)
# Programming for problem solving(ESC-105)
------------
Submitted by:-Roseleen kaur

Class Rollno.:-1916063

University Rollno.:-1905145

Branch:-Electrical

Batch:-2019-2023

Section:-A2


-----------
# INDEX

1. Write a code to print hello world.
2. Write a code to print big C.
3. Write a code to print the addition of two numbers.
4. Write a code to print the smallest number.
5. Write a code to print the character in a reverse way.
6. Write a code to print the area and perimeter of the rectangle.
7. Write a code to print  a factorial.
8. Write a code to print to check the timings.
9. Write a code to print farnehite to centrigrade.
10. Write a code to print the table of any number.
11. Write a code to print program of the prime numbers.
12. Write a code to print program of the swap of numbers using temporary variables.
13. Write a code to print program of area and perimeter of the circle.
14. Write a code to print program to find interest .
15. Write a code to print program to find maximum number.
16. Write a code to print program to find minimum number.
17. Write a code to print program to find a power of number.
18. Write a code to print program to find square of number.
19. Write a code to print program to find the swap of number without using temporary variables.
20. Write a code to print program to use arithmetic operators.
21. Write a code to print program to use assignment operators.
22. Write a code to print program to use operator precedence.
23. Write a code to print program to find average.
24. Write a code to print program for addition of 2*2 matrices.
25. Write a code to print program to take 5 values from the user and store them in an array and print the elements.
26. write a code to print program the number is even or odd using if-else loop . 
27. write a code to print program for sum of first natural numbers using for loop.
28. write a code to print Fizzbuzz of a integer.
29. write a code to print  Program of FizzBuzz in a continues loop.
30. Write a computer program in C, to print nth term, and sum up to nth term for series.
31. Write a computer program in C, which take integer input from user. If entered value > 10, it will call a function, which prints multiplication table of of entered number, from 1 to 10.
32. write a code to print program of game of life.
33. Write a C Program to Check Whether a Number is Positive or Negative .
34.  write a C Program to Display Characters from A to Z Using Loop.




-------------
# Program no. :- 1
Write a code to print hello world
### Input of the program
```c
#include<stdio.h>
int main()
{
printf("hello world")
return 0;
}
```
Output of the program
```c
hello world
```
------
# Program no.:-2
 Write a code to print big C.

### Input of the program
```c
#include<stdio.h>
int main()
{
puts(" ######");
puts("## ##");
puts("#");
puts("#");
puts("#");
puts("#");
puts("#");
puts("## ##");
puts(" ######");
}
```
-----------
# Program no.:-3
Write a code to print the addition of two numbers.
### Input of the program
```c
#include <stdio.h>
int main()
{
int x, y, z;
printf("Enter two numbers to add\n");
scanf("%d%d", &x, &y);
z = x + y;
printf("Sum of two numbers:%d",z);
return 0;
}
```
### output of the program
enter any two numbers: 2 4
sum of two numbers:6
--------
# Program no.:-4
Write a code to print the smallest number.
### Input of the program
```c
#include<stdio.h>
int main(void)
{
int a[10], Size, i, Smallest, Position;
printf("\nPlease Enter the size of an array \n");
scanf("%d",&Size);
printf("\nPlease Enter %d elements of an array: \n", Size);
for(i=0; i<Size; i++)
{
scanf("%d",&a[i]);
}
Smallest = a[0];
for(i=1; i<Size; i++)
{
if(Smallest > a[i])
{
Smallest = a[i];
Position = i;
}
}
printf("\nSmallest element in an Array = %d", Smallest);
printf("\nIndex position of the Smallest element = %d", Position);
return 0;
```
-------
# Program no.:-5
Write a code to print the character in a reverse way.
### Input of the program
```c
#include<stdio.h>
int main(void)
{
char char1 = 'X';
char char2 = 'M';
char char3 = 'L';
printf("The reverse of %c%c%c is %c%c%c\n",
char1, char2, char3,
char3, char2, char1);
return(0);
}
```
----------
# Program no.:-6
Write a code to print the area and perimeter of the rectangle.
### Input of the program
```C
#include<stdio.h>
int main()
{
float h,b,A,P;
printf("\nEnter Height: ");
scanf("%f",&h);
printf("\nEnter Bredth: ");
scanf("%f",&b);
A = h*b;
P = 2*(h+b);
printf("\nArea of Sqare (or) Rectangle: = %.3f",A);
printf("\nPerimeter of Sqare (or) Rectangle: = %.3f",P);
return 0;
}
```
### Output of the program
Enter Height: 24
Enter Bredth: 60
Area of Sqare (or) Rectangle: = 1440.000
Perimeter of Sqare (or) Rectangle: = 168.000


---------
# Program no.:-7
Write a code to print  a factorial
### Input of the program
```c
#include <stdio.h>
int main()
{
int c, n, f = 1;
printf("Enter a number to calculate its factorial\n");
scanf("%d", &n);
for (c = 1; c <= n; c++)
f = f * c;
printf("Factorial of %d = %d\n", n, f);
return 0;
}
```
----------
# Program no.:-8
Write a code to print to check the timings
### Input of the program
```c
#include <stdio.h>
clock_t start, end;
double cpu_time_used;
start = clock();
... /* Do the work. */
end = clock();
cpu_time_used = ((double) (end - start)) / CLOCKS_PER_SEC;
```
-----------
# Program no.:-9
Write a code to print farnehite to centrigrade
### Input of the program
```c
#include<stdio.h>
Int main()
{
float c,f;
clrscr();
printf("Enter the Temperature in farnehite: ");
scanf("%c",&f);
C=(5.0/9)* (f-32.0);
printf("Temparature in centigrate is : %f"\n",c);
return 0;
}
````

----------
# Program no.:-10
 Write a code to print the table of any number
### Input of the program
```c
#include<stdio.h>
Int main()
{
int i,no,table=1;
printf("Enter any number : ");
scanf("%d",&no);
printf("Table of %d \n",no);
for(i=1;i<=10;i++)
{
table=no*i;
printf("%d",table);
printf("\n");
}
```
---------
# Program no.:-11
Write a code to print program of the prime numbers
### Input of the program
```c
#include <stdio.h>
int main() {
    int n, i, flag = 0;
    printf("Enter a positive integer: ");
    scanf("%d", &n);

    for (i = 2; i <= n / 2; ++i) {

        // condition for non-prime
        if (n % i == 0) {
            flag = 1;
            break;
        }
    }

    if (n == 1) {
        printf("1 is neither prime nor composite.");
    }
    else {
        if (flag == 0)
            printf("%d is a prime number.", n);
        else
            printf("%d is not a prime number.", n);
    }

    return 0;
}
```
### output of the program
```c
Enter a positive integer: 29
29 is a prime number
```
------------
# Program no.:-12
 Write a code to print program of the swap of numbers using temporary variables
### Input of the program
```c
#include<stdio.h>
int main() {
      double first, second, temp;
      printf("Enter first number: ");
      scanf("%lf", &first);
      printf("Enter second number: ");
      scanf("%lf", &second);
     temp = first;
     first = second;
     second = temp;

      printf("\nAfter swapping, firstNumber = %.2lf\n", first);
      printf("After swapping, secondNumber = %.2lf", second);
      return 0;
}
```
### output of the program
```c
Enter first number: 1.20
Enter second number: 2.45

After swapping, firstNumber = 2.45
After swapping, secondNumber = 1.20
```
-----------
# Program no.:-13
 Write a code to print program of area and perimeter of the circle
### Input of the program
```c
#include <stdio.h> 
int main() {
   int radius;
   float area, perimeter;    
   radius = 6;

   perimeter = 2*3.14*radius;
   printf("Perimeter of the Circle = %f inches\n", perimeter);
	
	area = 3.14*radius*radius;
	printf("Area of the Circle = %f square inches\n", area);

return(0);
}
```
### output of the program
```c
Perimeter of the Circle = 37.680000 inches                             
Area of the Circle = 113.040001 square inches
```
----------
# Program no.:-14
 Write a code to print program to find interest 
### Input of the program
```c
#include<stdio.h>
int main()
{
float P,R,T,Interest;
printf("\nEnter The Principal Amount: ");
scanf("%f", &P);
printf("\nEnter The Interest Rate: ");
scanf("%f", &R);
printf("\nEnter The Time (in months): ");
scanf("%f", &T);
Interest = P*T*R/100;
printf("\nSimple Intesest is: = %.2f", Interest);
return Interest;
}
```
----------
# Program no.:-15
Write a code to print program to find maximum number
### Input of the program
```c
#include<stdio.h>
int max(float x,float y);
int main()
{
float x,y,z;
printf("\nEnter The First Value: ");
scanf("%f",&x);
printf("\nEnter The Second Value: ");
scanf("%f",&y);
z = max(x,y);
printf("\nMaximum value is: %.2f\n", z);
return 0;
}
int max(float x,float y)
{
float result;
if(x<y)
result = y;
else
result = x;
return 0;
}
```
------------
# Program no.:-16
 Write a code to print program to find minimum number
### Input of the program
```C
#include<stdio.h>
int min(float x,float y);
int main()
{
float x,y,z;
printf("\nEnter The First Value: ");
scanf("%f",&x);
printf("\nEnter The SecondValue: ");
scanf("%f",&y);
z = min(x,y);
printf("\nMinimum value is: %.2f\n", z);
return 0;
}
int min(float x,float y)
{
float result;
if(x<y)
result = x;
else
result = y;
return result;
}
```
### Output of the program
```c
Enter The First Value: 5
Enter The SecondValue: 3
Minimum value is: 3.00
```
---------
# Program no.:-17
Write a code to print program to find a power of number
### Input of the program
```c
#include<stdio.h>
int main()
{
int base,power,ans=1;
printf("\nEnter base number: ");
scanf("%d",&base);
printf("Enter exponent(power): ");
scanf("%d",&power);
while (power!=0)
{ ans *= base;
power--; }
printf("Answer = %d\n", ans);
return 0;
}
```
--------
# Program no.:-18
Write a code to print program to find square root of number
### Input of the program
```c
#include <stdio.h>
int main()
{
    double num, root;

    /* Input a number from user */
    printf("Enter any number to find square root: ");
    scanf("%lf", &num);

    /* Calculate square root of num */
    root = sqrt(num);

    /* Print the resultant value */
    printf("Square root of %.2lf = %.2lf", num, root);

    return 0;
}
```
### output of the program
```c
Enter any number to find square root: 144
Square root of 144.00 = 12.00
```
---------
# Program no.:-19
Write a code to print program to find the swap of number without using temporary variables
### Input of the program
```c
    #include<stdio.h>  
     int main()    
    {    
    int a=10, b=20;      
    printf("Before swap a=%d b=%d",a,b);      
    a=a+b;//a=30 (10+20)    
    b=a-b;//b=10 (30-20)    
    a=a-b;//a=20 (30-10)    
    printf("\nAfter swap a=%d b=%d",a,b);    
    return 0;  
    } 
 ```
### output of the program
```c
Before swap a=10 b=20
After swap a=20 b=10
```
----------
# Program no.:-20
 Write a code to print program to use arithmetic operators
### Input of the program
```c
#include<stdio.h>
int main()
{
float x,y,a;
printf("\nEnter The Value of x: ");
scanf("%f",&x);
printf("\nEnter The Value of y: ");
scanf("%f",&y);
a = x+y;
printf("x + y = %.3f\n",a);
a = x-y;
printf("x - y = %.3f\n",a);
a = y-x;
printf("y - x = %.3f\n",a);
a = x*y;
printf("x * y = %.3f\n",a);
a = x/y;
printf("x/y = %.3f\n",a);
a = y/x;
printf("y/x = %.3f\n",a);
return 0;
}
```
----------------
# Program no.:-21
 Write a code to print program to use assignment operators
### Input of the program
```C
#include<stdio.h>
int main()
{
float x,a;
printf("\nEnter The Value of x: ");
scanf("%f",&x);
a = x;
printf("Answer is a = x %.3f\n",a);
a +=x; //answer is a+x
printf("Answer is a+x = %.3f\n",a);
a -=x; //answer is a-x
printf("Answer is a-x = %.3f\n",a);
a *=x; //answer is a*x
printf("Answer is a*x = %.3f\n",a);
a /=x; //answer is a/x
printf("Answer is a/x= %.3f\n",a);
return 0;
}
```
### Output of the program
```c
Enter The Value of x: 45
Answer is a = x 45.000
Answer is a+x = 90.000
Answer is a-x = 45.000
Answer is a*x = 2025.000
Answer is a/x= 45.000
```
------------
# Program no.:-22
 Write a code to print program to use operator precedence
### Input of the program
```C
#include<stdio.h>
int main()
{
float a,b,c,d,A;
printf("\nEnter The Value of a: ");
scanf("%f",&a);
printf("Enter The Value of b: ");
scanf("%f",&b);
printf("Enter The Value of c: ");
scanf("%f",&c);
printf("Enter The Value of d: ");
scanf("%f",&d);
A = (a+b)*(c+d);
printf("\n (a+b)*(c+d) = %.3f",A);
A = (c+d)*a*b;
printf("\n (c+d)*a*b = %.3f",A);
A = a*d/(c-b-a);
printf("\n a*d/(c-b-a) = %.3f",A);
A = (b-c)*(a-d);
printf("\n (b-c)*(a-d) = %.3f",A);
return 0;
}
```
### Output of the program
```c
Enter The Value of a: 45
Enter The Value of b: 31
Enter The Value of c: 18
Enter The Value of d: 71
(a+b)*(c+d) = 6764.000
(c+d)*a*b = 124155.000
a*d/(c-b-a) = -55.086
(b-c)*(a-d) = -338.000
```
----------
# Program no.:-23
Write a code to print program to find average
### Input of the program
```c
#include<stdio.h>
int main()
{
int x,N;
float avg[1000],s,ans;
printf("\nEnter the Number of elements: ");
scanf("%d", &N);
printf("\n");
for(x=1; x<=N; x++)
{ printf("Enter [%d] element: ", x);
scanf("%f", &avg[x]);
s += avg[x]; }
ans = s/N;
printf("\nAverage of %d elements = %.3f", N, ans);
return 0;
}
```
----------
# Program no.:-24
Write a code to print program for addition of 2*2 matrices
### Input of the program
```c
#include <stdio.h>
int main() {
    int r, c, a[100][100], b[100][100], sum[100][100], i, j;
    printf("Enter the number of rows (between 1 and 100): ");
    scanf("%d", &r);
    printf("Enter the number of columns (between 1 and 100): ");
    scanf("%d", &c);

    printf("\nEnter elements of 1st matrix:\n");
    for (i = 0; i < r; ++i)
        for (j = 0; j < c; ++j) {
            printf("Enter element a%d%d: ", i + 1, j + 1);
            scanf("%d", &a[i][j]);
        }

    printf("Enter elements of 2nd matrix:\n");
    for (i = 0; i < r; ++i)
        for (j = 0; j < c; ++j) {
            printf("Enter element a%d%d: ", i + 1, j + 1);
            scanf("%d", &b[i][j]);
        }

    // adding two matrices
    for (i = 0; i < r; ++i)
        for (j = 0; j < c; ++j) {
            sum[i][j] = a[i][j] + b[i][j];
        }
```
### output of the program
```c
Enter the number of rows (between 1 and 100): 2
Enter the number of columns (between 1 and 100): 3

Enter elements of 1st matrix:
Enter element a11: 2
Enter element a12: 3
Enter element a13: 4
Enter element a21: 5
Enter element a22: 2
Enter element a23: 3
Enter elements of 2nd matrix:
Enter element a11: -4
Enter element a12: 5
Enter element a13: 3
Enter element a21: 5
Enter element a22: 6
Enter element a23: 3

Sum of two matrices: 
-2   8   7   

10   8   6  
```
--------
# Program no.:-25
Write a code to print program to take 5 values from the user and store them in an array and print the elements.
### Input of the program
```C
#include<stdio.h>
int main()
{
int x,array[5];
printf("\n");
for(x=1;x<=5;x++)
{ printf("Enter [%d] element: ", x);
scanf("%d", &array[x]); }
for(x=1;x<=5;x++)
{ printf("\nElement [%d] = %d", x, array[x]); }
return 0;
}
```
### Output of the Program
```c
Enter [1] element: 4
Enter [2] element: 5
Enter [3] element: 6
Enter [4] element: 9
Enter [5] element: 2
Element [1] = 4
Element [2] = 5
Element [3] = 6
Element [4] = 9
Element [5] = 2
```
-------
# Program no.:-26
write a code to print program the number is even or odd using if-else loop
### Input of the program
```c
#include <stdio.h>
int main() {
    int num;
    printf("Enter an integer: ");
    scanf("%d", &num);

    // True if num is perfectly divisible by 2
    if(num % 2 == 0)
        printf("%d is even.", num);
    else
        printf("%d is odd.", num);
    
    return 0;
}
```
### Output of the program
```c
Enter an integer: -7
-7 is odd
```
--------
# Program no.:-27
write a code to print program for sum of first natural numbers using for loop
### Input of the program
```c
#include <stdio.h>
int main() {
    int n, i, sum = 0;

    printf("Enter a positive integer: ");
    scanf("%d", &n);

    for (i = 1; i <= n; ++i) {
        sum += i;
    }

    printf("Sum = %d", sum);
    return 0;
}
```
### output of the program
```c
Enter a positive integer: 100
Sum = 5050
```
--------
# Program no.:-28
write a code to print Fizzbuzz of a integer
### Input of the program
```C
#include<stdio.h>
int main()
{
int n;
printf("\nEnter the Interger: ");
scanf("%d",&n);
if(n%15==0)
printf("\nFizzBuzz");
else if(n%3==0)
printf("Fizz\n");
else if (n%5==0)
printf("\nBuzz");
else
printf("\n%d",n);
return 0;
}
```
### Output of the program
```c
Enter the Interger: 171
Fizz
```
----------
# Program no.:-29
write a code to print  Program of FizzBuzz in a continues loop
### input of the program
```C
#include<stdio.h>
int main()
{
int n,x;
printf("\nEnter The Integer: ");
scanf("%d",&n);
printf("\n");
{
for(x=1;x<=n;x++)
if(x%15==0)
printf("FizzBuzz\n");
else if(x%3==0)
printf("Fizz\n");
else if(x%5==0)
printf("Buzz\n");
else
printf("%d\n",x);
}
return 0;
}
```
### Output of the program
```c
Enter The Integer: 17
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
```
-----
# Program no.:-30
Write a computer program in C, to print nth term, and sum up to nth term for series
### Input of the program
```c
#include <stdio.h>
int nth_ap(int a, int d, int n) {
   // using formula to find the
   // Nth term t(n) = a(1) + (n-1)*d
   return (a + (n - 1) * d);
}
//main function
int main() {
   // starting number
   int a = 2;
   // Common difference
   int d = 1;
   // N th term to be find
   int n = 5;
   printf("The %dth term of AP :%d\n", n, nth_ap(a,d,n));
   return 0;
}
```
###output of the program
```c
The 5th term of the series is: 6
```
------
# Program no.:-31
Write a computer program in C, which take integer input from user. If entered value > 10, it will call a function, which prints multiplication table of of entered number, from 1 to 10.
### Input of the program
#include <stdio.h>

int main()
{
    int i, num;

    /* Input a number to print table */
    printf("Enter number to print table: ");
    scanf("%d", &num);

    for(i=1; i<=10; i++)
    {
        printf("%d * %d = %d\n", num, i, (num*i));
    }

    return 0;
}
```
### output of the program
```c
Enter number to print table of: 5
5 * 1 = 5
5 * 2 = 10
5 * 3 = 15
5 * 4 = 20
5 * 5 = 25
5 * 6 = 30
5 * 7 = 35
5 * 8 = 40
5 * 9 = 45
5 * 10 = 50
```
--------
# Program no.:-32
write a code to print program of game of life
### Input of the program
```c
// A simple Java program to implement Game of Life 
public class GameOfLife 
{ 
    public static void main(String[] args) 
    { 
        int M = 10, N = 10; 
  
        // Intiliazing the grid. 
        int[][] grid = { { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 }, 
            { 0, 0, 0, 1, 1, 0, 0, 0, 0, 0 }, 
            { 0, 0, 0, 0, 1, 0, 0, 0, 0, 0 }, 
            { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 }, 
            { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 }, 
            { 0, 0, 0, 1, 1, 0, 0, 0, 0, 0 }, 
            { 0, 0, 1, 1, 0, 0, 0, 0, 0, 0 }, 
            { 0, 0, 0, 0, 0, 1, 0, 0, 0, 0 }, 
            { 0, 0, 0, 0, 1, 0, 0, 0, 0, 0 }, 
            { 0, 0, 0, 0, 0, 0, 0, 0, 0, 0 } 
        }; 
  
        // Displaying the grid 
        System.out.println("Original Generation"); 
        for (int i = 0; i < M; i++) 
        { 
            for (int j = 0; j < N; j++) 
            { 
                if (grid[i][j] == 0) 
                    System.out.print("."); 
                else
                    System.out.print("*"); 
            } 
            System.out.println(); 
        } 
        System.out.println(); 
        nextGeneration(grid, M, N); 
    } 
  
    // Function to print next generation 
    static void nextGeneration(int grid[][], int M, int N) 
    { 
        int[][] future = new int[M][N]; 
  
        // Loop through every cell 
        for (int l = 1; l < M - 1; l++) 
        { 
            for (int m = 1; m < N - 1; m++) 
            { 
                // finding no Of Neighbours that are alive 
                int aliveNeighbours = 0; 
                for (int i = -1; i <= 1; i++) 
                    for (int j = -1; j <= 1; j++) 
                        aliveNeighbours += grid[l + i][m + j]; 
  
                // The cell needs to be subtracted from 
                // its neighbours as it was counted before 
                aliveNeighbours -= grid[l][m]; 
  
                // Implementing the Rules of Life 
  
                // Cell is lonely and dies 
                if ((grid[l][m] == 1) && (aliveNeighbours < 2)) 
                    future[l][m] = 0; 
  
                // Cell dies due to over population 
                else if ((grid[l][m] == 1) && (aliveNeighbours > 3)) 
                    future[l][m] = 0; 
  
                // A new cell is born 
                else if ((grid[l][m] == 0) && (aliveNeighbours == 3)) 
                    future[l][m] = 1; 
  
                // Remains the same 
                else
                    future[l][m] = grid[l][m]; 
            } 
        } 
  
        System.out.println("Next Generation"); 
        for (int i = 0; i < M; i++) 
        { 
            for (int j = 0; j < N; j++) 
            { 
                if (future[i][j] == 0) 
                    System.out.print("."); 
                else
                    System.out.print("*"); 
            } 
            System.out.println(); 
        } 
    } 
} 
```
### output of the program
```c
Original Generation
..........
...**.....
....*.....
..........
..........
...**.....
..**......
.....*....
....*.....
..........

Next Generation
..........
...**.....
...**.....
..........
..........
..***.....
..**......
...**.....
..........
.........
------
```
# Program no.:-33
Write a C Program to Check Whether a Number is Positive or Negative
### Input of the program
```c
#include <stdio.h>
int main() {
    double num;
    printf("Enter a number: ");
    scanf("%lf", &num);
    if (num <= 0.0) {
        if (num == 0.0)
            printf("You entered 0.");
        else
            printf("You entered a negative number.");
    } else
        printf("You entered a positive number.");
    return 0;
}
```
### output of the program
```c
Enter a number: 12.3
You entered a positive number.
```
-------
# Program no.:-34
 write a C Program to Display Characters from A to Z Using Loop
### Input of the program
```c
#include <stdio.h>
int main() {
    char c;
    for (c = 'A'; c <= 'Z'; ++c)
        printf("%c ", c);
	return 0;
```
 ### output of the program
```c
A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
```
-----------

