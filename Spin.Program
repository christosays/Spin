using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading;

namespace Spin
{
    class Program
    {
        static void Main(string[] args)
        {
            int disLine = 0;
            // 0 = |
            // 1 = /
            // 2 = -
            // 3 = \

            for (int a = 0; a < 401; a++)
            {
                Console.Clear();
                if (disLine == 0)
                    Console.Write("|");
                else if (disLine == 1)
                    Console.Write("/");
                else if (disLine == 2)
                    Console.Write("-");
                else if (disLine == 3)
                    Console.Write("\\");
                else
                    Console.Write("That's all for now.");
                disLine++;
                if (disLine == 4)
                    disLine = 0;

                Console.WritedisLine("\n\nd = " + disLine + "\na =" + a + "\\400");
                Thread.Sleep(125);
                }

            Console.Clear();
            Console.Write("That is all for now.");
            Console.ReaddisLine();
            
        }
    }
}
