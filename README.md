# Idadeemdias
Exercicio07 idade em dias

package exercicios;

import java.util.Scanner;

/*
 * 
 * Faca um algortimo que leia  a idade de uma pessoa expressa em anos , meses e dias
 * e escreva a idade dessa pessoa expressa apenas em dias. Considerar ano com 365 dias e mes com 30 dias.
 */

public class Exercicio07 {

	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
	
		//byte ano;
	  //  byte dias;
	//	byte mes;
	
		System.out.println("Informe sua idade em anos: ");
		byte anos = scanner.nextByte();
		
		System.out.println("Informe a quantidade de meses depois do seu aniversario : ");
		byte meses = scanner.nextByte();
		
		System.out.println("informe a quantidade de dias que passou do seu mesversario:");
		byte dia = scanner.nextByte();

		int total =anos*365+meses*30+dia;
		
		
		System.out.println("A idade dessa pessoa em dias seria de : " + total);
scanner.close();
	}

}

