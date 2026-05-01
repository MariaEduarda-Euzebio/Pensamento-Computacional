INICIO Algoritmo PrepararBrownie

  // Abstração de preparar ambiente
  preparar_utensilios()
  preaquecer_forno(180)

  // Lógica de mistura
  mistura_base <- bater_ingredientes(ovos, acucar)
  chocolate_derretido <- derreter(chocolate, manteiga)
  
  massa_final <- combinar(mistura_base, chocolate_derretido, farinha)

  // Estrutura de repetição para garantir qualidade
  ENQUANTO (massa_tem_pelotas == VERDADEIRO) FACA
    mexer_suavemente(massa_final)
  FIM ENQUANTO

  // Estrutura condicional de execução
  SE (forno_pronto == VERDADEIRO) ENTAO
    assar(massa_final, 25) // tempo em minutos
    exibir_mensagem("Brownie assado com sucesso!")
  SENAO
    exibir_mensagem("Erro: Aguarde o forno atingir a temperatura.")
  FIM SE

FIM Algoritmo
