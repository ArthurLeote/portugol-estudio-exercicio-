programa{
	inclua biblioteca Texto
	inclua biblioteca Matematica

	funcao inicio()	{

		inteiro total_sim = 0
		inteiro total_nao = 0
		inteiro mulheres_sim = 0
		inteiro total_homens = 0
		inteiro homens_nao = 0
		real percentagem_homens_nao = 0.0
		cadeia sexo, resposta

		escreva("--- Pesquisa de Mercado ---\n")


		para (inteiro i = 1; i <= 10; i++) {
			escreva("\n--- Entrevistado nº ", i, " ---\n")

			faca {
				escreva("Digite o sexo (F/M): ")
				leia(sexo)
				sexo = Texto.caixa_alta(sexo)
				se (sexo != "F" e sexo != "M") {
					escreva("Entrada inválida. Tente novamente.\n")
				}
			} enquanto (sexo != "F" e sexo != "M")

			faca {
				escreva("Gostou do produto? (S/N): ")
				leia(resposta)
				resposta = Texto.caixa_alta(resposta)
				se (resposta != "S" e resposta != "N") {
					escreva("Entrada inválida. Tente novamente.\n")
				}
			} enquanto (resposta != "S" e resposta != "N")

			se (resposta == "S") {
				total_sim = total_sim + 1
				se (sexo == "F") {
					mulheres_sim = mulheres_sim + 1
				}
			} 
      senao { 
				total_nao = total_nao + 1
				se (sexo == "M") {
					homens_nao = homens_nao + 1
				}
			}
		
			se (sexo == "M") {
				total_homens = total_homens + 1
			}
		}

		se (total_homens > 0) {
			percentagem_homens_nao = (homens_nao) / total_homens * 100.0
		}

		escreva("\n--- Resultados Finais da Pesquisa ---\n")
		escreva("Número de pessoas que responderam sim: ", total_sim, "\n")
		escreva("Número de pessoas que responderam não: ", total_nao, "\n")
		escreva("Número de mulheres que responderam sim: ", mulheres_sim, "\n")
		escreva("Porcentagem de homens que responderam não: ", Matematica.arredondar(percentagem_homens_nao, 2), "%\n")
	}
}