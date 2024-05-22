# C--basics-
This all about C# basic programming 
Getting Started with C# Programming
C# is a versatile and powerful programming language developed by Microsoft. It's widely used for building various types of applications, including web applications, desktop software, games, mobile apps, and more. In this article, we'll cover some fundamental concepts to help you get started with C# programming.

1. Variables and Data Types
Variables are used to store data in C#. C# supports various data types such as integers, floating-point numbers, characters, booleans, and strings.

csharp
Copy code
int age = 25;
float height = 5.9f;
char grade = 'A';
bool isStudent = true;
string name = "John";
2. Control Structures
C# provides control structures like if, else, switch, for, while, and do-while for decision-making and looping.

csharp
Copy code
if (age >= 18)
{
    Console.WriteLine("You are an adult.");
}
else
{
    Console.WriteLine("You are a minor.");
}

for (int i = 0; i < 5; i++)
{
    Console.WriteLine(i);
}

while (isStudent)
{
    Console.WriteLine("You are a student.");
    isStudent = false;
}
3. Functions (Methods)
Functions are blocks of code that perform a specific task. C# allows you to define functions with or without parameters and return values.

csharp
Copy code
// Function without parameters and return value
void SayHello()
{
    Console.WriteLine("Hello!");
}

// Function with parameters and return value
int Add(int a, int b)
{
    return a + b;
}
4. Classes and Objects
C# is an object-oriented language, so it revolves around classes and objects. A class is a blueprint for creating objects, and an object is an instance of a class.

csharp
Copy code
class Person
{
    public string Name { get; set; }
    public int Age { get; set; }

    public void DisplayInfo()
    {
        Console.WriteLine($"Name: {Name}, Age: {Age}");
    }
}

// Creating an object of the Person class
Person person1 = new Person();
person1.Name = "Alice";
person1.Age = 30;
person1.DisplayInfo();
5. Arrays
Arrays are used to store multiple values of the same data type in C#. You can create and manipulate arrays easily.

csharp
Copy code
int[] numbers = { 1, 2, 3, 4, 5 };
Console.WriteLine(numbers[0]);  // Outputs: 1

// Loop through the array
foreach (int num in numbers)
{
    Console.WriteLine(num);
}
These are just some basic concepts to get you started with C# programming. As you delve deeper into C#, you'll encounter more advanced topics and features that will help you build powerful and robust applications.
