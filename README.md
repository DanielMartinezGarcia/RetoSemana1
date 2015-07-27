# RetoSemana1
using System;

namespace RetoUno
{
	class MainClass
	{
		public static void Main (string[] args)
		{
			string TipoDato;

			Console.WriteLine ("Bienvenido, Escriba el tipo de dato");
			TipoDato = Console.ReadLine();

			switch (TipoDato) 
			{
			   
			case "byte":
				Console.WriteLine ("El Tamaño es igual a 8 bits y el rango es de 0 a 255");
				break;

			case "sbyte":
				Console.WriteLine ("El Tamaño es igual a 8 bits y el rango es de -128 a 127");
				break;

			case "int":
				Console.WriteLine ("El Tamaño es igual a 32 bits y el rango es de -2.147.483.648 a 2.147.483.647");
				break;

			case "uint":
				Console.WriteLine ("El Tamaño es igual a 32 bits y el rango es de 0 a 4294967295");
				break;

			case "short":
				Console.WriteLine ("El Tamaño es igual a 16 bits y el rango es de -32.768 a 32.767");
				break;

			case "ushort":
				Console.WriteLine ("El Tamaño es igual a 16 bits y el rango es de 0 a 65535");
				break;

			case "long":
				Console.WriteLine ("El Tamaño es igual a 64 bits y el rango es de -922337203685477508 a 922337203685477507");
				break;

			case "ulong":
				Console.WriteLine ("El Tamaño es igual a 64 bits y el rango es de 0 a 18446744073709551615");
				break;

			case "float":
				Console.WriteLine ("El Tamaño es igual a 32 bits y el rango es de 3,402823e38 a 3,402823e38");
				break;

			case "double":
				Console.WriteLine ("El Tamaño es igual a 64 bits y el rango es de -1,79769313486232e308 a 1,79769313486232e308");
				break;

			case "char":
				Console.WriteLine ("El Tamaño es igual a 16 bits y el rango es de Símbolos Unicode utilizados en el texto");
				break;

			case "bool":
				Console.WriteLine ("El Tamaño es igual a 8 bits y el rango es de true or false");
				break;

			case "decimal":
				Console.WriteLine ("El Tamaño es igual a 128 bits y el rango es de ±1.0 × 10e−28 a ±7.9 × 10e28");
				break;



				default:
				break;
			}

		}
	}
}
