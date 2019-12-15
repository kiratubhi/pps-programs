 
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
## 6:Write a program to show the size of int,float,char,double,long,short.
```
 // size of int, float, char, double, long, short
#include<stdio.h>
int main()
{                                   
 printf("Integer:%d\n",sizeof(int));
 printf("float:%d\n",sizeof(float));
 printf("character:%d\n",sizeof(char));
 printf("double:%d\n",sizeof(double));
 printf("short:%d\n",sizeof(short));
 printf("long:%d\n",sizeof(long));
 }
```
**OUTPUT**:
```
Integer:4
float:4
character:1
double:8
short:2
long:8
```
## 7:Write a program to show area,perimeter,volume of square
```
   
 //Area,premiter,volume of square
  #include<stdio.h>
void square();
int main()
{     
 square();
 return 0;
}                                    
void square()
{
 int side;
 printf("Enter the side of square:");
 scanf("%d",&side);

 printf("\nPerimeter of square:%d",4*side);
 printf("\nArea of square:%d",side*side);
 printf("\nVolume of square:%d\n",side*side*side);
}
```
**OUTPUT**:
```
Enter the side of square:4

Perimeter of square:16
Area of square:16
Volume of square:64
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
 int a,b,n;
 printf("table of:");
 scanf("%d",&a);
 printf("\n enter the starting value of range:");
 scanf("%d",&b);
 printf("\n enter the last value of range:");
 scanf("%d",&n);
 for(b;b<=n;b++)
 printf("%d x %d = %d\n",a,b,a*b);
 return 0;
 }
```
**OUTPUT**:
```
table of:5

 enter the starting value of range:20

 enter the last value of range:30
5 x 20 = 100
5 x 21 = 105
5 x 22 = 110
5 x 23 = 115
5 x 24 = 120
5 x 25 = 125
5 x 26 = 130
5 x 27 = 135
5 x 28 = 140
5 x 29 = 145
5 x 30 = 150
```
## 14:Write a program to show even table.
```
//To show only even table
#include<stdio.h>
int main(){
int m;
printf("tabel of:");
scanf("%d",&m);
if(m%2==0)
{
for(int i=0;i<=20;i++)
{
printf("%d X %d=%d\n",m,i,m*i);
}}
else
printf("enter even number\n");

return 0;}
```
**OUTPUT**:
```
tabel of:16
16 X 0=0
16 X 1=16
16 X 2=32
16 X 3=48
16 X 4=64
16 X 5=80
16 X 6=96
16 X 7=112
16 X 8=128
16 X 9=144
16 X 10=160
16 X 11=176
16 X 12=192
16 X 13=208
16 X 14=224
16 X 15=240
16 X 16=256
16 X 17=272
16 X 18=288
16 X 19=304
16 X 20=320
```
## 15: Write a program to show result of operands.
```
//To show results using operands(+,-,*,%,/)
#include<stdio.h>
int main()
{
float a,b;
 char c;
printf("enter first  number:");
scanf("%f",&a);
printf("enter operator[+ - % / *]:");
scanf(" %c",&c);
printf("enter second number:");
scanf("%f",&b);
int d,r;
d=(int) a;
r=(int) b;
switch(c)
{
case '+': printf("The result is:%.2f\n",a+b); break;
case '-':printf("The result is:%.2f\n",a-b); break;
case '*':printf("The result is:%.2f\n",a*b); break;
case '%':printf("The result is:%d\n",d%r); break;
case '/':printf("The result is:%.2f\n",a/b); break;
default : printf("Enter correct operator ");
}
return 0;
}
```

**OUTPUT**:
```
enter first  number:20
enter operator[+ - % / *]: *
enter second number:10
The result is:200.00
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
 
 ## 19:Write a program to show factorial of a number.
 ```
 //To show factorial of user input
#include<stdio.h>
int main()
{
 int a,result=1;
 printf("Enter the factorial of:");
 scanf("%d",&a);
 for(int i=a;i>=1;i--)
{
printf("%d X ",i);
result=result*i;
}
printf("= %d\n",result);
return 0;
}
```
**OUTPUT**:
```
Enter the factorial of:5
5 X 4 X 3 X 2 X 1 X = 120
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
