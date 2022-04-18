# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Step1:
Start

Step2:
Create a class and declare two variable with string datatype

Step3:
Loop over the entire string and reverse it

Step4:
Use if condition to check whether the string and the reversed string is equal or not

Step5:
print palindrome if it's equal else print not a palindrome.

Step6:
stop
## Program:
```
using System;
namespace palindrome
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter string");
            s = Console.ReadLine();
            s=s.ToLower();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i];
            }
            if (revs == s)
            {
                Console.WriteLine("String is Palindrome");
            }
            else
            {
                Console.WriteLine("String is not Palindrome");
            }
        }
    }
}
```

## Output:

![c#(2)](https://user-images.githubusercontent.com/75235233/163826396-b3087162-d1af-4a95-9045-40ce4d1ac05c.png)

![c#(3)](https://user-images.githubusercontent.com/75235233/163826414-20765532-46d1-48e8-9d98-79fdea1f8e73.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
