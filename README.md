# JAVA-INICIO

*SCANNER*
  
	O  (SCANNER)  é utilizada para obter as informações que os usuarios digitam no teclado, e armazenar essas informações dentro de uma variavel,   para que possa ser utilizada pelos programas.
	
*METODOS - NEXT*
	
	NextLine = O método nextLine em java está presente na classe Scanner e é usado para obter a entrada do usuário. Para usar este método, um objeto Scanner precisa ser criado. Este método pode ler a entrada até o final da linha.
	
	NextInt = O método nextInt é colocado na variável num1 utilizado pela atribuição (=). Seja o comando: soma = (num1 + num2); É uma instrução de atribuição, que através do sinal de igual (=), diz que a soma dos valores (num1 + num2) será guardada dentro da variável soma.
	
	NextDouble = O método nextDouble da classe Random retorna o próximo valor duplo pseudo-aleatório, uniformemente distribuído entre 0,0 e 1,0 da sequência deste gerador de números aleatórios. Parâmetros: a função não aceita nenhum parâmetro.
	
*LOCALE*

	Locale = Locale é usada para executar tarefas de localidade e fornece informações de localidade para o usuário.
	
*SYSTEM. OUT*

	O objeto (System). out é a saída padrão, que permite exibir as Strings no console (terminal) de comando quando o aplicativo de Java é executado.

*IMPORT*

	A instrução import tem como objetivo disponibilizar em uma classe, de um determinado pacote, o acesso a demais classes que estejam em pacotes diferentes, por isso importamos ela.
	
*IF-ELSE*
	A condicional if é uma estrutura condicional que executa a afirmação, dentro do bloco, se determinada condição for verdadeira. Se for falsa, executa as afirmações dentro de else.
	
	
			
			n = int(input("Digite um numero: "))

		if n % 2 == 0:  # se n é múltiplo de 2 então é par
		    print(n, "e' par")
		else:           # senão o número é ímpar, não precisa fazer outro teste!
		    print(n, "e' impar")

		print("fim.")

_______________________________________________________________________________________________________________________________________________________________________
	
			nota = int(input("Digite uma nota: "))

		if nota < 30:
		    print("Reprovado")
		else:
		    if nota < 50:
			print("Recuperacao")
		else:
			print("Aprovado")

		print("fim.")
		
_______________________________________________________________________________________________________________________________________________________________________		
		int minutos = sc.nextInt();

		double conta = 50.0;
		if (minutos > 100) {
		    conta += (minutos - 100) * 2.0; //*conta += () ou conta = conta + ()
		}

		System.out.printf("Valor da conta = R$ %.2f%n", conta);

		sc.close();

