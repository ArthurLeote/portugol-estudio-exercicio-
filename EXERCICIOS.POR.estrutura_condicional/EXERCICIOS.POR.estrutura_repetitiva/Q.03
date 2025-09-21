programa {
  funcao inicio() {

    inteiro i, idade, porcentagem_primeiro, porcentagem_ultimo
      inteiro cont_1 = 0, cont_2 = 0, cont_3 = 0, cont_4 = 0, cont_5 = 0

    para (i = 1; i <= 8; i++) {
      escreva("Digite a idade de uma pessoa: ")
        leia(idade)

      se (idade <= 15){cont_1 = cont_1 + 1}
      senao se (idade >= 16 e idade <= 30) {cont_2 = cont_2 + 1}
      senao se (idade >= 31 e idade <= 45) {cont_3 = cont_3 + 1}
      senao se (idade >= 46 e idade <= 60) {cont_4 = cont_4 + 1}
      senao se (idade > 60) {cont_5 = cont_5 + 1}     
    }
    escreva("====== RESULTADO CONTAGEM ======")
    escreva("\nA quantidade de pessoas em cada faixa etária:\n | 1ª ", cont_1, " |\n | 2ª ", 
    cont_2, " |\n | 3ª ", cont_3, " |\n | 4ª ", cont_4, " |\n | 5ª ", cont_5, " | ")

    porcentagem_primeiro = (cont_1 * 100) / i
    porcentagem_ultimo = (cont_5 * 100) / i

     escreva("\n====== RESULTADO CONTAGEM ======")
     escreva("\nA porcentagem de pessoas na primeira faixa etária com relação ao total de pessoas é: ", porcentagem_primeiro, "%")
     escreva("\nA porcentagem de pessoas na última faixa etária com relação ao total de pessoas é: ", porcentagem_ultimo, "%")    
  }
}