INICIO Algoritmo Algoritmo_do_Brownie

  // Abstração de Insumos
  preparar_ingredientes(ovos, acucar, chocolate_derretido)
  
  // Processo de Homogeneização
  ENQUANTO (massa_esta_lisa == FALSO) FACA
    bater_ingredientes()
  FIM ENQUANTO
  
  // Validação e Execução
  SE (temperatura_forno == 180) ENTAO
    assar_massa(tempo_30_min)
    exibir_mensagem("Fim do Processo: Brownie Pronto!")
  SENAO
    exibir_mensagem("Aguardando aquecimento do sistema.")
  FIM SE

FIM Algoritmo
