# 📝 Blog com Strapi (CMS headless)

Back-end de um blog feito com **Strapi 5**, um CMS headless: o painel administrativo permite cadastrar posts, autores e categorias, e o conteúdo é entregue por uma API REST para qualquer front-end.

![Strapi](https://img.shields.io/badge/Strapi_5-4945FF?style=flat&logo=strapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat&logo=cloudinary&logoColor=white)

## ✨ O que tem

- Tipos de conteúdo: **Post**, **Autor**, **Categoria**, **Sobre** e **Global** (configurações do site)
- Componentes reutilizáveis: texto rico, citação, mídia, slider e SEO
- Banco **PostgreSQL no Supabase**
- Upload de imagens no **Cloudinary**
- `docker-compose.yml` para subir o banco localmente
- Script de seed com conteúdo de exemplo

## 🚀 Como rodar

```bash
git clone https://github.com/LucianoMachadoS/blog-strapi.git
cd blog-strapi
npm install
```

Crie um `.env` com `DATABASE_CLIENT=postgres`, os dados de conexão do banco (`DATABASE_HOST`, `DATABASE_PORT`, `DATABASE_NAME`, `DATABASE_USERNAME`, `DATABASE_PASSWORD`, `DATABASE_SSL=true`) e as chaves do Cloudinary (`CLOUDINARY_NAME`, `CLOUDINARY_KEY`, `CLOUDINARY_SECRET`). Depois:

```bash
npm run develop
```

Painel em `http://localhost:1337/admin`.

---
Projeto desenvolvido no curso [JavaScript e TypeScript do básico ao avançado](https://www.udemy.com/course/curso-de-javascript-moderno-do-basico-ao-avancado/) (Luiz Otávio Miranda, Udemy).
Feito por [Luciano Machado](https://github.com/LucianoMachadoS) · [LinkedIn](https://www.linkedin.com/in/luciano-machado-9253a1265/)
