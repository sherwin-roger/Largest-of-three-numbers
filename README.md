# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
```
using System;
namespace Sherwin{
    class sheru{
        
        static void Main(string[] args){
            void Multiply(int a,int b,int c){
                if(a>b &&a>c){
                    Console.Write("a is big");
                }else if(b>a && b>c){
                    Console.Write("b is big");
                }else
                {
                    Console.Write("C is big");
                }
            }
            int a = 100;
            int b = 200;
            int c = Convert.ToInt32(Console.ReadLine());
            Multiply(a,b);
            Add(a,b)
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/75235128/163684363-75af59b7-4c14-43cf-9c1c-2daa71cb7dd6.png)
## Result:
Thus the C# program to find the largest of three numbers is executed successfully
