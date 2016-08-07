using System;
namespace ConsoleApplicationCS
{
    class inverso
    {
        static void Main(string[] args)
        {
            int n, decena, unidad, inverso;
            do
            {
                Console.Clear();
                Console.WriteLine("Ingrese número de dos cifras");
                n = Convert.ToInt32(Console.ReadLine());
            } while (n < 10 || n >= 100);
            decena = n / 10;
            unidad = n % 10;
            inverso = unidad * 10 + decena;
            Console.WriteLine("El inverso de {0} es {1}", n, inverso);
            Console.ReadKey();
        }

    }


}
