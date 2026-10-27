# Pixel de Partida — Landing Page (projeto de estudo)

**Ver online:** https://pedrobartkevihi.github.io/PixelDePartida/

Landing page **fictícia** de uma escola de oficinas presenciais de
desenvolvimento web para iniciantes, criada **para fins de estudo**. Partindo
de um exercício de curso feito só com HTML e CSS, o objetivo foi modernizar o
visual — layout, tipografia, cores, espaçamentos, botões, cards,
responsividade e pequenas interações — mantendo o estilo de escrita do código
original.

A **Pixel de Partida**, as turmas, os planos e os textos são inventados para
este projeto e não correspondem a nenhuma empresa real.

## Tecnologias

- HTML5
- CSS3 (variáveis em `:root`, flexbox, `clamp()` e media queries)
- JavaScript (vanilla, sem dependências)
- [Google Fonts](https://fonts.google.com/) — Inter e Poppins (OFL)

Sem frameworks e sem etapa de build: é só abrir o `index.html`.

## Estrutura

```
Projeto1/
├── index.html
└── src/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── images/
        ├── logo-icone.svg  (ícone da logo, ao lado da marca em texto)
        ├── favicon.svg     (ícone da aba do navegador)
        ├── topo.jpg        (foto da seção inicial)
        ├── seta.svg        (seta da seção "Sobre")
        └── icone-plano.svg (ícone dos cards de planos)
```

## Seções

1. **Cabeçalho** — logo, menu de navegação e menu mobile (dropdown).
2. **Chamada** — título, lista de benefícios e formulário de inscrição.
3. **Sobre** — como funcionam as oficinas.
4. **Planos** — três cards com os formatos de turma.
5. **Rodapé** — marca e slogan.

## Interações (`src/js/script.js`)

- Abre/fecha o menu no mobile (com `Esc`, clique fora e clique em link).
- Sombra no cabeçalho ao rolar a página.
- Elementos `[data-revelar]` surgem ao entrar na tela (`IntersectionObserver`).
- Feedback ao enviar o formulário (não há back-end).
- Respeita `prefers-reduced-motion` e funciona sem JavaScript.

## Como executar

Abra o `index.html` no navegador, ou rode um servidor estático na pasta do
projeto:

```bash
python -m http.server 8080
```

E acesse `http://localhost:8080`.

## Créditos das imagens

A foto da seção inicial é do [Pexels](https://www.pexels.com/photo/6424588/)
(licença livre, sem necessidade de atribuição), redimensionada e sem
metadados. A logo, o favicon, a seta e o ícone dos planos são SVGs simples,
desenhados para este projeto.

## Uso

Repositório de **estudo de front-end, sem fins comerciais**. O código-fonte
(HTML, CSS e JavaScript) é de autoria de **Pedro Farias** e pode ser
reaproveitado livremente. Toda a identidade (nome da escola, textos e planos)
é fictícia.
