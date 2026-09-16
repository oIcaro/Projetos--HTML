# Projeto Unes

Site institucional de uma universidade fictícia ("Unes"), desenvolvido como desafio prático do módulo de HTML. O projeto é composto por três páginas interligadas por um menu de navegação, construídas apenas com HTML puro — sem CSS externo.

## Páginas

| Arquivo | Conteúdo |
|---|---|
| `index.html` | Página inicial, com imagem de capa e a seção "Sobre a universidade" |
| `quem-somos.html` | Apresentação institucional, lista ordenada com "5 motivos para estudar" e a seção "Objetivos" |
| `contato.html` | Formulário de contato com campos de e-mail, assunto e descrição |

## Conceitos praticados

- Estruturação de layout com tabelas (`<table>`, `<tr>`, `<td>`, `colspan`)
- Navegação entre páginas com links relativos (`<a href>`)
- Inserção de imagens (`<img>`) e imagem de fundo via atributo `background`
- Formulários: `<form>`, `<label>`, `<input>` (`email`, `text`, `submit`) e `<textarea>`
- Hierarquia de conteúdo com títulos, parágrafos, listas ordenadas e separadores (`<hr>`)
- Definição de idioma, codificação de caracteres e viewport no `<head>`

## Estrutura de arquivos

```
Projeto_Unes/
├── index.html
├── quem-somos.html
├── contato.html
└── arquivos-necessarios-projetos-unes/
    ├── logo.png
    ├── capa.png
    └── fundo2.png
```

## Observação

O layout utiliza tabelas e atributos de apresentação (`border`, `align`, `width`, `background`), uma abordagem hoje considerada obsoleta e substituída por CSS. A escolha foi intencional, já que o desafio tinha como foco o domínio da estrutura HTML antes da introdução da estilização.

## Como visualizar

Abra o arquivo `index.html` diretamente no navegador.
