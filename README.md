# ArreglosJavayPython
Un arreglo es un tipo de datos que contiene varios elementos de un mismo tipo. Cada elemento tiene asociado un índice, y puede ser tratado como si fuera una variable. La cantidad de elementos que tiene un arreglo es fija, y no puede cambiar durante la ejecución del programa.

Codigo Java 

package tablamultiplicar;
import java.util.Scanner;
public class TablaMultiplicar {
public static void main(String[] args) {
        Scanner obtenerNumero = new Scanner(System.in);
        int numero,i,j;
         System.out.print("indica la tabla de multiplicar: ");
        numero = obtenerNumero.nextInt();
         for(i = 1; i<=numero; i++)
        {
            for(j = 1; j <= 12; j++)
            {
                System.out.println(i + " X " + j + " = " + i*j);
            }
            System.out.println();
        }
    }
}

CODIGO PYTHON

matriz=list(range (5,21,3))
list (range (5,10))
