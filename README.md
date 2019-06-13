# Potencia-o

//POTENCIAÇÂO
package javaapplication2;

import java.util.Scanner;

public class JavaApplication2 {

    public static void main(String[] args) {

        Scanner leia = new Scanner(System.in);

        int base = 0;
        int potencia = 0;
        int resultado = 1;

        System.out.println("Informe o número da base: ");
        base = leia.nextInt();
        System.out.println("Informe o número da potencia: ");
        potencia = leia.nextInt();

        if (base == 0 | potencia == 0) {
            System.out.println("O resultado dessa potencia é 0");
        } else {
            for (int i = 0; i < potencia; i++) {
                resultado = base * resultado;
            }
            System.out.println(resultado);

        }

    }
}
