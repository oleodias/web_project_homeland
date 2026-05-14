# 🌍 De Pátria para Pátria — TripleTen Art Gallery

## 📝 Descrição do Projeto

**De Pátria para Pátria** é uma página web responsiva que apresenta as cidades natais de profissionais da Galeria de Arte TripleTen. Uma jornada épica que parte do Kentucky e atravessa o País de Gales, a Ucrânia e o Burundi, celebrando as origens e histórias que formam a equipe da galeria.

O projeto foi desenvolvido como parte do Sprint 5 do curso de Desenvolvimento Web da TripleTen Brasil, com foco em **layout responsivo adaptativo** para três principais larguras de tela: `1280px`, `768px` e `320px`.

### 🎯 Funcionalidades

- **Layout adaptativo** com pontos de interrupção (breakpoints) em `544px` e `1024px`.
- **Tipografia em escala fluida** que se ajusta de forma harmônica em cada resolução.
- **Imagem responsiva** em escala de cinza, já fornecida pelo design, que se adapta a cada breakpoint.
- **Hierarquia semântica** completa com tags `<header>`, `<main>`, `<section>` e `<footer>`.

---

## 🛠 Tecnologias Utilizadas

- **HTML5 Semântico**: estruturação acessível com tags semânticas e atributos `alt` em todas as imagens.
- **CSS3 com Metodologia BEM Flat**: cada bloco em seu arquivo CSS separado dentro de `/blocks`, garantindo manutenção e escalabilidade.
- **Consultas de mídia (Media Queries)**: layout responsivo com `max-width` em `1023px` e `543px`.
- **Fontes locais**: família Inter conectada via `@font-face` em formato `.woff2`, sem dependências externas.
- **Normalize.css**: reset de estilos consistente entre navegadores.
- **Otimização de imagens**: imagem principal exportada do Figma e comprimida para reduzir o tempo de carregamento.

---

## 📐 Estrutura do Projeto

```
web_project_homeland/
├── blocks/             ← Blocos BEM (CSS por componente)
│   ├── footer.css
│   ├── intro.css
│   ├── lead.css
│   ├── logo.css
│   └── page.css
├── images/             ← Imagens e SVGs
├── pages/
│   └── index.css       ← Orquestrador de imports
├── vendor/
│   ├── fonts/          ← Arquivos .woff2 da fonte Inter
│   ├── fonts.css
│   └── normalize.css
├── favicon.ico
├── index.html
└── README.md
```

---

## 🎨 Design

O design foi fornecido em Figma com três frames principais (320, 768 e 1280 pixels) e segue o tema **"De Pátria para Pátria"**.

> _"Cada pessoa é um artista livre, chamado a transformar as condições, pensamentos e estruturas que moldam suas vidas."_
> — Joseph Beuys

---

## 👤 Autor

**Leonardo Dias Caumo** — _Desenvolvido como parte do portfólio de estudos em Desenvolvimento Web da TripleTen Brasil._

---

© 2026 Leonardo Dias Caumo
