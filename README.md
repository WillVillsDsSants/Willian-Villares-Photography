<div align="center">

![Willian Villares Photography](banner.svg)

<br>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-wvillares--photography.vercel.app-c8c8c8?style=for-the-badge&labelColor=0a0a0a&color=1a1a1a)](https://wvillares-photography.vercel.app)
&nbsp;
[![Instagram](https://img.shields.io/badge/INSTAGRAM-%40wvillares.photos-c8c8c8?style=for-the-badge&logo=instagram&logoColor=c8c8c8&labelColor=0a0a0a&color=1a1a1a)](https://www.instagram.com/wvillares.photos/)
&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-will.vills.ds.sants%40hotmail.com-c8c8c8?style=for-the-badge&logo=gmail&logoColor=c8c8c8&labelColor=0a0a0a&color=1a1a1a)](mailto:will.vills.ds.sants@hotmail.com)

<br>

```
Fotografia urbana · Bauru — SP · Brasil
Sony ZV-E10 · street · nocturne · cotidiano · arquitetura
```

</div>

---

## Sobre o Projeto

Portfolio pessoal de fotografia urbana construido do zero — sem templates, sem CMS, sem frameworks. Um unico arquivo HTML com CSS e JavaScript puros, conectado a um backend real no Supabase e hospedado na Vercel com deploy automatico via GitHub.

O projeto nasceu da vontade de ter um espaco proprio para a fotografia e virou um exercicio completo de desenvolvimento web — do design ao backend, passando por otimizacao de performance, acessibilidade e SEO.

---

## A Fotografia

Encontro nas ruas a minha maior inspiracao. Cada clique e uma tentativa de registrar o que passa despercebido na pressa do dia a dia — becos, fachadas, cenas noturnas, silhuetas contra a luz, reflexos no asfalto molhado.

A camera nao como instrumento de registro, mas de **leitura da cidade**.

| | |
|---|---|
| **Camera** | Sony ZV-E10 |
| **Lente** | 16–50mm f/3.5–5.6 OSS |
| **Base** | Bauru — SP, Brasil |
| **Estilos** | Street · Nocturne · Cotidiano · Arquitetura |

---

## Stack Tecnica

| Camada | Tecnologia | Detalhe |
|---|---|---|
| **Frontend** | HTML · CSS · JavaScript | Single file, zero dependencias de build |
| **Backend** | Supabase | PostgreSQL + Storage para fotos |
| **Hospedagem** | Vercel | Deploy automatico via GitHub |
| **Tipografia** | Cormorant Garamond · DM Sans | Google Fonts, carregamento nao-bloqueante |
| **Favicon** | SVG inline | Sem arquivo externo, carrega instantaneo |

---

## Funcionalidades

**Portfolio publico**
- Grade de fotos dinamica com 5 modos de layout (2, 3, 4 colunas, masonry e destaque)
- Lightbox com navegacao por teclado, painel de specs tecnicas e fundo desfocado
- Secao de Series com modal de colecoes e animacao de entrada
- Hero com foto configuravel via painel admin
- Menu mobile fullscreen com animacao de entrada escalonada

**Painel Admin** *(acesso restrito por senha)*
- Upload de fotos diretamente para o Supabase Storage
- Gestao completa de fotos, series e categorias
- Reordenacao por drag-and-drop com publicacao em lote
- Selecao de layout do portfolio salvo no banco e aplicado em tempo real
- Upload e troca da foto hero

**Performance e SEO**
- Fonts nao-bloqueantes com preload
- `fetchpriority="high"` na primeira imagem (LCP)
- Preconnect ao Supabase e dns-prefetch ao JSDelivr
- `<main>` landmark, `aria-label` em todos os controles
- Schema.org: Person, WebSite e ImageGallery
- Open Graph e Twitter Card completos

---

## Performance — Lighthouse

| Metrica | Desktop | Mobile |
|---|---|---|
| **Performance** | 99 / 100 | 88 / 100 |
| **Acessibilidade** | 100 / 100 | 100 / 100 |
| **Praticas recomendadas** | 100 / 100 | 96 / 100 |
| **SEO** | 100 / 100 | 92 / 100 |

> Limitacao principal: tamanho das imagens no Supabase (controlado pelo upload do usuario, nao pelo codigo)

---

## Estrutura do Repositorio

```
/
├── index.html          site completo — frontend + logica + admin
├── vercel.json         headers de seguranca, cache e cleanUrls
├── banner.svg          banner do README
├── og-image.png        preview para redes sociais (1200x630)
├── favicon.ico
└── README.md
```

---

## Sobre

De dia, **analista de logistica** — processos, fluxos e dados operacionais.

Nas horas livres, fotografo nas ruas e entusiasta de **programacao** e **inteligencia artificial**. Acredito que tecnologia e arte caminham juntas — este portfolio e a prova disso.

| | |
|---|---|
| Logistica | Analise de processos, fluxos operacionais e dados |
| Fotografia | Street photography, arquitetura, cotidiano urbano |
| Dev | HTML · CSS · JavaScript · integracoes com APIs |
| IA | Entusiasta de automacao, LLMs e ferramentas de IA |

---

<div align="center">

```
feito com camera na rua e codigo no terminal
```

*Desenvolvido com auxilio de inteligencia artificial como parte de estudos e experimentos em desenvolvimento web.*
*Todo o conceito, conteudo e direcao criativa sao autorais.*

</div>
