# Protótipo

Este documento tem como objetivo apresentar o Protótipo do nosso projeto, um documento com informações essenciais sobre a criação das interfaces do sistema. 

O protótipo foi desenvolvido por meio da ferramenta Figma, e pode ser acessado por meio deste [link](https://www.figma.com/file/H3eSGIgJDEs1K8q3RCNBAJ/Crach%C3%A1-Virtual?type=design&node-id=0-1&mode=design&t=2uO9uvZACSjMwhz1-0).

Todas as telas foram desenvolvidas no formato mobile e para notebook/computador.

## Organização das telas

Nosso sistema tem 2 tipos de usuários: o administrador e o perfil das pessoas vinculadas ao laboratório de desenvolvimento de software da universidade. 
Para satisfazer as necessidades do sistema, foram criadas 4 telas, 2 em comum entre os usuários e 1 para cada perfil.

## Cadastro e Login
Ambos os usuários compartilham as telas de Login e Cadastro.

No Login, o usuário precisa inserir seu e-mail e senha.

Já no cadastro, o usuário insere: nome, e-mail, senha, confirmação de senha, CPF, cargo no laboratório e uma foto de perfil.

## Visualização e Edição do crachá
As pessoas vinculadas ao laboratório, após realizarem o login, tem acesso ao seu crachá pessoal, com informações do seu nome completo, foto de perfil, e-mail, cargo, CPF e a validade do seu próprio acesso ao laboratório. 
As informações pessoais do usuários podem ser editadas, porém essas alterações são validadas pelo administrador.

## Gerenciamento do Administrador
O administrador do laboratório tem em sua tela uma tabela para gerenciar os participantes, em que ele tem acesso a todos os integrantes vinculados ao laboratório, com suas informações pessoais e solicitações de edição das mesmas, em que ele tem a opção de aceitar e vizualizar qual informação está sendo alterada. Além disso, o administrador consegue distinguir usuários verificados, que todas as informações já foram validadas, e usuários com pendências para validação.
