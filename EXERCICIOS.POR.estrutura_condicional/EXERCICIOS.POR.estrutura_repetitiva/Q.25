programa
{
	funcao inicio()
	{
		inteiro codigoCliente, tipoInvestimento
		real valorInvestido
		real totalInvestido = 0.0
		real totalJuros = 0.0
		
		escreva("--- Cálculo de Rendimento Mensal ---\n")
		escreva("Tipos de Investimento:\n")
		escreva("1 - Poupança (1,5%)\n")
		escreva("2 - Poupança Plus (2%)\n")
		escreva("3 - Fundos de Renda Fixa (4%)\n")
		escreva("----------------------------------------\n")
		escreva("Para encerrar, digite um código de cliente menor ou igual a 0.\n\n")
		escreva("Digite o código do cliente: ")
		  leia(codigoCliente)

		enquanto (codigoCliente > 0) {
			escreva("Digite o tipo de investimento (1, 2 ou 3): ")
			leia(tipoInvestimento)
			escreva("Digite o valor investido: R$ ")
			leia(valorInvestido)

			real rendimentoMensal = 0.0
	
			escolha (tipoInvestimento) {
				caso 1: 
					rendimentoMensal = valorInvestido * 0.015
					pare
				caso 2: 
					rendimentoMensal = valorInvestido * 0.02
					pare
				caso 3: 
					rendimentoMensal = valorInvestido * 0.04
					pare
				caso contrario:
					escreva("-> Tipo de investimento inválido! Rendimento não calculado.\n")		
					pare
			}

			escreva("-> Rendimento mensal do cliente ", codigoCliente, ": R$ ", rendimentoMensal, "\n")
			escreva("----------------------------------------\n")

			totalInvestido = totalInvestido + valorInvestido
			totalJuros = totalJuros + rendimentoMensal

			escreva("Digite o código do próximo cliente: ")
			leia(codigoCliente)
		}

		escreva("\n========= Relatório Final da Agência =========\n")
		
		se(totalInvestido > 0.0) {
			escreva("Valor total investido: R$ ", totalInvestido, "\n")
			escreva("Valor total de juros pagos: R$ ", totalJuros, "\n")
		}
		senao {
			escreva("Nenhum investimento foi registrado.\n")
		}
	}
}