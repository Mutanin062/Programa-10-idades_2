programa
{
    funcao inicio()
    // Iniciando programa
    {
        inteiro idade, maiorIdade = 0
        para(inteiro i = 1; i <= 10; i++)
        // Declarando idade e maior idade
        {
            escreva("Digite a idade da pessoa ", i, ": ")
            leia(idade)
            se (idade > maiorIdade)
            // Escrevendo e lendo as idades
            {
                maiorIdade = idade
            }
        }
        escreva("A maior idade é: ", maiorIdade)
        // Mostrando maior idade
    }
}
