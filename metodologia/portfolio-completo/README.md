# Portfólio — Luiz Henrique Rabello Ferreira

Site estático (HTML + CSS puro, sem build) com identidade visual minimalista
inspirada no álbum *The Car* (Arctic Monkeys, 2022): fundo creme de papel
envelhecido, tipografia brutalista-retrô (Archivo Black), granulação de película,
o poste vermelho na proporção áurea e paleta creme/carvão/oliva/mostarda/vermelho
vintage.

A estética é só visual — a estrutura é de portfólio mesmo: Sobre mim (com foto),
índice de projetos e um bloco por semestre (Projeto 01 a 05), com o conteúdo
completo do README original preservado nos dropdowns "Detalhes do Projeto"
(introdução, contribuições com código, hard/soft skills e competências).

A foto em `assets/foto-luiz.png` é o avatar do GitHub — para trocar, basta
substituir o arquivo mantendo o nome.

## Rodar localmente

Abra o `index.html` no navegador, ou:

```bash
npx serve .
```

## Deploy no Vercel

Dentro desta pasta (`portfolio-completo/`):

```bash
vercel            # primeiro deploy
vercel --prod     # produção
```

Ou em [vercel.com/new](https://vercel.com/new): importe o repositório com
**Root Directory** = `portfolio-completo`, framework preset **Other**.

## Estrutura

```
portfolio-completo/
├── index.html   # todo o conteúdo do README, com dropdowns
├── style.css    # identidade visual The Car
└── assets/      # todas as imagens dos 5 semestres + foto-luiz.png
```

Obs.: `assets/` tem ~24 MB (o `pontual.gif` do 3º semestre sozinho tem 14 MB).
Se quiser a página mais leve, dá para trocar esse GIF por um menor.
