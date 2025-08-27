# Comparação entre Programação Procedural e Orientada a Objetos

Programação orientada a objetos e programação procedural são dois paradigmas diferentes de como estruturar e organizar o código. Na programação procedural, o foco está em funções e procedimentos que manipulam dados, você escreve um conjunto de instruções que são executadas passo a passo, normalmente com variáveis globais ou locais sendo passadas entre funções. Já a programação orientada a objetos organiza o código em torno de objetos, que são instâncias de classes contendo atributos (dados) e métodos (funções). Enquanto a abordagem procedural se concentra mais na sequência de ações, a orientada a objetos busca modelar entidades do mundo real, encapsulando comportamento e estado dentro de objetos, o que facilita a reutilização, manutenção e expansão do código em sistemas maiores.


# Algoritmo: Hora de Acordar


```portugol
programa
{
    funcao vazio TocarAlarme()
    {
        escreva("Alarme tocando\n")
    }

    funcao vazio PararAlarme()
    {
        escreva("Parar Alarme\n")
    }

    funcao vazio RotinaPosAcordar()
    {
        escreva("Sentar na cama\n")
        escreva("Levantar da cama\n")
        escreva("Beber um copo de água\n")
        escreva("Fazer higiene (ir no banheiro, tomar banho e escovar os dentes)\n")
        escreva("Preparar café da manhã\n")
        escreva("Conferir agenda do dia\n")
        escreva("Sair para compromissos\n")
    }

    funcao inicio()
    {
        TocarAlarme()
        PararAlarme()
        RotinaPosAcordar()
    }
}
