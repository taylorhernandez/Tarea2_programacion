using System;

public class mayusculas
{

    public static void Main()
    {
        Console.WriteLine("Ingrese palabra:");
        string palabra = Console.ReadLine(); 

        Console.WriteLine("El texto es: {0}",
          palabra);
        
        Console.WriteLine("En mayúsculas: {0}",
          palabra.ToUpper());
      

                Console.ReadLine();
    }
  }
