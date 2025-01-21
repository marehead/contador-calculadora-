# contador-calculadora-em-logica-linguagem-de-programação
atividade senac lapa tito
programa {
  funcao inicio() 
  {
    logico baterPalma
    inteiro contador = 0

    //baterPalma = verdadeiro

    enquanto (contador < 5) {
      escreva("Clap! \n")
      escreva(contador, "\n")
      contador = contador + 1
    }   
  }
}
programa {
  funcao inicio() 
  {
    inteiro contador = 5
    inteiro limite = 12

    enquanto(contador <= limite)
  {
     escreva(contador, "\n")
     contador = contador + 5
  }
}
}
-----------------------------------
programa {
  funcao inicio() 
{
    //TABUADA DE UM NÚMERO QUALQUER 
    inteiro numero = 0
    inteiro contador = 1
    //PEÇA O NUMERO AO USUARIO E ARMAZENE EM UMA VARIAVEL
    escreva("informe um número inteiro para exibir sua multiplicação")
    leia(numero)
    //FAÇA UMA REPETIÇÃO DE 1 ATÉ 10, ANDE:
    enquanto(contador <= 10)
    {
      escreva(contador * numero, "\n")
      contador = contador + 1
    }
    //A CADA INTERAÇÃO DA REPETIÇÃO, MULTIPLICA O NUMERO PELO CONTADOR
    escreva("Fim")
  }
}
