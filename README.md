[README.md](https://github.com/user-attachments/files/26165034/README.md)
# Willian Villares | Photography Portfolio

> Portfólio pessoal de fotografia urbana — desenvolvido do zero como projeto pessoal.

---

## 📷 Sobre o Hobby

A fotografia entrou na minha vida como uma forma de olhar diferente para o cotidiano. Encontro nas ruas a minha maior inspiração — a arquitetura, o movimento, a luz que muda a cada hora, as pessoas e os espaços que geralmente passam despercebidos na pressa do dia a dia.

Meu estilo é urbano: becos, fachadas, cenas noturnas, reflexos, silhuetas. Fotografo principalmente em **Bauru — SP** com uma **Sony ZV-E10**, explorando o que há de poético na vida comum das cidades brasileiras.

A câmera se tornou uma extensão do olhar — cada clique é uma tentativa de registrar o que não volta.

---

## 🌐 Sobre o Site

Este portfólio foi construído como um projeto pessoal completo, do zero — design, backend e deploy.

### Tecnologias utilizadas

| Camada | Tecnologia |
|---|---|
| Frontend | HTML, CSS e JavaScript puros (single file) |
| Backend / Banco de dados | [Supabase](https://supabase.com) — PostgreSQL + Storage |
| Hospedagem | [Vercel](https://vercel.com) |
| Fontes | Cormorant Garamond + DM Sans via Google Fonts |

### Funcionalidades

- **Portfólio dinâmico** — fotos carregadas do Supabase, com ordem e layout configuráveis
- **Modo de layout** — grade 2, 3 ou 4 colunas, masonry e destaque, salvos no banco e refletidos no site em tempo real
- **Séries/Coleções** — agrupamento de fotos por tema com modal de visualização
- **Painel Admin** — gerenciamento completo de fotos, séries, categorias e hero via interface visual protegida por senha
- **Ordenação por drag & drop** — reposicione as fotos arrastando e publique com um clique
- **Modo destaque (Spotlight)** — layout com foto principal grande e miniaturas ao lado
- **Lightbox** — visualização expandida com navegação por teclado e informações técnicas da foto
- **SEO completo** — meta tags, Open Graph, Schema.org (Person, WebSite, ImageGallery)
- **Performance otimizada** — Lighthouse 98/100 desktop, 89/100 mobile

### Deploy

O site roda na Vercel conectado a este repositório. Cada push na branch principal gera um deploy automático.

```
https://wvillares-photography.vercel.app
```

---

## 👨‍💼 Sobre mim

Sou **analista de logística** de dia — trabalho com processos, fluxos e dados operacionais. Fora do trabalho, sou entusiasta de **programação e inteligência artificial**, sempre explorando como a tecnologia pode resolver problemas reais ou simplesmente criar coisas interessantes.

Este portfólio é um bom exemplo disso: nasceu da vontade de ter um espaço próprio para a fotografia e virou um projeto técnico completo — com backend, painel de administração, otimização de performance e deploy automatizado.

**Interesses:**
- 📦 Logística e otimização de processos
- 📸 Fotografia urbana
- 💻 Desenvolvimento web
- 🤖 Inteligência Artificial e automação

---

## 📁 Estrutura do repositório

```
/
├── index.html          # Site completo (frontend + JS inline)
├── vercel.json         # Configurações de deploy e headers HTTP
├── favicon.ico         # Ícone do site
├── favicon-32x32.png
├── apple-touch-icon.png
├── og-image.png        # Imagem para preview em redes sociais
└── README.md
```

---

## 🚀 Como rodar localmente

Basta abrir o `index.html` no browser. O site conecta automaticamente ao Supabase — as fotos e configurações são carregadas em tempo real.

> O painel admin é acessível via atalho `Alt + A` ou 5 cliques no nome do rodapé.

---

*Feito com curiosidade, café e muitas horas de câmera na rua.*
