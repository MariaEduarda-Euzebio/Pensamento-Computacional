# Documentação de Design – Pensamento Computacional

## 1. Decomposição
O sistema foi dividido em módulos fundamentais para facilitar a gestão da complexidade:
* **Módulo de Usuários:** Cadastro, autenticação e perfis.
* **Módulo de Conteúdo:** Processamento e exibição de postagens (fotos/vídeos).
* **Módulo de Conexões:** Gestão de seguidores e interações (curtidas/comentários).

## 2. Abstração e Padrões
* **Reconhecimento de Padrões:** Identificamos que a estrutura de notificações segue o mesmo padrão lógico para diferentes tipos de alertas (novas curtidas ou novos seguidores).
* **Abstração:** Focamos nas informações essenciais de uma postagem (autor e mídia), ignorando detalhes de infraestrutura de hardware.

## 3. Algoritmos
* Implementação lógica de um algoritmo de ordenação para o feed, garantindo que o conteúdo seja exibido de acordo com a relevância para o usuário.
  
