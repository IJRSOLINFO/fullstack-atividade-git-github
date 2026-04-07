# Pratica de Git e GitHub com JavaScript

Este repositório é a base da atividade da turma.

## Objetivo

Cada aluno deve:

1. Escolher uma função da lista em `ATIVIDADES.md`.
2. Criar uma pasta com o nome da função dentro de `funcoes/`.
3. Implementar a função em JavaScript com os parâmetros exigidos.
4. Subir a solução com fluxo de Git/GitHub (branch, commit e pull request).

## Estrutura do projeto

```txt
funcoes/
  nome-da-funcao/
    index.js
    README.md (opcional)
template/
  nome-da-funcao/
    index.js
ATIVIDADES.md
CONVENCAO.md
```

## Passo a passo da atividade

1. Criar uma branch:

```bash
git checkout -b feat/seu-nome-nome-da-funcao
```

2. Criar a pasta da função em `funcoes/` seguindo a convenção.
3. Criar o arquivo `index.js` com a implementação.
4. Fazer commit:

```bash
git add .
git commit -m "feat(nome-da-funcao): implementa funcao"
```

5. Publicar a branch e abrir PR.

## Instalação e execução

Este projeto usa apenas Node.js (sem dependências externas).

```bash
npm install
```

## Critérios de avaliação

- Seguiu a convenção de pastas e nomes.
- Função implementada com os parâmetros corretos.
- Código legível e funcionando.
- Fluxo Git/GitHub feito corretamente.
