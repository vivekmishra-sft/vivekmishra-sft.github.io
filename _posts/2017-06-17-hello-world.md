# Hello World in C#

This is the first program in C# that is usually written by every programmer on the earth.

    using System;
    
    public namespace Example
    {
        public class Program
        {
            //The entry point for a program. This must be static.
            public static void Main(string[] args)
            {
                Console.WriteLine("Hello World!");
            }
        }
    }

This program contains very little amount of code, but there are number of concepts that are used inside this small program. Here are all the features of C# language that are used in this program:

* Class
* Static keyword
* Using clause
* Namespace
* Function/Methods in C#

### Class
A class is feature of object oriented programming methodology. Classes acts as a template that are used for the creation of objects. All the objects created from a class will have the same features as the class, but the data contained by each object may differ. In the above program the class name is `Program`. We will see more about the classes in more detail in the upcoming tutorials.

### Static keyword
The static keyword in the program is used to mark the `Main()` method as static. When we use static keyword, we instruct the compiler that that member can be shared by all. The behavior of static method will be same for all the caller. Here, it is by the design of language that you need to make the `Main()` method static. If you forget to mark the `Main()` as static, the program will give you a compile time error. Later, you will see that we can make methods without marking them as static.

### Using clause
In the start of the program, you can see `using System;` statement. Here `System` is a namespace and the statement tell that we want to use it in our program. Mostly, a namespce contains classes that we want to use. `System` is one of most important namespace that contains a lot of classes. One of them is the `Console` class that contains methods to display and take input from the command line.

### Namespace
A namespace is a way to remove naming conflicts between the classes. The .Net framework contains thousands of classes and we as a developer also creates classes on regular basis. Somehow it is possible that in a program we may end up having same names for the classes. Every class name must be unique.


