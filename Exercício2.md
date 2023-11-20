import java.util.Scanner;

public class Exercício_2 {

    public static void main(String[] args) {
    
        Scanner in = new Scanner(System.in);
        
int[] A = new int[5];

for (int i = 0; i < 5; i++) {

            System.out.print("Informe o elemento " + (i + 1) + ": ");
            
            A[i] = in.nextInt();
}
for (int i = 0; i < A.length; i++) {

            System.out.println("Tabuada de " + A[i] + ":");
            for (int j = 1; j <= 10; j++) {
                int resultado = A[i] * j;
                System.out.println(A[i] + " x " + j + " = " + resultado);
            }
            System.out.println();
        in.close();
    }
    }
}
