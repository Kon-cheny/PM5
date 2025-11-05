using System;
class Program
{
    static void Main()
    {
        string a = "Hello";
        string b = "hello";
        string c = "Hello World";
        
        // Compare() - сравнение строк
        Console.WriteLine(string.Compare(a, b));
        
        // Equals() - проверка равенства
        Console.WriteLine(a.Equals(b));
        
        // CompareOrdinal() - сравнение по кодам
        Console.WriteLine(string.CompareOrdinal(a, b));
        
        // IndexOf() - поиск позиции
        Console.WriteLine(c.IndexOf("World"));
        
        // Contains() - проверка наличия
        Console.WriteLine(c.Contains("Hello"));
        
        // Операторы == и !=
        Console.WriteLine(a == b);
        Console.WriteLine(a != b);
    }
}
// я устал хочу отдахнуть 
