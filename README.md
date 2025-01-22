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
//TABUADA
programa 
{
  inteiro contador = 1
  inteiro numero
  funcao inicio()
  {
    escreva("informe um número inteiro para exibir sua multiplicação")
leia(numero)

enquanto(contador <= 10)
{
  escreva(contador, " X ", numero, ": ", numero*contador, "\n")
  contador++
} 

escreva("Fim") 

}
}

//calculadora
programa {
 
  real numero1, numero2, soma, divisao, multiplicacao, subtracao
  inteiro operacao
 
 //segunda versão da uma caculadora
  funcao inicio() {
   
    escreva("Digite o primeiro número: ")
    leia(numero1)
    limpa()
 
    escreva("Digite o segundo número: ")
    leia(numero2)
    limpa()
 
    escreva("Escolha uma operação:\n")
    escreva("1 - Adição\n")
    escreva("2 - Subtração\n")
    escreva("3 - Multiplicação\n")
    escreva("4 - Divisão\n")
    leia(operacao)
 
    soma = numero1 + numero2
    subtracao = numero1 - numero2
    multiplicacao = numero1*numero2
    divisao = numero1/numero2
 
    se(operacao == 1){
      escreva("A soma é: " + soma)
    }
 
    se(operacao == 2){
      escreva("A subtracao é: " + subtracao)
    }
 
    se(operacao == 3){
      escreva("A multiplicação é: " + multiplicacao)
    }
 
    se(operacao == 4){
      se(numero2 == 0) {
        escreva("você não pode dividir nenhum número por zero")
      } senao{
        escreva("A divisão é: " + divisao)
      }
     
    }
 
 
 
  }
}

programa 
  {
    //EXEMPLO DE CONTADOR 
    
    funcao inicio()
    {

    inteiro totalDeNotas, contador = 1, somaDasNotas = 0

    escreva("informe o total de notas para cada média: ")
    leia(totalDeNotas)

    enquanto(contador <= totalDeNotas) 
    {
      inteiro notaAtual
      escreva("Qual a ", contador, "º nota")
      leia(notaAtual)
      somaDasNotas = somaDasNotas + notaAtual
      contador++
    }

    escreva("\nMédia: ", somaDasNotas / totalDeNotas)
    
  }
}

