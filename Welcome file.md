 
<img src="https://i.imgur.com/EZtECRw.png" align="center">

---

<h3><b><center>Guru Nanak Dev Engineering College<br>
        Programming for Problem Solving 
 <br>ESC-18105</center></b>
  
  
     
    Name Harkirat kaur 
    Branch-InformationTechnology
    Section - A2 
    Roll Number - 1921036
    University roll number - 1905334
    # My C programes 

## 1:Write a program to print hello world.

```
//To print  hello world
#include<stdio.h>
int main()
{                     
 printf("\nHello world\n");
}
```
**OUTPUT:**
``` 
 Hello world
```
## 2:Write a program to fill your information.

```
  // To fill your information
#include<stdio.h>
  int main()
  { 
  char a[20];
     int roll,age,ph;
   printf("\nEnter your information:\n");
   printf("Name = ");
    scanf("%c",a);
  printf("\nRoll no=");
scanf("%d",&roll);
printf("\nAge = ");
 scanf("%d",&age);
 printf("\nPhone no.= ");
 scanf("%d",&ph);
printf("\nThe name is %c\n
Your roll no is %d\n
My phone number is %d\n
My age is %d\n",a,roll,ph,age);

}
```
**OUTPUT:**
```
Enter your information:
Name = Harkirat
Roll no=1905334
Age = 18
Phone no.= 9922115566

The name is Harkirat
Your roll no is 1905334
My phone number is 9922115566
 My age is 18
 ```

## 3:Write a program to find sum of two numbers
```

     // to find sum of two numbers
     #include<stdio.h>
int main()
{                                                                                      
 int a;
 int b;
 int c ;
 printf("Enter two numbers to get sum:");
 scanf("%d  %d",&a,&b);
 printf(" \nThe result is :%d + %d= %d\n",a,b,c=a+b);
    return 0;
 }
```
**OUTPUT**:
```
Enter two numbers to get sum:45 55
 
The result is :45 + 55= 100
```
## 4:Write a program to Sum and average of numbers
```
 // sum and average of number
#include<stdio.h>
  int main()
 {                                 
     int a,b,c,d,e,sum,avg;
                                                               
   printf("Enter five numbers:");
   scanf("%d %d %d %d %d",&a,&b,&c,&d,&e);
    sum = a+b+c+d+e;
   printf("The sum is:%d\n",sum);
   avg = sum/5;
   printf("The average is:%d\n",avg);
  }
``` 
**OUTPUT**:
```
Enter five numbers:1 2 3 4 5 
The sum is:15
The average is:3
```
  ## 5:Write a program to find number is even or odd.
  ```
       #include<stdio.h>
int main()
 {                                
    int a;   
   printf("Enter a number:");
   scanf("%d",&a);
 if(a%2==0)
  printf("The  number is even\n");
 else
   printf("The number is odd\n");
 }
```
**OUTPUT**:
```
Enter a number:4
The  number is even
```
***OR***
```
Enter a number:7
The number is odd
```
## 6:Write a program to swap two numbers.
```
#include<stdio.h>
int swap(int a,int b);
int main()
{
int a,b;
printf("please enter 2 integer values a and b:\n");
scanf("%d %d",&a,&b);
swap(a,b);
}
int swap(int a,int b)
{
a=a+b;
b=a-b;
a=a-b;
printf("value of a is:%d\n",a);
printf("value of b is:%d\n",b);
}
```
**OUTPUT**:
```
please enter 2 integer values a and b:
2
8
value of a is:8
value of b is:2
```
## 7:Write a program to show years of experience of the employees.
```
#include<stdio.h>
int main()
{
int n,y,sum=0;
printf("\n enter number of employees");
scanf("%d",&n);
for(int i=1;i<=n;i++)
{
printf("enter the data of %d employee",i);
scanf("%d",&y);
sum=sum+y;
}
printf("%d",sum);
return 0;
}
```
**OUTPUT**:
```
 enter number of employees3
enter the data of 1 employee4
enter the data of 2 employee4
enter the data of 3 employee6
14
```
## 8:Write a program to show puts value upto n number using loop.
```
// to show punishment using loop
 #include<stdio.h>
 int main()
 {
 int i,a;
 printf("Enter the number upto punishment is shown:");
 scanf("%d",&a);
  for(i=1;i<=a;i++)
puts("WORK HARD AND ACHIEVE SUCCESS ");
return 0;
}
```
**OUTPUT**:
```
Enter the number upto punishment is shown:10
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS 
WORK HARD AND ACHIEVE SUCCESS
```
## 9:Write a program to show area,diameter,circumference of circle .
```
   #include<stdio.h>
 int main()
  {
    float a;   
float  const pi=3.14;
   printf("Enter radius of circle:");
    scanf("%f\n",&a);
  printf("diameter of circle is:%f\n",2*a);
  printf("circumference of circle:%f\n",2*pi*a);
  printf("Area of circle:%f\n",pi*a*a);
return 0;
 } 
```
**OUTPUT**:
```
Enter radius of circle:6
diameter of circle is:12.000000
circumference of circle:37.680000
Area of circle:113.040001
```
## 10:Write a program to find area and volume of rectangle.
```
//find area and volume of rectangle
#include<stdio.h>
int main()
{
 int l,b,h;
 printf("Enter length of rectangle:");
 scanf("%d",&l);
 printf("\nEnter breadth of rectangle:");
 scanf("%d",&b);
 printf("\nEnter height of rectangle:");
 scanf("%d",&h);
 printf("\nThe area of rectangle is:%d",l*b);
 printf("\nThe volume is :%d\n",l*b*h);
 return 0;
 }
 ```
 **OUTPUT**:
 ```
 Enter length of rectangle:4 

Enter breadth of rectangle:3 

Enter height of rectangle:4

The area of rectangle is:12
The volume is :48
```
 
 ##  11 .Write a program to represent a table of user input .
 
 ```
  // To represent a table of user input  number
 #include<stdio.h>
 int main()
 {
    int i,j,k;
  printf("Table of:");
  scanf("%d",&j);

   for(i=0;i<=10;i++)
   printf("%d x %d = %d\n",j,i,j*i);

return 0;
}
```
**OUTPUT**:
```Table of:15
15 x 0 = 0
15 x 1 = 15
15 x 2 = 30
15 x 3 = 45
15 x 4 = 60
15 x 5 = 75
15 x 6 = 90
15 x 7 = 105
15 x 8 = 120
15 x 9 = 135
15 x 10 = 150
```
## 12:Write a program to convert Fahrehnite to Celcius.
```
//to convert fahrehnite to celcius
#include<stdio.h>
int main(){
float f,c;
printf("Enter temp in fahrehnite :");
scanf("%f",&f);
c=((f-32)*5)/9;
printf("The celcius value is:%f\n",c);

return 0;
}
```
**OUTPUT**:
```
Enter temp in fahrehnite :450
The celcius value is:232.222229
```
## 13: Write a program to show the table range .
```
//To show a range of table upto user input
#include<stdio.h>
int main()
{
int b,c,i,x;
printf("enter the starting number");
scanf("%d",&b);
printf("enter the ending number");
scanf("%d",&c);
for(i=b;i<=c;i++)
{
for(x=1;x<=10;x++){
printf("\n %d X %d =%d",i,x,i*x);
}
}
return 0;
}
```
**OUTPUT**:
```
enter the starting number3
enter the ending number5

 3 X 1 =3
 3 X 2 =6
 3 X 3 =9
 3 X 4 =12
 3 X 5 =15
 3 X 6 =18
 3 X 7 =21
 3 X 8 =24
 3 X 9 =27
 3 X 10 =30
 4 X 1 =4
 4 X 2 =8
 4 X 3 =12
 4 X 4 =16
 4 X 5 =20
 4 X 6 =24
 4 X 7 =28
 4 X 8 =32
 4 X 9 =36
 4 X 10 =40
 5 X 1 =5
 5 X 2 =10
 5 X 3 =15
 5 X 4 =20
 5 X 5 =25
 5 X 6 =30
 5 X 7 =35
 5 X 8 =40
 5 X 9 =45
 5 X 10 =50
```
## 14:Write a program to show even table.
```
//To show only even table
#include<stdio.h>
int main()
{
int a,b,i,x;
printf("enter the starting and ending number");
scanf("%d%d",&a,&b);
for (i=a;i<=b;i++)
{
 if(i%2==0)
  {
    for(x=1;x<=10;x++)
      {
        printf("\n%d X %d = %d ",i,x,i*x);
      }
  }
}
return 0;
}   
```
**OUTPUT**:
```
enter the starting and ending number2
7

2 X 1 = 2 
2 X 2 = 4 
2 X 3 = 6 
2 X 4 = 8 
2 X 5 = 10 
2 X 6 = 12 
2 X 7 = 14 
2 X 8 = 16 
2 X 9 = 18 
2 X 10 = 20 
4 X 1 = 4 
4 X 2 = 8 
4 X 3 = 12 
4 X 4 = 16 
4 X 5 = 20 
4 X 6 = 24 
4 X 7 = 28 
4 X 8 = 32 
4 X 9 = 36 
4 X 10 = 40 
6 X 1 = 6 
6 X 2 = 12 
6 X 3 = 18 
6 X 4 = 24 
6 X 5 = 30 
6 X 6 = 36 
6 X 7 = 42 
6 X 8 = 48 
6 X 9 = 54 
6 X 10 = 60
```
## 15: Write a program to show result of operands.
```
//To show results using operands(+,-,*,%,/)
#include<stdio.h>
int main()
{
float a,b;
int c;
char op;
printf("\n enter the number");
scanf("%f%f",&a,&b);
printf("\n enter the operator ");
scanf(" %c",&op);
switch(op)
{
case '+':printf("%f",a+b);
break;
case '-':printf("%f",a-b);
break;
case '*':printf("%f",a*b);
break;
case '/':printf("%f",a/b);
break;
case '%':c=(int)a%(int )b;
printf("%d",c);
break;
default:printf("invalid statement");
}
}
```

**OUTPUT**:
``` enter the number4
6
 enter the operator +
10.000000
```
## 16:Write a program to call a patterns of face and calculator.
```
// call a pattern of face or calculator
             #include<stdio.h>

void calculator();
void face();
int main()
{  int a;
 printf("enter 0 to see a calculator or 1 to see face\n");
 scanf("%d",&a);

if(a==0)
{
   calculator();
}
   else if(a==1)
{
     face();
  }
 else
{
  printf("enter correct values\n");
}
}
 void calculator()
{ 
puts(" _______________");
puts("|               |");
puts("|_______________|");
puts("| 1 | 2 | 3 |   |");
puts("|___|___|___|   |");
puts("| 4 | 5 | 6 | + |");
puts("|___|___|___|___|");
puts("| 7 | 8 | 9 | - |");
puts("|___|___|___|___|");
puts("|     0     | * |");
puts("|___________|___|");
}
 
 void face()
{
puts("___________________");
puts("|   XXXXXXXXXXX   |");
puts("|   ( ^     ^ )   |");
puts("|   ( 0     0 )   |");
puts("|    \\   |   /    |");
puts("|     \\     /     |");
puts("|      \\ = /      |");
puts("|       \\_/       |");
puts("|        |        |");
puts("|________|________|");
}
```
**OUTPUT**:IF YOU ENTER 0 THEN OUTPUT IS :
``` 
enter 0 to see a calculator or 1 to see face
0
 _______________
|               |
|_______________|
| 1 | 2 | 3 |   |
|___|___|___|   |
| 4 | 5 | 6 | + |
|___|___|___|___|
| 7 | 8 | 9 | - |
|___|___|___|___|
|     0     | * |
|___________|___|
```
IF YOU ENTER 1 THEN OUTPUT
```
enter 0 to see a calculator or 1 to see face
1
___________________
|   XXXXXXXXXXX   |
|   ( ^     ^ )   |
|   ( 0     0 )   |
|    \   |   /    |
|     \     /     |
|      \ = /      |
|       \_/       |
|        |        |
|________|________|
```
## 17:Write a program to find maximum number.
```
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
         return result;
    }

**Output**

Enter The First Value: 5

Enter The Second Value: 4

Maximum value is: 5.00

```

## 18:Write a program to find average of numbers.
```
  #include<stdio.h>
     int main()
     {
     int x,N;
     float avg[1000],s,ans;

     printf("\nEnter the Number of elements: ");
     scanf("%d", &N);
     printf("\n");

     for(x=1; x<=N; x++)
       {  printf("Enter [%d] element: ", x);
          scanf("%f", &avg[x]);
          s += avg[x];  }
  
       ans = s/N;

     printf("\nAverage of %d elements = %.3f", N, ans);
     return 0;
     }
 ```
 **OUTPUT**:
 ```
 Enter the Number of elements: 8

 Enter [1] element: 1
 Enter [2] element: 2
 Enter [3] element: 3
 Enter [4] element: 4
 Enter [5] element: 5
 Enter [6] element: 6
 Enter [7] element: 7
 Enter [8] element: 8
 
 Average of 8 elements = 4.500
```
 
 ## 19:Write a program to show factorial of a number using recursion.
 ```
 #include<stdio.h>
int factorial(int n);
int main(){
printf("enter a number ");
int fact;
scanf("%d",&fact);
printf("%d\n",factorial(fact));

return 0;
}
int factorial(int n)
{int a;

if(n==0){a=1;

}
else
a=n*factorial(n-1);

return a;
}
```
**OUTPUT**:
```enter a number 5
120
```
 ## 20:Write a program to show addition and subtraction of two matrices.
 ```
 #include<stdio.h>
    int main()

    {
         float a,b,c,d,e,f,g,h,i,j,k,l;
         printf("\nSample of Ist matrix: | a=1      b=2 |\n 
         | c=3      d=4 |\n\n\
         Sample of 2nd matrix: | e=5      f=6 |\n    
         | g=7      h=8 |\n\n");
         printf("Enter The Valve of a: ");
         scanf("%f",&a);
         printf("Enter The Valve of b: ");
         scanf("%f",&b);
         printf("Enter The Valve of c: ");
         scanf("%f",&c);
         printf("Enter The Valve of d: ");
         scanf("%f",&d);
         printf("Enter The Valve of e: ");
         scanf("%f",&e);
         printf("Enter The Valve of f: ");
         scanf("%f",&f);
         printf("Enter The Valve of g: ");
         scanf("%f",&g);
         printf("Enter The Valve of h: ");
         scanf("%f",&h); 
        
         i = a+e;
         j = b+f;
         k = c+g;
         l = d+h;
         printf("\n\nSum of Matrix(A+B) is: | %.2f     %.2f |\n            
         | %.2f     %.2f |",i,j,k,l)
         i = a-e;
         j = b-f;
         k = c-g;
         l = d-h;
         printf("\n\nSubstraction of Matrix(A-B) is: | %.2f     %.2f |\n 
         | %.2f     %.2f |",i,j,k,l);
         i = e-a;
         j = f-b;
         k = g-c;
         l = h-d;
         printf("\n\nSubstraction of Matrix(B-A) is: | %.2f     %.2f |\n 
         | %.2f     %.2f |",i,j,k,l); 
         return 0;
    }
```
**OUTPUT**:
```
Sample of Ist matrix: | a=1      b=2 |
                      | c=3      d=4 |

Sample of 2nd matrix: | e=5      f=6 |
                      | f=7      h=8 |

Enter The Valve of a: 7
Enter The Valve of b: 5
Enter The Valve of c: 4
Enter The Valve of d: 0
Enter The Valve of e: 3
Enter The Valve of f: 5
Enter The Valve of g: 9
Enter The Valve of h: 1


Sum of Matrix(A+B) is: | 10.00     10.00 |
                       | 13.00     1.00 |

Substraction of Matrix(A-B) is: | 4.00     0.00 |
                                | -5.00     -1.00 |

Substraction of Matrix(B-A) is: | -4.00     0.00 |
                                | 5.00     1.00 |
```

## 21:Write a program to show Matrix multipication.
 ```
 #include<stdio.h>
    int main()
    {
    float a,b,c,d,e,f,g,h,i,j,k,l;

    printf("\nSample of Ist matrix: | a=1      b=2 |\n  
    | c=3      d=4 |\n\n\
    Sample of 2nd matrix: | e=5      f=6 |\n  
    | f=7      h=8 |\n\n");
         printf("Enter The Valve of a: ");
         scanf("%f",&a);
         printf("Enter The Valve of b: ");
         scanf("%f",&b);
         printf("Enter The Valve of c: ");
         scanf("%f",&c);
         printf("Enter The Valve of d: ");
         scanf("%f",&d);
         printf("Enter The Valve of e: ");
         scanf("%f",&e);
         printf("Enter The Valve of f: ");
         scanf("%f",&f);
         printf("Enter The Valve of g: ");
         scanf("%f",&g);
         printf("Enter The Valve of h: ");
         scanf("%f",&h); 

         i=(a*e)+(b*g);
         j=(a*f)+(b*h);
         k=(c*e)+(d*g);
         l=(c*f)+(d*h);

         printf("\nMultiplication of A,B is: | %.2f     %.2f |\n 
         | %.2f     %.2f |",i,j,k,l);

         return 0;
    }
 ```
 **OUTPUT**:
 ```
 Sample of Ist matrix: | a=1      b=2 |
                      | c=3      d=4 |

Sample of 2nd matrix: | e=5      f=6 |
                      | f=7      h=8 |

Enter The Valve of a: 7
Enter The Valve of b: 5
Enter The Valve of c: 4
Enter The Valve of d: 0
Enter The Valve of e: 3
Enter The Valve of f: 5
Enter The Valve of g: 9
Enter The Valve of h: 1

Multiplication of A,B is: | 66.00     40.00 |
                          | 12.00     20.00 |
```
## 22: Write a program to find Prime number.
```
#include<stdio.h>
int main()
{
int a,b = 0;
printf("\nEnter the Number: ");
scanf("%d",&a);
  for(int x=2; x<a; x++)
  {  if(a%x==0)
     {  flag = 1;
        break;  }
  }
if(b == 1)
printf("%d is not a Prime Number",a);
if(b== 0)
printf("%d is a Prime Number",a);
return 0;
}

**Output**
  Enter the Number: 7
  7 is a Prime Number

  Enter the Number: 8
  8 is not a Prime Number
```
##23:Write a program of days of the week.
```
     #include<stdio.h>
     int main()
     {
     int x;
     printf("\n\nEnter the day Number: ");
     scanf("%d", &x);
     switch(x)
     {
       case 1:
       if(x==1)
       {  printf("\nSunday");  }
       case 2:
       if(x==2)
       {  printf("\nMonday");  }
       case 3:
       if(x==3)
       {  printf("\nTuesday");  }
       case 4:
       if(x==4)
       {  printf("\nWednesday");  }
       case 5:
       if(x==5)
       {  printf("\nThursday");  }
       case 6:
       if(x==6)
       {  printf("\nFriday");  }
           case 7:
       if(x==7)
       {  printf("\nSaturday");  
     } 
     return 0;
     }
**Output**

Enter the day Number: 3

Tuesday
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTk0Njc2OTc1MiwxNjU2OTAxNTI4LC03Mj
g2NzQ5NjUsLTc4ODExMDUzMywxNDAxMzg0NjY0LDE2MTgwMjUy
ODAsNDg3NDA0MzAxLDIwOTY4MjEwMzQsLTIxMjg5MTIwOTIsLT
I2MDQ0OTE2NywtMjc3NjA5ODExLDExMzUyMDA5NjEsLTY0MzA4
ODI1NiwzOTMzOTkyMzgsNzc0OTQ3NzEzLC0xOTM0OTcwMDY2LC
0xNTMzMjE1ODU2LDQwNzQ1NzQyMiwtMjMyMDc4MTA4LDEzMTEw
NDM5MzddfQ==
-->

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MzA1MDQxMjksMTk4NTg2OTYzMSwxOT
UwNjM2OTVdfQ==
-->
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjYwMDY1Mjg3XX0=
-->
