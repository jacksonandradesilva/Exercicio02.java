package sala;
import java.util.Scanner;
import java.util.Locale;

public class problemaexemplo {
	

	public static void main(String[] args) {
		
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner (System.in);
		
		int minuto;
		double conta = 50.0;
		
		System.out.println("Digite valor em minutos:");
		minuto = sc.nextInt();
		
		if (minuto > 100) {
			conta += (minuto - 100)*2.0;
					
		}
		
		System.out.printf("valor da conta= %.2f%n", conta);
		
		
		
		
		
		
		
		
		
		
		
		sc.close();
	}

}
