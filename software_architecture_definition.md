# Arquitetura de Software

No nosso projeto do crachá virtual, tomamos a decisão em seguir com uma arquitetura de software monolítica.

Uma arquitetura de software monolítica representa um paradigma de desenvolvimento em que todos os componentes de uma aplicação são unificados em uma única base de código. 
Isso inclui desde a interface do usuário, passando pela lógica de negócios, até o acesso ao banco de dados. 
Esta abordagem tem várias vantagens, especialmente em contextos específicos.

Primeiramente, por ser um modelo unificado, a arquitetura monolítica permite uma compreensão mais direta e integrada do software. 
Como todas as funcionalidades estão contidas em um único local, desenvolvedores podem entender e navegar pelo código mais facilmente, o que pode acelerar tanto o desenvolvimento quanto a resolução de problemas. 
Além disso, o teste da aplicação tende a ser mais simplificado, uma vez que é necessário focar em uma única base de código.

No aspecto da implantação, sistemas monolíticos podem ser mais fáceis de implantar e gerenciar, já que consistem em um único pacote ou arquivo executável. 
Isso se traduz em uma simplificação nos processos de implantação e manutenção. Do ponto de vista financeiro, a arquitetura monolítica pode ser mais econômica, 
especialmente para projetos de menor escala, onde a complexidade e os custos adicionais de uma arquitetura mais distribuída, como a de microserviços, não se justificam.

No caso específico do nosso projeto, a escolha da arquitetura monolítica foi influenciada por vários fatores. 
O tamanho e o prazo do projeto, junto com a dimensão da equipe de desenvolvimento, indicaram que um modelo mais simples e direto seria o mais adequado. 
Além disso, a escolha do framework NextJS, conhecido por sua natureza fullstack, foi crucial. 
Este framework nos permite desenvolver tanto a interface do usuário quanto a parte mais técnica da aplicação de maneira integrada, utilizando uma mesma base de código. 
Isso não apenas simplifica o processo de desenvolvimento, mas também facilita a interação entre diferentes partes da aplicação, mantendo uma coesão que é fundamental para o sucesso do projeto.
