# husky-template

Exemplo de configuração de hooks pré-commit

## Descrição

Uma abordagem aliando husky com eslint e lint-staged

Ao realizar um commit a ferramenta irá executar um yarn audit e um lint-staged. Este ultimo realiza o linter apenas dos arquivos que estão selecionados para commit.
