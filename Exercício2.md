import java.util.Scanner;

public class Exercicio2 {

	public static void main(String[] args) {
 
		Scanner in = new Scanner (System.in);
  
		final int TAM=10;
  
		int i, a[], b[], c[];
		a= new int [TAM];
		b= new int [TAM];
		c= new int [TAM];
		for (i=0; i<TAM; i++) {
			 System.out.println("insira o "+(i+1)+ "o. valor do Vetor A");
			 a[i]=in.nextInt();
			 System.out.println("insira o "+(i+1)+ "o. valor do vetor B");
			 b[i]=in.nextInt();
			 c[i]=a[i]+b[i];
			}
		System.out.print("A[] = [");
		for (i=0;i<TAM;i++) {
			System.out.print(a[i]+ " ");
		}
		System.out.println("]");
		System.out.print("B[] = [");
		for (i=0;i<TAM;i++) {
			System.out.print(b[i]+ " ");
		}
		System.out.println("]");
		System.out.print("C[] = [");
		for (i=0;i<TAM;i++) {
			System.out.print(c[i]+ " ");
		}
		System.out.print("]");
		in.close();
	}
 }
