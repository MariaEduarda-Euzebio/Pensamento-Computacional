# Algoritmo de Controle de Acesso

```text
ALGORITMO ControleAcessoSala
INICIO
    VAR listaOficial: Lista de Nomes
    VAR nomeAluno: Texto
    VAR quantidadeFila: Inteiro
    VAR i: Inteiro

    ESCREVA "Informe a quantidade de alunos na fila: "
    LEIA quantidadeFila

    PARA i DE 1 ATE quantidadeFila FACA
        ESCREVA "Digite o nome do aluno: "
        LEIA nomeAluno

        SE (nomeAluno consta na listaOficial) ENTAO
            ESCREVA "Acesso Permitido para: " + nomeAluno
        SENAO
            ESCREVA "ERRO: Aluno " + nomeAluno + " não autorizado."
        FIM_SE
    FIM_PARA

    ESCREVA "Processo finalizado."
FIM
