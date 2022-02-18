# program-to-print-even-numbers-using-break-
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

    public class Program 
    {
        public static void Main()
        {
			int i;
			for(i=1;i<=10;i++)
			{
				if(i%2==0)
				{
					Console.WriteLine(i);
					if(i==6)
					{
					break;
					}
				}
			}
        }
    }
}
