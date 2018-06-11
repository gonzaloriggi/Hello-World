# Hello-World
ASP.NET Core project
using System;

namespace QuestionAnswer
{
  class Program
  {
    static vois Main(String[] args)
    {
        Console.WriteLine("\nCould you please provide me your name? ");
        var name = Console.ReadLine();
        var date = DateTime.Now;
        Console.WriteLine($"\nHi!, {name}. Date:{date:d} at {date:t}!");
        Console.Write("\nPlease press any key to close this application");
        Console.ReadKey(true);
    }
  }
