# Projeto: Planejamento de Sistema de Rede Social

## Descrição
Este projeto aplica os fundamentos do Pensamento Computacional e da Engenharia de Software para projetar a arquitetura lógica de uma rede social de larga escala.

## Metodologia de Desenvolvimento
* **Metodologia:** Scrum.
* **Justificativa:** O uso de Sprints permite que o sistema seja desenvolvido em módulos (como 'Perfil', depois 'Postagens'), facilitando correções rápidas.

## Princípios de Segurança (Saltzer & Schroeder)
* **Menor Privilégio:** Um usuário comum não tem permissão para acessar o banco de dados de outros usuários, apenas suas próprias informações.
* **Bloqueio por Padrão:** O acesso a qualquer funcionalidade privada é negado até que o usuário faça o login corretamente.
