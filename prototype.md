# Protótipo

Este documento tem como objetivo apresentar o Protótipo do nosso projeto, um documento com informações essenciais sobre a criação das interfaces do sistema. 

O protótipo foi desenvolvido por meio da ferramenta Figma, e pode ser acessado por meio deste [link](https://www.figma.com/file/H3eSGIgJDEs1K8q3RCNBAJ/Crach%C3%A1-Virtual?type=design&node-id=0-1&mode=design&t=2uO9uvZACSjMwhz1-0).

Todas as telas foram desenvolvidas no formato mobile e para notebook/computador.

## Paleta de cores
A paleta de cores do nosso sistema é composta pelos seguintes valores, respectivamente:
- #F2F2F2
- #333437
- #C1C1C1
- #CFEFF8
- #0099CB
- #1E3B66

<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo3.jpeg" alt="Login" width="1500" height="230">

## Organização das telas

Nosso sistema tem 2 tipos de usuários: o administrador e o perfil dos pesquisadores vinculados ao laboratório de desenvolvimento de software da universidade. 
Para satisfazer as necessidades do sistema, foram criadas 4 telas, 2 em comum entre os usuários e 1 para cada perfil.

Pesquisador 
- Cadastro 
- Login 
- Visualização do crachá
- Funcionalidade de editar informações pessoais do crachá

LEDES (admin)
- Visualização de lista de pesquisadores 
- Lista de solicitações
- Funcionalidade de aprovar solicitações de edição das informações dos pesquisadores

## Cadastro e Login
Ambos os usuários compartilham as telas de Login e Cadastro.

No Login, o usuário precisa inserir seu e-mail e senha.

<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo1.jpeg" alt="Login" width="850" height="500">

<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo2.jpeg" alt="Login" width="250" height="520">

Já no cadastro, o usuário insere: nome, e-mail, senha, confirmação de senha, CPF, cargo no laboratório e uma foto de perfil.
<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo4.jpeg" alt="Login" width="850" height="540">

<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo5.jpeg" alt="Login" width="250" height="540">

## Visualização e Edição do crachá
Os pesquisadores vinculados ao laboratório, após realizarem o login, tem acesso ao seu crachá pessoal, com informações do seu nome completo, foto de perfil, e-mail, cargo, CPF e a validade do seu próprio acesso ao laboratório. 
As informações pessoais do usuários podem ser editadas, porém essas alterações são validadas pelo administrador.

<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo6.jpeg" alt="Visualização" width="850" height="500">
<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo8.jpeg" alt="Tooltip de edição" width="850" height="500">
<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo10.jpeg" alt="Edição" width="850" height="500">

<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo7.jpeg" alt="Visualização - Mobile" width="300" height="540">
<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo9.jpeg" alt="Tooltip de edição - Mobile" width="300" height="540">
<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo11.jpeg" alt="Edição - Mobile" width="300" height="700">

## Gerenciamento do Administrador
O administrador do laboratório tem em sua tela uma tabela para gerenciar os participantes, em que ele tem acesso a todos os integrantes vinculados ao laboratório, com suas informações pessoais e solicitações de edição das mesmas, em que ele tem a opção de aceitar e vizualizar qual informação está sendo alterada. Além disso, o administrador consegue distinguir usuários verificados, que todas as informações já foram validadas, e usuários com pendências para validação.

<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo12.jpeg" alt="Gerenciamento do admin" width="900" height="540">

<img src="https://github.com/Cracha-virtual-LEDES/documentation/blob/main/images/prototipo13.jpeg" alt="Gerenciamento do admin - Mobile" width="800" height="540">
