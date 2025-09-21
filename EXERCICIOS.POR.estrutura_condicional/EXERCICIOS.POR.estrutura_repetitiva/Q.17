programa
{
	funcao inicio()
	{
		inteiro canal
		inteiro pessoas

		inteiro audienciaCanal4 = 0
		inteiro audienciaCanal5 = 0
		inteiro audienciaCanal7 = 0
		inteiro audienciaCanal12 = 0

		inteiro totalAudiencia = 0
		
		escreva("--- Pesquisa de Audiência de TV ---\n")
		escreva("Para encerrar, digite 0 para o número do canal.\n\n")

		faca	{
			escreva("Digite o número do canal (4, 5, 7, 12): ")
			leia(canal)
	
			se (canal != 0)	{
				escreva("Digite o número de pessoas assistindo: ")
				leia(pessoas)

				escolha (canal)	{
					caso 4:
						audienciaCanal4 = audienciaCanal4 + pessoas
						pare
					caso 5:
						audienciaCanal5 = audienciaCanal5 + pessoas
						pare
					caso 7:
						audienciaCanal7 = audienciaCanal7 + pessoas
						pare
					caso 12:
						audienciaCanal12 = audienciaCanal12 + pessoas
						pare
					caso contrario:
						escreva("Atenção: Canal inválido. Dado não computado.\n")
				}
				escreva("----------------------------------------\n")
			}
		}	enquanto(canal != 0)

		totalAudiencia = audienciaCanal4 + audienciaCanal5 + audienciaCanal7 + audienciaCanal12

		escreva("\n--- Resultado Final da Pesquisa ---\n")

		se (totalAudiencia > 0) {	
			real p4 = (audienciaCanal4 / totalAudiencia) * 100.0
			real p5 = (audienciaCanal5 / totalAudiencia) * 100.0
			real p7 = (audienciaCanal7 / totalAudiencia) * 100.0
			real p12 = (audienciaCanal12 / totalAudiencia) * 100.0
			
			escreva("Total de pessoas assistindo TV: ", totalAudiencia, "\n\n")
			escreva("Porcentagem de audiência por canal:\n")
			escreva("Canal 4: ", p4, "%\n")
			escreva("Canal 5: ", p5, "%\n")
			escreva("Canal 7: ", p7, "%\n")
			escreva("Canal 12: ", p12, "%\n")
		}
		senao	{
			escreva("Nenhum dado de audiência foi registrado.\n")
		}
	}
}