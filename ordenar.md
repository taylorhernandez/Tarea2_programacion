using System;

class alfabeticamente
    {
        static void Main(string[] args)
        {                       
            Console.WriteLine("Ingrese palabra:");
            string palabra = Console.ReadLine(); 
            char[] arregloCaracteres = new char[palabra.Length]; 
            Console.WriteLine("Palabra ingresada: {0}",palabra);
            palabra.CopyTo(0, arregloCaracteres, 0, arregloCaracteres.Length); 
            Array.Sort(arregloCaracteres);
            Console.WriteLine("Cadena ordenada por caracteres: ");
            for(int i = 0; i < arregloCaracteres.Length; i++) 
                Console.Write(arregloCaracteres[i]);
            Console.ReadLine();
           
        }
    }  
