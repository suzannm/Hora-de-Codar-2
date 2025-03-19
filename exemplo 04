programa {
    funcao inicio() {
        real numero1, numero2, numero3, soma

        escreva("Digite o primeiro número: ")
        leia(numero1)
        escreva("Digite o segundo número: ")
        leia(numero2)
        escreva("Digite o terceiro número: ")
        leia(numero3)

        se (numero1 >= numero2 e numero1 >= numero3) {
            se (numero2 >= numero3) {
                soma = numero1 + numero2
            } senao {
                soma = numero1 + numero3
            }
        } se (numero2 >= numero1 e numero2 >= numero3) {
            se (numero1 >= numero3) {
                soma = numero2 + numero1
            } senao {
                soma = numero2 + numero3
            }
        } se (numero3 >= numero1 e numero3 >= numero2) {
            se (numero2 >= numero1) {
                soma = numero3 + numero2
            } senao {
                soma = numero3 + numero1
            }
        }
        escreva("A soma dos dois maiores números é: ", soma)
    }
}
