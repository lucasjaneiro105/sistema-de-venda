package projetos_java;

import java.text.DecimalFormat;
import java.util.Scanner;

public class desconto_produto {

	public static void main(String[] args) {
		// variaveis 
		double total, totalDesconto, desconto, valorPago, troco; 
		
	    // objetos 
	    Scanner teclado = new Scanner(System.in);
	    DecimalFormat formatador = new DecimalFormat("#0.00");
	    
	    // primeira entrada
	    System.out.println("Produto");
	    System.out.print("Valor Total: " );
	    total = teclado.nextDouble();
	    System.out.print("Desconto: " );
	    desconto = teclado.nextDouble();
	    
	    // processamento 
	    totalDesconto = total - (desconto * total) / 100; 
	    
	    //primeira saida 
	    System.out.println("Total com Desconto: R$ " + formatador.format(totalDesconto));
	    
	    //segunda entrada 
	    System.out.println("////////////////");
	    System.out.print("valor pago:");
	    valorPago = teclado.nextDouble();
	    
	    // processamento 
	    troco = valorPago - totalDesconto;
	    
	    // segunda saida 
	    System.out.println("Troco: R$ " + formatador.format(troco));
	    
        teclado.close();

	}

}
