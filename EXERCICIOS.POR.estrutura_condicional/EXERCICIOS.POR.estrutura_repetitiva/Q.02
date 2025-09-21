programa {
  inclua biblioteca Matematica --> mat 
  funcao inicio() {

      real preco_ingresso = 5.00, 
      despesas = 200.00, 
      receita, lucro, 
      lucro_maximo = 0.00, preco_ideal = 0.00, quantidade_ideal = 0.00
      inteiro quantidade_ingresso = 120

      escreva("| Preço (R$) | Quantidade de ingressos | Lucro (R$) |")

      enquanto (preco_ingresso >= 1) {
        receita = preco_ingresso * quantidade_ingresso
        lucro = receita - despesas

        escreva("   ", mat.arredondar(preco_ingresso, 2), " | ", mat.arredondar(lucro, 2), "\n")

        se (lucro > lucro_maximo) {
          lucro_maximo = lucro
          preco_ideal = preco_ingresso
          quantidade_ideal = quantidade_ingresso
        }

        preco_ingresso = preco_ingresso - 0.50
        quantidade_ingresso = quantidade_ingresso + 26
      }

      escreva("Lucro maximo esperado: R$", mat.arredondar(lucro, 2), "\n")
      escreva("Preço do ingresso ideal: R$", mat.arredondar(preco_ideal, 2), "\n")
      escreva("Quantidade de ingressos vendidos: ", quantidade_ideal, "\n")    
  }
}
