# 1.-Suma-y-resta
git clone https://github.com/AxlZapata/1.-Suma-y-resta.git
cd 1.-Suma-y-resta
touch 1.-Suma-y-resta.java
import java.util.Scanner;

public class  1.-Suma-y-resta{

    // Método para sumar dos números
    public static int suma(int a, int b) {
        return a + b;
    }

    // Método para restar dos números
    public static int resta(int a, int b) {
        return a - b;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Solicitar al usuario los números
        System.out.print("Ingresa el primer número: ");
        int num1 = scanner.nextInt();
        System.out.print("Ingresa el segundo número: ");
        int num2 = scanner.nextInt();

        // Mostrar resultados
        System.out.println("La suma de " + num1 + " y " + num2 + " es: " + suma(num1, num2));
        System.out.println("La resta de " + num1 + " y " + num2 + " es: " + resta(num1, num2));

        scanner.close();
    }
}
