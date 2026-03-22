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

Portfólio pessoal de fotografia urbana construído do zero, sem templates, sem CMS, sem frameworks. Um único arquivo HTML com CSS e JavaScript puros, conectado a um backend real no Supabase e hospedado na Vercel com deploy automático via GitHub.

O projeto nasceu da vontade de ter um espaço próprio para a fotografia e virou um exercício completo de desenvolvimento web, do design ao backend, passando por otimização de performance, acessibilidade e SEO.

---

## A Fotografia

Encontro nas ruas a minha maior inspiração. Cada clique é uma tentativa de registrar o que passa despercebido na pressa do dia a dia. Becos, fachadas, cenas noturnas, silhuetas contra a luz, reflexos no asfalto molhado.

A câmera não como instrumento de registro, mas de **leitura da cidade**.

| | |
|---|---|
| **Câmera** | Sony ZV-E10 |
| **Lente** | 16–50mm f/3.5–5.6 OSS |
| **Base** | Bauru — SP, Brasil |
| **Estilos** | Street · Nocturne · Cotidiano · Arquitetura |

---

## Stack Técnica

| Camada | Tecnologia | Detalhe |
|---|---|---|
| **Frontend** | HTML · CSS · JavaScript | Single file, zero dependências de build |
| **Backend** | Supabase | PostgreSQL para dados e Storage para fotos |
| **Hospedagem** | Vercel | Deploy automático a cada push no GitHub |
| **Tipografia** | Cormorant Garamond · DM Sans | Google Fonts com carregamento não bloqueante |
| **Favicon** | SVG inline | Sem arquivo externo, carrega instantâneo |

---

## Funcionalidades do Portfólio

O portfólio público oferece uma experiência visual completa com 5 modos de layout configurável para o grid de fotos: grade de 2, 3 ou 4 colunas, masonry com alturas livres e modo destaque com foto principal ampliada. Cada foto abre em um lightbox com navegação por teclado, painel lateral de especificações técnicas (câmera, lente, ISO, abertura, velocidade) e fundo desfocado dinâmico.

As fotos são agrupadas em series temáticas com modal próprio, animação de entrada escalonada e descrição da coleção. O hero da página inicial exibe uma foto de fundo configurável com animação de zoom suave. O menu mobile é um overlay fullscreen com animação de entrada nos itens de navegação.

---

## Performance e Acessibilidade

O site foi construído com foco em performance real, sem bibliotecas de UI, sem framework JavaScript e sem etapas de build. Todo o código roda diretamente no browser.

Algumas otimizações aplicadas: fonts carregadas de forma não bloqueante via preload, `fetchpriority="high"` na primeira imagem para acelerar o LCP, preconnect ao Supabase e dns-prefetch ao CDN, requests ao banco agrupados em paralelo com `Promise.all` e settings combinados em uma única query.

Na acessibilidade: `<main>` landmark, `aria-label` em todos os controles interativos, `alt` descritivo em todas as imagens, navegação completa por teclado no lightbox e estrutura semântica com Schema.org para Person, WebSite e ImageGallery.

**Lighthouse**

| Métrica | Desktop | Mobile |
|---|---|---|
| **Performance** | 99 / 100 | 88 / 100 |
| **Acessibilidade** | 100 / 100 | 100 / 100 |
| **Práticas recomendadas** | 100 / 100 | 96 / 100 |
| **SEO** | 100 / 100 | 92 / 100 |

A principal limitação no score mobile é o tamanho original das imagens armazenadas no Supabase, algo controlado pelo conteúdo do usuário e não pelo código.

---

## SEO

Implementação completa de metadados: Open Graph para preview em redes sociais, Twitter Card, canonical URL, metadados de idioma e localização geográfica. Dados estruturados em JSON-LD seguindo o padrão Schema.org com três blocos: Person, WebSite com SearchAction e ImageGallery. O arquivo `robots.txt` é válido e o sitemap é reconhecido pelo Google Search Console.

---

## Estrutura do Repositório

```
/
├── index.html          site completo
├── vercel.json         headers de segurança, cache e cleanUrls
├── banner.svg          banner do README
├── og-image.png        preview para redes sociais (1200x630)
├── favicon.ico
└── README.md
```

---

## Sobre

De dia, **analista de logística** com foco em processos, fluxos operacionais e análise de dados. Nas horas livres, fotógrafo nas ruas de Bauru e entusiasta de **programação** e **inteligência artificial**.

Este portfólio é o resultado de unir essas três áreas. A fotografia forneceu o conteúdo, a programação construiu o espaço, e a IA foi uma ferramenta de estudo e experimentação ao longo do desenvolvimento.

| | |
|---|---|
| **Logística** | Análise de processos, fluxos operacionais e dados |
| **Fotografia** | Street photography, arquitetura e cotidiano urbano |
| **Desenvolvimento** | HTML · CSS · JavaScript · integração com APIs |
| **Inteligência Artificial** | Entusiasta de automação, LLMs e ferramentas de IA |

---

<div align="center">

```
feito com câmera na rua e código no terminal
```

*Desenvolvido com auxílio de inteligência artificial como parte de estudos e experimentos em desenvolvimento web. Todo o conceito, conteúdo e direção criativa são autorais.*

</div>
