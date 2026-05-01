# Documentação de Design e Raciocínio Lógico

## 1. Decomposição
Para gerenciar a complexidade, o sistema foi dividido em módulos menores:
* **Gestão de Usuários:** Cadastro, login e perfis.
* **Feed de Notícias:** Processamento de fotos, vídeos e textos.
* **Interações:** Sistema de curtidas, comentários e compartilhamentos.

## 2. Abstração e Padrões
* **Reconhecimento de Padrões:** Identificamos que o processo de "curtir" uma foto é o mesmo de "curtir" um comentário, permitindo usar a mesma lógica para ambos.
* **Abstração:** Focamos na funcionalidade essencial de cada postagem (autor, conteúdo e data), ignorando detalhes técnicos de como a imagem é armazenada no hardware.

## 3. Algoritmos
* O sistema utiliza um algoritmo de ordenação para exibir primeiro as postagens mais recentes e relevantes no topo do feed do usuário.
