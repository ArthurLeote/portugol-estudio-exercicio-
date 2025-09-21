programa
{
	funcao inicio()
	{
		inteiro voto
		inteiro votosCandidato1 = 0
		inteiro votosCandidato2 = 0
		inteiro votosCandidato3 = 0
		inteiro votosCandidato4 = 0
		inteiro votosNulos = 0
		inteiro votosBranco = 0
		
		escreva("--- Urna Eletrônica ---\n")
		escreva("Códigos de votação:\n")
		escreva("1, 2, 3, 4 = Voto para o respectivo candidato\n")
		escreva("5 = Voto Nulo\n")
		escreva("6 = Voto em Branco\n")
		escreva("------------------------------------\n")
		escreva("Para finalizar a votação, digite 0.\n\n")

		faca {
			escreva("Digite seu voto: ")
			  leia(voto)

			escolha(voto)	{
				caso 1:
					votosCandidato1 = votosCandidato1 + 1
					pare
				caso 2:
					votosCandidato2 = votosCandidato2 + 1
					pare
				caso 3:
					votosCandidato3 = votosCandidato3 + 1
					pare
				caso 4:
					votosCandidato4 = votosCandidato4 + 1
					pare
				caso 5:
					votosNulos = votosNulos + 1
					pare
				caso 6:
					votosBranco = votosBranco + 1
					pare
				caso 0:
					pare 
				caso contrario:
					escreva("-> Voto inválido. Tente novamente.\n")
					pare
			}
		}
		enquanto(voto != 0)		

		inteiro totalDeVotos = votosCandidato1 + votosCandidato2 + votosCandidato3 + votosCandidato4 + votosNulos + votosBranco
		
		escreva("\n========= Resultado da Eleição =========\n")

		se (totalDeVotos > 0) {
			real pNulos = 0.0
			real pBranco = 0.0
			pNulos = (votosNulos / totalDeVotos) * 100.0
			pBranco = (votosBranco / totalDeVotos) * 100.0

			escreva("Total de votos para o Candidato 1: ", votosCandidato1, "\n")
			escreva("Total de votos para o Candidato 2: ", votosCandidato2, "\n")
			escreva("Total de votos para o Candidato 3: ", votosCandidato3, "\n")
			escreva("Total de votos para o Candidato 4: ", votosCandidato4, "\n")			

			escreva("Total de votos nulos: ", votosNulos, "\n")
			escreva("Total de votos em branco: ", votosBranco, "\n\n")

			escreva("Porcentagem de votos nulos sobre o total: ", pNulos, "%\n")
			escreva("Porcentagem de votos em branco sobre o total: ", pBranco, "%\n")
		}
		senao	{
			escreva("Nenhum voto foi registrado.\n")
		}
	}
}