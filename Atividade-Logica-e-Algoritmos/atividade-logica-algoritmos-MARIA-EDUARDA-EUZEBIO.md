# Algoritmo de Controle de Acesso

## 1. Pseudocódigo (Linguagem Estruturada)

```text
ALGORITMO ControleAcessoSala
INICIO
    VAR listaOficial: Lista de Nomes
    VAR nomeAluno: Texto
    VAR quantidadeFila: Inteiro
    VAR i: Inteiro

    ESCREVA "Informe a quantidade de alunos na fila: "
    LEIA quantidadeFila

    // Estrutura de Repetição para garantir que todos sejam verificados
    PARA i DE 1 ATE quantidadeFila FACA
        ESCREVA "Digite o nome do aluno: "
        LEIA nomeAluno

        // Estrutura de Decisão para permissão de entrada
        SE (nomeAluno consta na listaOficial) ENTAO
            ESCREVA "Entrada permitida para: " + nomeAluno
        SENAO
            // Mensagem de erro obrigatória
            ESCREVA "ERRO: O aluno " + nomeAluno + " não está na lista oficial. Entrada NEGADA."
        FIM_SE
    FIM_PARA

    ESCREVA "Fila finalizada com sucesso."
FIM
