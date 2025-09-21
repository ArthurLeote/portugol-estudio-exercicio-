programa
{
	funcao inicio()
	{

		inteiro opcao

		faca {

			escreva("\n--- Menu de Opções ---\n")
			escreva("1. Média aritmética\n")
			escreva("2. Média ponderada\n")
			escreva("3. Sair\n")
			escreva("-----------------------\n")
			escreva("Digite a opção desejada: ")
			leia(opcao)
			escreva("\n")
	
			escolha (opcao)	{		
				caso 1:
					real nota1, nota2, media
					escreva("-> Cálculo da Média Aritmética <-\n")
					escreva("Digite a primeira nota: ")
					leia(nota1)
					escreva("Digite a segunda nota: ")
					leia(nota2)

					media = (nota1 + nota2) / 2.0
					
					escreva("A média aritmética é: ", media, "\n")
					pare
	
				caso 2:
					real n1, n2, n3, p1, p2, p3, mediaPond
					escreva("-> Cálculo da Média Ponderada <-\n")
					
					escreva("Digite a primeira nota: ")
					leia(n1)
					escreva("Digite o peso da primeira nota: ")
					leia(p1)

					escreva("Digite a segunda nota: ")
					leia(n2)
					escreva("Digite o peso da segunda nota: ")
					leia(p2)

					escreva("Digite a terceira nota: ")
					leia(n3)
					escreva("Digite o peso da terceira nota: ")
					leia(p3)

					se ((p1 + p2 + p3) != 0.0) {
						mediaPond = (n1*p1 + n2*p2 + n3*p3) / (p1 + p2 + p3)
						escreva("A média ponderada é: ", mediaPond, "\n")
					} 
          senao {
						escreva("Erro: A soma dos pesos não pode ser zero.\n")
					}
					pare 
	
				caso 3:
					escreva("Encerrando o programa...\n")
					pare
	
				caso contrario:
					escreva("Opção inválida! Por favor, digite 1, 2 ou 3.\n")
					pare
			}
		}
		enquanto (opcao != 3) 
	}
}