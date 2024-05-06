# Semana-16---Arreglos
La actividad la cual realizamos en clase fue obtener los arreglos los cuales le teniamos que hacer al script para que este sea mas simplificado y tenga menor derivadas.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Runtime.Remoting.Proxies;
using System.Text;
using System.Threading.Tasks;

namespace S16___AAA_1318424
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //inicio
            string[] estudiante = new string[5];

            estudiante[0] = "JUAN";
            estudiante[1] = "PEDRO";
            estudiante[2] = "LUISA";
            estudiante[3] = "ADRIANA";
            estudiante[4] = "SOFIA";

            int[] nota = new int[5];
            nota[0] = (88);
            nota[1] = (75);
            nota[2] = (96);
            nota[3] = (77);
            nota[4] = (59);


            int promedio = 0;
            int suma = 0;

            for(int i = 0; i<5; i++) 
            {
                suma = suma + nota[i]
    ;            }
            promedio = suma / 5;

            for (int i = 0; i<5; i++)
            {
                Console.WriteLine("" + estudiante[i] + "-" + nota[i]+".");
            }
            Console.WriteLine("El promedio es: " + promedio);

            Console.ReadKey();


        }
    }
}
