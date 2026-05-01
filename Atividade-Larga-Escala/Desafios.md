# Desafios de Sistemas de Larga Escala

## 1. Escalabilidade
* **Problema:** Milhões de acessos simultâneos podem derrubar o servidor.
* **Solução:** Uso de múltiplos servidores interligados (Clusters) para distribuir a carga de acesso.

## 2. Mutabilidade
* **Problema:** O software precisa ser atualizado constantemente sem sair do ar.
* **Solução:** Arquitetura modular onde é possível atualizar o módulo de "Comentários" sem afetar o módulo de "Login".

## 3. Invisibilidade
* **Problema:** A complexidade do sistema torna difícil entender falhas.
* **Solução:** Documentação detalhada e mapeamento de fluxos para facilitar a manutenção pela equipe.
