programa
{
	funcao inicio()
	{
		inteiro idade
		inteiro somaIdades = 0
		inteiro contadorIdades = 0
		real media = 0.0

		escreva("Digite várias idades. Para finalizar e calcular a média, digite 0.\n")

		faca {
			escreva("Digite uma idade: ")
			leia(idade)

			se (idade != 0)	{
				somaIdades = somaIdades + idade
				contadorIdades = contadorIdades + 1
			}
		}	enquanto (idade != 0)


		se (contadorIdades > 0) {

			media = somaIdades / contadorIdades

			escreva("\n--- Resultado ---\n")
			escreva("Foram digitadas ", contadorIdades, " idades.\n")
			escreva("A média das idades é: ", media, "\n")
		}
		senao	{
			escreva("\nNenhuma idade válida foi inserida.\n")
		}
	}
}