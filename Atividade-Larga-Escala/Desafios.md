# Desafios Críticos e Soluções Mitigadoras

## 1. Escalabilidade
* **Desafio:** Manter o sistema estável com milhões de usuários simultâneos.
* **Solução:** Uso de arquitetura distribuída (clusters) para balanceamento de carga.

## 2. Segurança (Saltzer & Schroeder)
* **Desafio:** Proteção de dados sensíveis dos usuários.
* **Solução:** Aplicação do princípio de "Menor Privilégio", garantindo que usuários tenham acesso apenas aos seus próprios dados privados.

## 3. Mutabilidade
* **Desafio:** Atualizar o sistema sem interromper o serviço para os usuários.
* **Solução:** Design modular que permite alterações em componentes isolados sem afetar o sistema completo.
