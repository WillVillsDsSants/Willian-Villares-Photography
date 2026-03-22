<div align="center">

![Willian Villares Photography](banner.svg)

<br>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-wvillares--photography.vercel.app-c8c8c8?style=for-the-badge&labelColor=0a0a0a&color=1a1a1a)](https://wvillares-photography.vercel.app)
&nbsp;
[![Instagram](https://img.shields.io/badge/INSTAGRAM-%40wvillares.photos-c8c8c8?style=for-the-badge&logo=instagram&logoColor=c8c8c8&labelColor=0a0a0a&color=1a1a1a)](https://www.instagram.com/wvillares.photos/)
&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-will.vills.ds.sants%40hotmail.com-c8c8c8?style=for-the-badge&logo=gmail&logoColor=c8c8c8&labelColor=0a0a0a&color=1a1a1a)](mailto:will.vills.ds.sants@hotmail.com)

<br>

<p>
Fotografia urbana &nbsp;·&nbsp; Bauru — SP &nbsp;·&nbsp; Brasil<br>
Sony ZV-E10 &nbsp;·&nbsp; street &nbsp;·&nbsp; nocturne &nbsp;·&nbsp; cotidiano &nbsp;·&nbsp; arquitetura
</p>

</div>

---

## Sobre o Projeto

Portfolio pessoal de fotografia urbana construido do zero, sem templates, sem CMS, sem frameworks. Um unico arquivo HTML com CSS e JavaScript puros, conectado a um backend real no Supabase e hospedado na Vercel com deploy automatico via GitHub.

O projeto nasceu da vontade de ter um espaco proprio para a fotografia e virou um exercicio completo de desenvolvimento web, do design ao backend, passando por otimizacao de performance, acessibilidade e SEO.

---

## A Fotografia

Encontro nas ruas a minha maior inspiracao. Cada clique e uma tentativa de registrar o que passa despercebido na pressa do dia a dia. Becos, fachadas, cenas noturnas, silhuetas contra a luz, reflexos no asfalto molhado.

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
| **Backend** | Supabase | PostgreSQL para dados e Storage para fotos |
| **Hospedagem** | Vercel | Deploy automatico a cada push no GitHub |
| **Tipografia** | Cormorant Garamond · DM Sans | Google Fonts com carregamento nao bloqueante |
| **Favicon** | SVG inline | Sem arquivo externo, carrega instantaneo |

---

## Funcionalidades do Portfolio

O portfolio publico oferece uma experiencia visual completa com 5 modos de layout configuravel para o grid de fotos: grade de 2, 3 ou 4 colunas, masonry com alturas livres e modo destaque com foto principal ampliada. Cada foto abre em um lightbox com navegacao por teclado, painel lateral de especificacoes tecnicas (camera, lente, ISO, abertura, velocidade) e fundo desfocado dinamico.

As fotos sao agrupadas em series tematicas com modal proprio, animacao de entrada escalonada e descricao da colecao. O hero da pagina inicial exibe uma foto de fundo configuravel com animacao de zoom suave. O menu mobile e um overlay fullscreen com animacao de entrada nos itens de navegacao.

---

## Performance e Acessibilidade

O site foi construido com foco em performance real, sem bibliotecas de UI, sem framework JavaScript e sem etapas de build. Todo o codigo roda diretamente no browser.

Algumas otimizacoes aplicadas: fonts carregadas de forma nao bloqueante via preload, `fetchpriority="high"` na primeira imagem para acelerar o LCP, preconnect ao Supabase e dns-prefetch ao CDN, requests ao banco agrupados em paralelo com `Promise.all` e settings combinados em uma unica query.

Na acessibilidade: `<main>` landmark, `aria-label` em todos os controles interativos, `alt` descritivo em todas as imagens, navegacao completa por teclado no lightbox e estrutura semantica com Schema.org para Person, WebSite e ImageGallery.

**Lighthouse**

| Metrica | Desktop | Mobile |
|---|---|---|
| **Performance** | 99 / 100 | 88 / 100 |
| **Acessibilidade** | 100 / 100 | 100 / 100 |
| **Praticas recomendadas** | 100 / 100 | 96 / 100 |
| **SEO** | 100 / 100 | 92 / 100 |

A principal limitacao no score mobile e o tamanho original das imagens armazenadas no Supabase, algo controlado pelo conteudo do usuario e nao pelo codigo.

---

## SEO

Implementacao completa de metadados: Open Graph para preview em redes sociais, Twitter Card, canonical URL, metadados de idioma e localizacao geografica. Dados estruturados em JSON-LD seguindo o padrao Schema.org com tres blocos: Person, WebSite com SearchAction e ImageGallery. O arquivo `robots.txt` e valido e o sitemap e reconhecido pelo Google Search Console.

---

## Estrutura do Repositorio

```
/
├── index.html          site completo
├── vercel.json         headers de seguranca, cache e cleanUrls
├── banner.svg          banner do README
├── og-image.png        preview para redes sociais (1200x630)
├── favicon.ico
└── README.md
```

---

## Sobre

De dia, **analista de logistica** com foco em processos, fluxos operacionais e analise de dados. Nas horas livres, fotografo nas ruas de Bauru e entusiasta de **programacao** e **inteligencia artificial**.

Este portfolio e o resultado de unir essas tres areas. A fotografia forneceu o conteudo, a programacao construiu o espaco, e a IA foi uma ferramenta de estudo e experimentacao ao longo do desenvolvimento.

| | |
|---|---|
| **Logistica** | Analise de processos, fluxos operacionais e dados |
| **Fotografia** | Street photography, arquitetura e cotidiano urbano |
| **Desenvolvimento** | HTML · CSS · JavaScript · integracao com APIs |
| **Inteligencia Artificial** | Entusiasta de automacao, LLMs e ferramentas de IA |

---

<div align="center">

```
feito com camera na rua e codigo no terminal
```

*Desenvolvido com auxilio de inteligencia artificial como parte de estudos e experimentos em desenvolvimento web. Todo o conceito, conteudo e direcao criativa sao autorais.*

</div>
