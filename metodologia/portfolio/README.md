# Portfólio — Luiz Henrique Rabello Ferreira

Site estático (HTML + CSS puro, sem build) com identidade visual inspirada no álbum
*The Car* (Arctic Monkeys, 2022): paleta creme/carvão/oliva/mostarda/vermelho vintage,
tipografia brutalista-retrô (Archivo Black), granulação de película e o portfólio
apresentado como um disco de vinil (Lado A / Lado B).

## Rodar localmente

Basta abrir o `index.html` no navegador, ou:

```bash
npx serve .
```

## Deploy no Vercel

Dentro desta pasta (`portfolio/`):

```bash
npm i -g vercel   # se ainda não tiver
vercel            # primeiro deploy (aceite os padrões)
vercel --prod     # deploy de produção
```

Ou pelo site: [vercel.com/new](https://vercel.com/new) → importe o repositório e
configure o **Root Directory** como `portfolio`. Framework preset: **Other** (não há build).

## Estrutura

```
portfolio/
├── index.html   # todo o conteúdo
├── style.css    # toda a identidade visual
└── assets/      # uma imagem/GIF por projeto
```
