# 🌍 De Pátria para Pátria — TripleTen Art Gallery

## 📝 Descrição do Projeto

**De Pátria para Pátria** é uma página web responsiva que apresenta as cidades natais de profissionais da Galeria de Arte TripleTen. Uma jornada épica que parte do Kentucky e atravessa o País de Gales, a Ucrânia e o Burundi, celebrando as origens e histórias que formam a equipe da galeria.

Este projeto foi desenvolvido em **duas partes**, ao longo dos Sprints 5 e 6 do curso de Desenvolvimento Web da TripleTen Brasil. No **Sprint 5**, foi construída a base do site com layout responsivo adaptativo. No **Sprint 6**, foram adicionadas as seções de **galeria de fotos** e **cidades natais**, ambas implementadas com **CSS Grid Layout**, além de **gradientes**, **sombras** e **estados de hover** para uma experiência visual mais rica.

### 🎯 Funcionalidades

- **Layout adaptativo** com pontos de interrupção (breakpoints) em `544px` e `1024px`, atendendo às três principais larguras de tela: `320px`, `768px` e `1280px`.
- **Galeria de fotos** em CSS Grid (4 colunas no desktop, 2 no tablet, 1 no mobile).
- **Seção de cidades natais** com 4 cards, cada um contendo: título, créditos do artista, imagem com sombra e botão NFT com gradiente.
- **Botões NFT** com gradiente azul (`#0278FE → #003A7B`) e efeito de elevação ao passar o cursor (sombra que se expande).
- **Logotipo clicável** que retorna ao topo da página, com transição suave de opacidade no hover.
- **Bloco bônus** preparado para que o usuário adicione sua própria cidade natal.
- **Estrutura semântica** completa com `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<ul>` e `<li>`.

---

## 🛠 Tecnologias Utilizadas

- **HTML5 Semântico**: marcação acessível com tags semânticas e atributos `alt` em todas as imagens.
- **CSS3 com Metodologia BEM Flat**: cada bloco em arquivo CSS separado dentro de `/blocks`, garantindo manutenção e escalabilidade.
- **CSS Grid Layout**: usado nas seções `photo-grid` e `places` para criar layouts bidimensionais com `grid-template-columns`, `grid-template-areas` e `repeat()`.
- **Gradientes lineares**: aplicados nos botões NFT (`linear-gradient`).
- **Sombras**: `box-shadow` nas imagens grandes das cidades e nos botões (com transição animada no hover).
- **Estados Hover**: transições suaves em todos os elementos interativos (logo, botões, imagens da galeria).
- **Consultas de mídia (Media Queries)**: layout responsivo com `max-width` em `1023px` e `543px`.
- **Fontes locais**: família Inter conectada via `@font-face` em formato `.woff2`, em 5 pesos (Regular 400, Medium 500, SemiBold 600, Bold 700, Black 900).
- **Normalize.css** v8.0.1: reset de estilos consistente entre navegadores.
- **Otimização de imagens**: assets exportados do Figma e comprimidos sem perda visual, reduzindo o tamanho total em mais de 70%.

---

## 📐 Estrutura do Projeto

```
web_project_homeland/
├── blocks/                  ← Blocos BEM (CSS por componente)
│   ├── footer.css
│   ├── header.css
│   ├── intro.css
│   ├── lead.css
│   ├── page.css
│   ├── photo-grid.css       ← NOVO no Sprint 6
│   └── places.css           ← NOVO no Sprint 6
├── images/                  ← Imagens otimizadas
│   ├── image_country.jpg
│   ├── item_1.jpg ... item_8.jpg
│   ├── logo_header.svg
│   ├── place_berea.jpg
│   ├── place_criccieth.jpg
│   └── place_muramvya.jpg
├── pages/
│   └── index.css            ← Orquestrador de imports
├── vendor/
│   ├── fonts/               ← Arquivos .woff2 da fonte Inter
│   ├── fonts.css
│   └── normalize.css
├── favicon.ico
├── index.html
└── README.md
```

---

## 🎨 Design

O design foi fornecido em Figma com três frames principais (320, 768 e 1280 pixels) e segue o tema **"De Pátria para Pátria"** da TripleTen Art Gallery.

> _"Cada pessoa é um artista livre, chamado a transformar as condições, pensamentos e estruturas que moldam suas vidas."_
> — Joseph Beuys

---

## 📈 Planos de Melhoria

1. **Adicionar mais cidades natais**: expandir a galeria para incluir outras origens dos integrantes da TripleTen, criando uma jornada mais completa.
2. **Implementar uma versão multilíngue**: traduzir o site para inglês e ucraniano, refletindo a diversidade cultural dos artistas apresentados.

---

## 🔗 Link do Projeto

🌐 **GitHub Pages:** _adicionar URL aqui após publicar_

---

## 👤 Autor

**Leonardo Dias Caumo** — _Desenvolvido como parte do portfólio de estudos em Desenvolvimento Web da TripleTen Brasil._

---

© 2026 Leonardo Dias Caumo
