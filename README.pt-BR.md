[🇺🇸 English](README.md) · 🇧🇷 Português

# Trabalho-desingweb

Quatro telas de interface estáticas feitas só com HTML e CSS (sem JavaScript, sem frameworks) para um trabalho de Design Web da faculdade.

## Contexto

Este foi o primeiro trabalho ("Trabalho 1") da disciplina de Design Web na faculdade: recriar algumas telas usando apenas HTML e CSS. Todas as telas usam a paleta de cores [Catppuccin Mocha](https://catppuccin.com). O conteúdo (músicas, canais, arquivos) é fictício, e as telas são maquetes estáticas: botões e campos não fazem nada.

## O que tem aqui

Cada pasta é uma tela, com seu próprio `index.html` e `style.css`:

| Pasta | Tela |
| --- | --- |
| `mobile-e-impressora3d/` | Item 1: tela mobile de um player de música ("NovaTune") e menu estilo desktop de um app de impressora 3D |
| `layout-colorido/` | Item 2: grade com as cores do Catppuccin Mocha, com nomes e códigos hex |
| `gerenciador-arquivos/` | Item 3: janela de gerenciador de arquivos (barra de título, barra de ferramentas, caminho, barra lateral, lista de arquivos, barra de status) |
| `novacast-youtube/` | Item 4: página de resultados de busca estilo YouTube ("NovaCast") com cabeçalho, barra lateral e grade de vídeos |

## Como rodar

Não há build nem dependências. Clone o repositório e abra qualquer `index.html` no navegador, por exemplo:

```bash
git clone https://github.com/y4g0o/Trabalho-desingweb.git
cd Trabalho-desingweb
xdg-open novacast-youtube/index.html   # Linux; no macOS use "open", no Windows dê dois cliques
```

## O que aprendi / próximos passos

- Montar layouts completos (cabeçalhos, barras laterais, grades, cards, moldura de janela) só com HTML e CSS, reaproveitando uma paleta de cores em várias telas.
- Próximo: deixar as telas responsivas. Ainda não há `<meta name="viewport">` nem media queries, então elas foram pensadas para tela de desktop.
- Próximo: melhorar acessibilidade e semântica, por exemplo `aria-label` nos botões só com ícone, rótulos nos campos e elementos como `<header>`, `<nav>` e `<main>` no lugar de `<div>`s genéricas.
- Próximo: dar um `<title>` descritivo a cada página (hoje são "Item 1" a "Item 4") e criar um `index.html` na raiz com links para as quatro telas.

## Feedback e contribuições são bem-vindos

Feedback sobre o HTML/CSS é bem-vindo. Abra uma issue ou mande um pull request pequeno, principalmente com correções de acessibilidade ou responsividade. Por favor, mantenha só HTML e CSS, já que essa era a regra do trabalho.

## Licença

[MIT](LICENSE) © Yago Macambira
