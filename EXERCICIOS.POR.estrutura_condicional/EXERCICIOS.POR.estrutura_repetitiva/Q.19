programa
{
	funcao inicio()
	{

		caracter tipoAcao
		real precoCompra
		real precoVenda
		real lucroAcao
		inteiro qtdLucroSuperior1000 = 0
		inteiro qtdLucroInferior200 = 0
		real lucroTotalEmpresa = 0.0
		
		escreva("--- Controle de Ações da Bolsa ---\n")
		escreva("Digite os dados de cada ação. Para finalizar, digite 'F' no tipo da ação.\n\n")
		escreva("Digite o tipo da ação (uma letra): ")
		leia(tipoAcao)

		enquanto (tipoAcao != 'F' e tipoAcao != 'f') {

			escreva("Digite o preço de compra: R$ ")
			leia(precoCompra)
			escreva("Digite o preço de venda: R$ ")
			leia(precoVenda)

			lucroAcao = precoVenda - precoCompra
			escreva("-> Lucro desta ação ('", tipoAcao, "'): R$ ", lucroAcao, "\n")
			escreva("-------------------------------------\n\n")

			lucroTotalEmpresa = lucroTotalEmpresa + lucroAcao

			se (lucroAcao > 1000.00) {
				qtdLucroSuperior1000 = qtdLucroSuperior1000 + 1
			}

			se (lucroAcao < 200.00)	{
				qtdLucroInferior200 = qtdLucroInferior200 + 1
			}

			escreva("Digite o tipo da próxima ação (ou 'F' para finalizar): ")
			leia(tipoAcao)
		}

		escreva("\n========= Relatório Final =========\n")
		escreva("Quantidade de ações com lucro SUPERIOR a R$ 1.000,00: ", qtdLucroSuperior1000, "\n")
		escreva("Quantidade de ações com lucro INFERIOR a R$ 200,00: ", qtdLucroInferior200, "\n")
		escreva("Lucro total da empresa: R$ ", lucroTotalEmpresa, "\n")
	}
}