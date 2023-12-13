//quetion1
class Program

{

    static void Main()

    {

        int n = GenerateRandomNumber();

 

        Console.WriteLine($"The number is: {n}");

 

        DetermineAndPrintNumberType(n);

    }

 

    static int GenerateRandomNumber()

    {

     

        Random random = new Random(DateTime.Now.Millisecond);

        return random.Next(-10, 11);

    }

 

    static void DetermineAndPrintNumberType(int number)

    {

        string result = (number > 0) ? "positive" : (number < 0) ? "negative" : "zero";

        Console.WriteLine($"The number is {result}.");

    }

}


//question 2
class Program
{
    static void Main()
    {
        int n = GenerateRandomNumber();

        Console.WriteLine($"The number is: {n}");

        DetermineAndPrintNumberType(n);
    }

    static int GenerateRandomNumber()
    {
     
        Random random = new Random(DateTime.Now.Millisecond);
        return random.Next(-10, 11);
    }

    static void DetermineAndPrintNumberType(int number)
    {
        string result = (number > 0) ? "positive" : (number < 0) ? "negative" : "zero";
        Console.WriteLine($"The number is {result}.");
    }
}
//question 3
class Program
{
    static void Main()
    {
        int n = GenerateRandomNumber();

        Console.WriteLine($"The number is: {n}");

        DetermineAndPrintNumberType(n);
    }

    static int GenerateRandomNumber()
    {
     
        Random random = new Random(DateTime.Now.Millisecond);
        return random.Next(-10, 11);
    }

    static void DetermineAndPrintNumberType(int number)
    {
        string result = (number > 0) ? "positive" : (number < 0) ? "negative" : "zero";
        Console.WriteLine($"The number is {result}.");
    }
}
//question4
class Program
{
    static void Main()
    {
        int n = GenerateRandomNumber();

        Console.WriteLine($"The number is: {n}");

        DetermineAndPrintNumberType(n);
    }

    static int GenerateRandomNumber()
    {
     
        Random random = new Random(DateTime.Now.Millisecond);
        return random.Next(-10, 11);
    }

    static void DetermineAndPrintNumberType(int number)
    {
        string result = (number > 0) ? "positive" : (number < 0) ? "negative" : "zero";
        Console.WriteLine($"The number is {result}.");
    }
}
//question5
using System;

 

class Program

{

    static void Main()

    {

        string reversedString = ReverseString("C# is fun!");

        Console.WriteLine(reversedString);

    }

 

    static string ReverseString(string input)

    {

        char[] charArray = input.ToCharArray();

        Array.Reverse(charArray);

        return new string(charArray);

    }

}

//question 6
class Program
{
    static void Main()
    {
        int n = GenerateRandomNumber();

        Console.WriteLine($"The number is: {n}");

        DetermineAndPrintNumberType(n);
    }

    static int GenerateRandomNumber()
    {
     
        Random random = new Random(DateTime.Now.Millisecond);
        return random.Next(-10, 11);
    }

    static void DetermineAndPrintNumberType(int number)
    {
        string result = (number > 0) ? "positive" : (number < 0) ? "negative" : "zero";
        Console.WriteLine($"The number is {result}.");
    }
}


