# java02

import java.util.Scanner;

public class time {
 public	String nome;
 public String zagueiro;
 public	String lateral;
 public	String volante;
 public	 String meia;
 public	String atacante;
	
	Scanner entrada = new Scanner(System.in);
	
	 
	  
	
	  void  escalacao(){
		  System.out.println("qual seu time " + nome);
		  nome = entrada.nextLine();
		  System.out.println("Digite o nome do zagueiro:  " + zagueiro);
		  zagueiro = entrada.nextLine();
		  System.out.println("Digite o nome do lateral:  " + lateral);
		  lateral =  entrada.nextLine();
		  System.out.println("Digite o nome do volante:  " + volante);
		  volante =  entrada.nextLine();
		  System.out.println("Digite o nome do meia: " + meia);
		  meia = entrada.nextLine();
		  System.out.println("Digite o nome do atacante: " +atacante);
		  atacante = entrada.nextLine();
		  
