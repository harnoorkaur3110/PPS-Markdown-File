﻿![GURU NANAK DEV ENGINEERING COLLEGE](https://gndec.ac.in/)
# **Programming for Problem Solving**
## **Name:- Ekam Preet Singh**
## **CRN:-1921028/1905327**
## **Branch:- IT-A1**
## **Subject code: ESC18104/18105**
## **Submitted To:- Ms. Ranjodh Kaur**

## 1)To print hello world
  ```
//To print  hello world
#include<stdio.h>
int main()
{                     
 printf("\nHello world\n");
}
```
**Output:-**
```
Hello world
```
## 2)To fill your information

   ```
  // To fill your information
#include<stdio.h>

  void info();
  int main()
  {
     info();
  }

   void info()
  {  char a[20];
     int roll,age;
     long int ph;
   printf("\nEnter your information:\n");
   printf("Name = ");
    scanf("%s",a);
  printf("\nRoll no=");
scanf("%d",&roll);
printf("\nAge = ");
 scanf("%d",&age);
 printf("\nPhone no.= ");
 scanf("%ld",&ph);

printf("\nThe name is %s\nYour roll no is %d\nMy phone number is %ld\n My age is %d\n",a,roll,ph,age);

}
```
**Output:-**
```
Enter your information:
Name = Ekam

Roll no=1921028

Age = 18

Phone no.= 9569818072

The name is Ekam
Your roll no is 1921028
My phone number is 9569818072
My age is 18
```
## 3)To find sum of two numbers

   ```
// to find sum of two numbers
#include<stdio.h>
int main()
{                                                                                      
 int x;
 int y;
 int z ;
 printf("Enter two numbers to get sum:");
 scanf("%d  %d",&x,&y);
 printf(" \nThe result is :%d + %d= %d\n",x,y,z=x+y);
 return 0;
 }

```

**Output:-**

```
Enter two numbers to get sum:45 55
 
The result is :45 + 55= 100
```
## 4)Sum and average of numbers

   ```
 // sum and average of number
#include<stdio.h>
  int main()
 {                                 
     int x,y,z,p,q,sum,avg;                                                          
   printf("Enter five numbers:");
   scanf("%d %d %d %d %d",&x,&y,&z,&p,&q);
    sum = x+y+z+p+q;
   printf("The sum is:%d\n",sum);
   avg = sum/5;
   printf("The average is:%d\n",avg);
  }

```

**Output:-**

```
Enter five numbers:1 2 3 4 5 
The sum is:15
The average is:3

```

## 5)To find number is even or odd

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

_**OR**_

```
Enter a number:7
The number is odd

```

## 6)To show the size of int,float,char,double,long,short

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

**Output:-**

```
Integer:4
float:4
character:1
double:8
short:2
long:8

```

## 7)To show area,perimeter,volume of square

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

**Output:-**

```
Enter the side of square:4

Perimeter of square:16
Area of square:16
Volume of square:64

```

## 8)To show puts value upto n number using loop

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

**Output:-**

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

## 9)To show area,diameter,circumference of circle

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

**Output:-**

```
Enter radius of circle:6
diameter of circle is:12.000000
circumference of circle:37.680000
Area of circle:113.040001
 
```

##  9)To find area and volume of rectangle

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

**Output:-**

```
Enter length of rectangle:4 
Enter breadth of rectangle:3 
Enter height of rectangle:4

The area of rectangle is:12
The volume is :48

```

## 10)To represent a table of user input

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

**Output:-**

```

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

## 11)To convert fahrenheit to celsius

```
//to convert fahrenheit to celsius
#include<stdio.h>
int main(){
float f,c;
printf("Enter temp in fahrenheit :");
scanf("%f",&f);
c=((f-32)*5)/9;
printf("The celsius value is:%f\n",c);

return 0;
}

```

**Output:-**

```
Enter temp in fahrenheit :450
The celsius value is:232.222229

```

## 12) To show the table range

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

**Output:-**

  ```
table of:5

 Enter the starting value of range:20

 Enter the last value of range:30
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

## 13)To show  table of any given number
```
#include <stdio.h>
int main()
{
    int n, i;
    printf("Enter an integer: ");
    scanf("%d",&n);
    for(i=1; i<=10; ++i)
    {
        printf("%d * %d = %d \n", n, i, n*i);
    }
    
    return 0;
}
```

**Output:-**
```
#include <stdio.h>
int main()
{
    int n, i;
    printf("Enter an integer: ");
    scanf("%d",&n);
    for(i=1; i<=10; ++i)
    {
        printf("%d * %d = %d \n", n, i, n*i);
    }
    
    return 0;
}
```
## 14)To show result of operands

  ```
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

**Ouput:-**

```
enter first  number:60
enter operator[+ - % / *]: +
enter second number:90
The result is:150.00

```

## 15)To call a patterns of face and calculator

   ```

#include<stdio.h>

void calculator();
void face();
int main()
{  int a;
 printf("Enter 0 to see a calculator or 1 to see face\n");
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

**Output:-**

```
Enter 0 to see a calculator or 1 to see face
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

IF YOU ENTER 1 THEN OUTPUT

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

## 16)To convert fahrenheit to celsius and kelvin

   ```
 #include<stdio.h>
 int main()
 {
  float a,b,c;
  printf("Enter a fahrenheit value:");
  scanf("%f",&a);
b=((a-32.00)*5.00)/9.00;
 printf("celsius value is:%.2f\n",b);

 printf("kelvin value is:%.2f\n",c=b+273.15);
  return 0;} 

```

**Output:-**

```
Enter a fahrenheit value:450
celsius value is:232.22
kelvin value is:505.37

```

## 17)To show stars pattern

  ```
#include<stdio.h>
int main()
{ int i,j,k;
 printf("Enter the value to show pattern:");
 scanf("%d",&k);
 
  for(i=k;i>=1;i--)
 {
  for(j=i;j>=1;j--)
 {
  printf("* ");
 }
 printf("\n");
 }
 return 0;
 }

```

**Output:-**

```
Enter the value to show pattern:8
* * * * * * * * 
* * * * * * * 
* * * * * * 
* * * * * 
* * * * 
* * * 
* * 
*

```

## 18)To show factorial result

```
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

**Output:-**

```
Enter the factorial of:4
4 X 3 X 2 X 1 X = 24

```

## 19)To show stars pattern

```
#include<stdio.h>
int main()
{
int i,j,k;
printf("Enter the value upto pattern is shown:");
scanf("%d",&k);

for(i=1;i<=k;i++)
{
 for(j=1;j<=i;j++)
{
 printf("* ");
}
printf("\n");
}
return 0;
}

```

**Output:-**

```
Enter the value upto pattern is shown:5
* 
* * 
* * * 
* * * * 
* * * * * 
```

## 20)Matrix multipication
 
  ```
#include<stdio.h>
int main()
{
int sum=0,m,n,p,q,c,d,k;
int first[10][10], second[10][10], multiply[10][10];
// for matrix 1
printf("Enter the number of rows and column of first matrix:\n");
scanf("%d %d",&m,&n);
printf("Enter elements of first matrix:\n");

for(c=0;c<m;c++)
for(d=0;d<n;d++)
 scanf("%d",&first[c][d]);
// for second matrix
printf("Enter the number of rows and columns of second matrix:\n");
scanf("%d %d",&p,&q);

if(n!=p){
printf("matrix multipication cannot be possible !!!!\n");}

else{
printf("Enter the elements of second matrix:\n");
for(c=0;c<p;c++)
for(d=0;d<q;d++)
 scanf("%d",&second[c][d]);

for(c=0;c<m;c++)
{
for(d=0;d<q;d++)
{
 for(k=0;k<p;k++)
{                             
 sum = sum + first[c][k] * second[k][d];
 }
  multiply[c][d] = sum;
sum =0;
}
}

 printf("product of the matrix:\n");
 
 for(c=0;c<m;c++)
{
 for(d=0;d<q;d++)
  printf("%d\t",multiply[c][d]);
  printf("\n");
}
}                             
return 0;
}

```

**Output:-**

```
Enter the number of rows and column of first matrix:
2 2
Enter elements of first matrix:
3 4
5 6
Enter the number of rows and columns of second matrix:
2 2
Enter the elements of second matrix:
1 2
3 4
product of the matrix:
15      22
23      34
```
