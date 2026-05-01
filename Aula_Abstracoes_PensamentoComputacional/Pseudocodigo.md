INICIO Algoritmo PrepararReceita

  preparar_utensilios()
  
  ingredientes_misturados <- misturar_itens(ovos, manteiga, acucar)
  
  ENQUANTO (massa_homogenea == FALSO) FACA
    bater_massa(ingredientes_misturados)
  FIM ENQUANTO
  
  SE (forno_aquecido == VERDADEIRO) ENTAO
    assar_massa(carrinho)
    exibir_mensagem("Receita Pronta!")
  SENAO
    exibir_mensagem("Aguarde o aquecimento")
  FIM SE

FIM Algoritmo
