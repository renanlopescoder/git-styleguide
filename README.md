# Git Commit Message Style Guide
## Guia de Estilos para Mensagens de Commit

## Tipos

- feature: nova funcionalidade
- bugfix: correções de erros
- docs: mudança na documentação
- style: formatação como adição de ponto e virgula, identação, etc. sem alterações do código em produção
- refactor: refatoração no código de produção como melhorias de performance ou organização de arquivos
- test: Adição de testes, alteração em testes, sem alteração no código de produção
- chore: adição ou alterações em tarefas automatizadas (Gulp / Grunt)
- package: adição ou alteração nas dependências do projeto
- issue: normalmente usado no footer ou no título para referenciar id da issue resolvida ou concluída

## Title
#### Titulo do Commit (Obrigatório)

- Os titulos devem ser escritos com foco na atualização principal efetuada no commit e pode conter também o id da issue para rastreamento.

## Body
#### Corpo do Commit (Obrigatório)

- No corpo da mensagem deve conter detalhado todos os pontos principais e secundários.

## Footer
#### Rodapé do Commit (Opcional)

- Pode conter id da issue para rastreamento ou observaçes gerais sobre o commit.

Exemplo commit com nova funcionalidade:

```
feature: novo controle de mensagens

feature: Adicionado controle de mensagens com formularios de adição e alteração.
style: lista de mensagens
chore: automatizado minificação dos arquivos das mensagens (Gulp)

issue: 1029
```

Exemplo commit com melhorias de performance:

```
issue: 1209 - refactor: desempenho load inicial da aplicação

refactor: reduzido número de imports fazendo concatenção dos arquivos css
refactor: redução do peso de imagens redimencionando para tamanho correto de apresentação
refactor: redução no peso das imagens usando compressão lossy
chore: automatizado minificação e concatenação dos arquivos css (Gulp)
```
