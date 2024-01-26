# Guia de estilo para mensagens de commit do Github

## Formato
As mensagens de commit devem seguir o seguinte formato:

[tipo] : descrição

[corpo]

[rodapé]

Onde:
- tipo: Uma palavra que descreve a natureza da mudança (ex: "feat", "fix", "documentation", etc.).
- descrição: Uma breve descrição do que foi feito (ex: "Adicionar validação do tamanho do dataset").
- [corpo]: Uma explicação mais detalhada das mudanças feitas, justificativas, etc.
- [rodapé]: Informações adicionais, como número de issues relacionadas, referências a outras mudanças, etc.

## Tipos
Os tipos de mensagens de commit devem ser apenas um dentre as opções a seguir:
- FEAT: Uma nova funcionalidade adicionada
- FIX: Alterações que afetam o sistema de compilação ou dependências externas, uma correção de bug
- REFACTOR: Uma alteração de código que não corrige um bug nem adiciona um recurso, mas torna o código mais limpo, eficiente ou bem documentado
- DOCUMENTATION: Documentação
- REVERT: Reverter um commit anterior
- TEST: Adiciona testes ausentes ou corrige testes existentes
- STYLE: Alterações que não afetam o comportamento do código (espaço em branco, formatação, falta ponto e vírgula, etc.)
- PERF: Uma alteração de código que melhora o desempenho da aplicação
- BUILD: Alterações que afetam o sistema de compilação ou dependências externas
- CHORE: Alterações na configuração, build, ou outras alterações que não modificam os arquivos src ou de teste
- CI: Alterações em nossos arquivos e scripts de configuração de CI (exemplos de escopos: Travis, Circle, BrowserStack, SauceLabs)
- TYPO: Correção ortográfica atribuída a comentários ou nomes de variáveis
- FUNC: Criação de uma função unitária no corpo do código
- IN: Arquivos de entrada que servem para popular o sistema
- UPDATE: Atualização de arquivo ou documento contendo nova prescrição/conteúdo
- CONFLICT: Resolução de conflito 

## Descrição
A descrição deve ser clara e sucinta do que foi feito. Ele deve ser escrito em letras minúsculas e sem ponto final.

## Corpo
O corpo é opcional e pode ser usado para fornecer mais informações sobre as mudanças feitas. Ele deve ser escrito em letras minúsculas e separado do assunto por uma linha em branco.

## Rodapé
O rodapé é opcional e pode ser usado para fornecer informações adicionais, como números de issues relacionadas, referências a outras mudanças, etc. Ele deve ser escrito em letras minúsculas e separado do corpo por uma linha em branco.

## Exemplo
refactor: Mudar tabelas do banco

Mudança das tabelas do banco de acordo com o alinhamento em reunião, adicionando a coluna CPF na tabela de Pessoa.

Fixes #123
