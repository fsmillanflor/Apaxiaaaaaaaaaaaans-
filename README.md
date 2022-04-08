# Apaxiaaaaaaaaaaaans-

using System;

namespace Apaxians_
{
    class Program
    {
        static void Main(string[] args)
        {
            //Declared variable
            string name = Console.ReadLine();//Read input
            string last = "";
            //Range variable x
            for (int x = 0; x < name.Length - 1; x++)
                if (name[x] != name[x + 1])
                    last += name[x];
            {
                Console.WriteLine(last + name[name.Length - 1]);//Show the final name
            }
        }
    }
}
