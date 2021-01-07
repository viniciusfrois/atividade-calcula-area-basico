<h2 align="center"> AtividadeCalculaArea  </h2>
<p align="center">Atividade Academica, resolvida por mim</p>

<h2 align="center"> Questão Proposta: </h2>
<p align="center"><image src="https://github.com/viniciusfrois/AtividadeCalculaArea/blob/main/Atividade6.JPG?raw=true"></p>

<h2 align="center"> Resolvido: </h2>

import java.util.Locale;<br>
import java.util.Scanner;

public class Atividade6 {

	public static void main(String[] args) {
		//variaveis
		Locale.setDefault(Locale.US);
		Scanner teclado = new Scanner (System.in);
		double a,b,c,triangulo,circulo,trapezio,quadrado,retangulo;
		
		//entradas
		System.out.println("Informe o valor de A:");
		a = teclado.nextDouble();
		System.out.println("Informe o valor de B:");
		b = teclado.nextDouble();
		System.out.println("Informe o valor de C:");
		c = teclado.nextDouble();
		
		//calculo
		triangulo = a * c / 2.00;
		circulo = 3.14159 * Math.pow(c, 2);
		trapezio = (a+b) / 2.0 * c;
		quadrado = b * b;
		retangulo = a * b;
		
		//saidas
		System.out.printf("TRIANGULO: %.3f%n", triangulo);
		System.out.printf("CIRCULO: %.3f%n", circulo);
		System.out.printf("TRAPEZIO: %.3f%n", trapezio);
		System.out.printf("QUADRADO: %.3f%n", quadrado);
		System.out.printf("RETANGULO: %.3f%n", retangulo);
		
		teclado.close();
		

	}

}
