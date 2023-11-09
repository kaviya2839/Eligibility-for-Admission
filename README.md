## EX 01 Eligibility-for-Admission
## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
Step 1 : Import the 'System' namespace to use the classes present in the 'System' namespace.

Step 2 : Declare the Main method.

Step 3 : Declare name variable in string format and marks variable in integer format.

Step 4 : Using " Console.Write " print the statement and get the input from user using " Console.ReadLine " .

Step 5 : Add the 3 subject marks and store it in sum_of_three. Add the marks of physics and maths and store it in sum_of_two.

Step 6 : Using Nested if loop check whether the student is eligible or not eligible for engineering admission with the conditions given.

Step 7 : Print the result.

## Program:
```
Name : KAVIYA SHREE S
Reg no : 212222110018

using System;

namespace EngineeringAdmission
{
    class Program
    {
        static void Main(string[] args)
        {
            int maths, physics, chemistry;
            Console.WriteLine("Welcome to Engineering Admission Eligibility Checker");

            Console.Write("Enter Math marks: ");
            maths = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Physics marks: ");
            physics = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Chemistry marks: ");
            chemistry = Convert.ToInt32(Console.ReadLine());

            int totalMarks = maths + physics + chemistry;

            if (maths >= 65 && physics >= 55 && chemistry >= 50)
            {
                if (totalMarks >= 180)
                {
                    Console.WriteLine("Congratulations! You are eligible for admission.");

                }
                else
                {
                    Console.WriteLine("Sorry, you are not eligible for admission.");

                }
            }
        }
    }
}

```




## Output:
![exp01](https://github.com/arunkumarsukdevchavan/Eligibility-for-Admission/assets/118343978/529bef16-7733-423f-8d82-7ba9870b2ee0)
![exp01(01)](https://github.com/arunkumarsukdevchavan/Eligibility-for-Admission/assets/118343978/24fd6204-78b0-4f91-bf5a-bde473d9cf5f)

## Result:
Thus a C# program to find the eligibility for admission to an engineering course is written and executed.

