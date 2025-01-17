Even or odd Programe


using System;

class Program
{
    static void Main()
    {
        // Prompt the user to enter a number
        Console.Write("Enter a number: ");
        
        // Read the user input
        int number=int.Parse(Console.ReadLine());

        // Check if the number is even or odd
        if (number % 2 == 0)
        {
            Console.WriteLine($"{number} is even.");
        }
        else
        {
            Console.WriteLine($"{number} is odd.");
        }
    }
}
