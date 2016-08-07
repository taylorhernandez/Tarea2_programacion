using System;

public class mayusculas
{
    static void Main(string[] args)
    {
        string palabra;
        int contador1 = 0, contador2 = 0, consonantes;
        Console.WriteLine("Escribe una palabra");
        palabra = Console.ReadLine();
        for (int i = 0; i < palabra.Length; i++)
        {
            contador1++;
        }
        for (int i = 0; i < palabra.Length; i++)
        {
            if ((palabra[i] == 'a') || (palabra[i] == 'e') || (palabra[i] == 'i') || (palabra[i] == 'o') || (palabra[i] == 'u'))
            {
                contador2++;
            }
        }
        consonantes = contador1 - contador2;
        Console.WriteLine ("la palabra tiene:  "+contador2 + " vocales" );
        Console.ReadLine ();
    }
}
