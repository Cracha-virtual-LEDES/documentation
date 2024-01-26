# Visão Geral do Sistema
O Sistema de Crachá Virtual do LEDES tem como principal objetivo oferecer uma forma simples e prática de registrar e identificar os membros do Laboratório de Engenharia de Software. 

# Classes de Usuário
1. Usuário: O usuário comum do sistema poderá realizar seu cadastro e a partir dele terá um crachá contendo suas informações básicas. 

2. Administrador: O administrador do sistema poderá visualizar os crachás de todos os usuários cadastrados no sistema e aprovar as solicitações de mudanças nos crachás.

# Requisitos Funcionais
- RF-1. O sistema deve permitir a inclusão e alteração de contas com os seguintes atributos: nome, email, senha, CPF, cargo e foto de perfil.

- RF-2. O sistema deve permitir que os usuários visualizem seus crachás.

- RF-3. O sistema deve garantir que não haja repetição de CPF nos cadastros.

- RF-4. O sistema deve garantir que não haja repetição de email nos cadastros.

- RF-5. O sistema deve gerar uma data de expiração para o crachá após sua criação.

- RF-6. [Administrador] Todas as alterações feitas no crachá devem ser aprovadas por um Administrador. 

- RF-7.[Administrador] O sistema deve permitir que apenas perfis de Administrador criem novos usuários do tipo Administrador.
