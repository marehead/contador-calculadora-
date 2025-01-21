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
    programa {
  funcao inicio() 
  {
    inteiro numero = 0
    inteiro contador = 100

    escreva("informe um número inteiro para exibir sua multiplicação")
    leia(numero)

    escreva("\nResultado: \n")

    enquanto(contador <= 10)
    {
      escreva(contador, " X ", numero, ": ")
      escreva(contador * numero, "\n")
      contador = contador + 1
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
