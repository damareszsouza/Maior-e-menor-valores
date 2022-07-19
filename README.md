# Maior-e-menor-valores

Exercício 2: Maior e Menor valor
Gabarito do Exercício 2
Exercício 2: Faça uma função que leia cinco valores inteiros, determine e mostre o maior e o menor deles.

programa
{
    funcao inicio()
    {
        inteiro numeros[5]
        escreva("Escreva os números: ")
        para(inteiro n=0; n<5; n++){
            leia(numeros[n])
        }
        maiormenorde5(numeros)
    }

    funcao maiormenorde5 (inteiro numeros[])
    {
        inteiro maior = numeros[0]
        inteiro menor = numeros[0]
        para(inteiro n=1; n<5; n++){
            se(numeros[n] > maior){
                maior = numeros[n]
            }
            se(numeros[n] < menor){
                menor = numeros[n]
            }
        }
        escreva("Maior número: ", maior, "\n")
        escreva("Menor número: ", menor, "\n")
    }

}
