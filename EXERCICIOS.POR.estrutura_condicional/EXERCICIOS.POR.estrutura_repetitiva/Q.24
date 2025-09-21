programa
{
	funcao inicio()
	{

		inteiro valor
		inteiro maiorValor = 0
		inteiro menorValor = 0
		logico primeiroValorValido = verdadeiro
		
		escreva("--- Maior e Menor Valor de um Conjunto ---\n")
		escreva("Digite valores inteiros e positivos.\n")
		escreva("Para valores negativos, uma mensagem será exibida.\n")
		escreva("Para encerrar, digite 0.\n\n")

		faca {
			escreva("Digite um valor: ")
			leia(valor)
	
			se (valor > 0) {	
				se (primeiroValorValido) {		
					maiorValor = valor
					menorValor = valor
		
					primeiroValorValido = falso
				}
				senao {			
					se (valor > maiorValor)	{
						maiorValor = valor
					}
					se (valor < menorValor)	{
						menorValor = valor
					}
				}
			}

			senao se (valor < 0) {
				escreva("-> Mensagem: Valor negativo não é permitido. Tente novamente.\n")
			}	

		}	enquanto (valor != 0)

		escreva("\n========= Resultado =========\n")

		se (primeiroValorValido) {
			escreva("Nenhum valor positivo foi inserido para análise.\n")
		}
		senao	{
			escreva("O maior valor digitado foi: ", maiorValor, "\n")
			escreva("O menor valor digitado foi: ", menorValor, "\n")
		}
	}
}