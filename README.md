# alana-ted_moldura
área de uma moldura

package visao;
import java.util.Scanner;

public class Retangulo {
	 public static void main(String[] args) {
		 
		 Scanner entrada;
	        int lad1;
	        int lad2;
	        int per;
	        int area; 
	       
	        entrada = new Scanner(System.in);
	        
	        System.out.println("Informe o maior lado do ret:");
	        lad1 = entrada.nextInt();
	        System.out.println("Informe o menor lado do ret:");
	        lad2 = entrada.nextInt();
	        
	        area = lad1 * lad2;  //Cálculo da área
	        per = 2*lad1 + 2*lad2;  //Cálculo do perímetro
	        
	        System.out.println("A area do quadrado eh " + area + " unid. area");
	        System.out.println("O perimetro do quadrado eh " + per); 
	 }

}

