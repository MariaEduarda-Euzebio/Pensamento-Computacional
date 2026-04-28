# Atividade Prática: Desafio de Controle de Acesso

## 1. O Desafio
Desenvolver uma solução sistemática para o controle de entrada de alunos, verificando a presença em uma lista oficial e tratando casos de acesso permitido ou negado.

## 2. Algoritmo (Pseudocódigo)

```text
ALGORITMO ControleAcessoSala
INICIO
    VAR listaOficial: Lista de Nomes
    VAR nomeAluno: Texto
    VAR quantidadeFila: Inteiro
    VAR i: Inteiro

    ESCREVA "Informe a quantidade de alunos na fila: "
    LEIA quantidadeFila

    // Estrutura de Repetição para percorrer a fila (Requisito: Repetição)
    PARA i DE 1 ATE quantidadeFila FACA
        ESCREVA "Digite o nome do aluno: "
        LEIA nomeAluno

        // Estrutura Condicional para verificação (Requisito: Verificação e Condicionais)
        SE (nomeAluno consta na listaOficial) ENTAO
            ESCREVA "Acesso Permitido para o aluno: " + nomeAluno
        SENAO
            // Mensagem de erro para condicional negativa
            ESCREVA "ERRO: O aluno " + nomeAluno + " não consta na lista oficial. Entrada NEGADA."
        FIM_SE
    FIM_PARA

    ESCREVA "Processo de entrada finalizado."
FIM
