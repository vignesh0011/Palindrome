# Palindrome
## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step1:
Start

### Step2:
Create a class and declare two variable with string datatype

### Step3:
Loop over the entire string and reverse it

### Step4:
Use if condition to check whether the string and the reversed string is equal or not

### Step5:
print palindrome if it's equal else print not a palindrome.

### Step6:
stop
<br/>

## Program:
```c#

using System;
namespace palindrome
{
    class Pals
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter any string");
            s = Console.ReadLine();
            s=s.ToLower();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i];
            }
            if (revs == s)
            {
                Console.WriteLine("{0} is Palindrome", revs);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", s);
            }
        }
    }
}
```
## Output:
![image](https://github.com/vignesh0011/Palindrome/assets/53014593/0353b140-30bd-47c8-8545-27163193e823)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
