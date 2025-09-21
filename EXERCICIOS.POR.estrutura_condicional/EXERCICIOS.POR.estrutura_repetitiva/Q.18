programa
{
	funcao inicio()
	{

		inteiro idade
		caracter sexo
		real salario
		real somaSalarios = 0.0
		real mediaSalarios = 0.0
		inteiro contadorPessoas = 0
		inteiro maiorIdade = 0
		inteiro menorIdade = 0
		inteiro mulheresSalarioBaixo = 0
		real menorSalario = 0.0
		inteiro idadeMenorSalario = 0
		caracter sexoMenorSalario = ' '

		escreva("--- Início da Pesquisa ---\n")
		escreva("Para finalizar, digite uma idade negativa.\n\n")
		escreva("Digite a idade: ")
		leia(idade)

		enquanto (idade >= 0)	{

			escreva("Digite o sexo (M/F): ")
			leia(sexo)
			escreva("Digite o salário: R$ ")
			leia(salario)
			escreva("------------------------------------\n")

			contadorPessoas = contadorPessoas + 1

			somaSalarios = somaSalarios + salario

			se (contadorPessoas == 1)	{
				maiorIdade = idade
				menorIdade = idade
			}
			senao	{
				se (idade > maiorIdade)	{
					maiorIdade = idade
				}
				se (idade < menorIdade)	{
					menorIdade = idade
				}
			}
	
			se (sexo == 'F' ou sexo == 'f')	{
				se (salario <= 200.00) {
					mulheresSalarioBaixo = mulheresSalarioBaixo + 1
				}
			}

			se (contadorPessoas == 1)	{
				menorSalario = salario
				idadeMenorSalario = idade
				sexoMenorSalario = sexo
			}
			senao	{
				se (salario < menorSalario)	{
            menorSalario = salario
            idadeMenorSalario = idade
            sexoMenorSalario = sexo
				}
			}
      
			escreva("Digite a próxima idade: ")
			leia(idade)
		}

		escreva("\n========= Resultado da Pesquisa =========\n")

		se (contadorPessoas > 0){

			mediaSalarios = somaSalarios / contadorPessoas

			escreva("a) Média dos salários do grupo: R$ ", mediaSalarios, "\n")
			escreva("b) Maior idade do grupo: ", maiorIdade, " anos\n")
			escreva("   Menor idade do grupo: ", menorIdade, " anos\n")
			escreva("c) Quantidade de mulheres com salário até R$ 200,00: ", mulheresSalarioBaixo, "\n")
			escreva("d) Dados da pessoa com o menor salário (R$ ", menorSalario, "):\n")
			escreva("   - Idade: ", idadeMenorSalario, " anos\n")
			escreva("   - Sexo: ", sexoMenorSalario, "\n")
		}
		senao	{
			escreva("Nenhum dado foi inserido.\n")
		}
	}
}