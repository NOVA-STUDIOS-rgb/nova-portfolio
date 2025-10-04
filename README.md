# NOVA Studios — Website

Site institucional da **NOVA Studios**, focado em **desenvolvimento de sites** (Landing Pages, Institucionais e Portfólios) com design **corporativo + moderno**.

## 🚀 Tecnologias
- HTML5 semântico + CSS externo (`assets/style.css`) + JS mínimo
- Hospedagem: **GitHub Pages** (estático) — também compatível com Netlify
- Imagens e ícones em `/assets` (SVG + PNG)

## 🧩 Estrutura
```
/ (raiz)
├─ index.html
├─ assets/
│  ├─ style.css
│  ├─ logo.svg | logo-dark.svg | logo-light.svg
│  ├─ favicon.svg | favicon-512.png | favicon-180.png | favicon-32.png
│  └─ social-cover-1200x630.png
```
Seções do `index.html`: Início, Serviços, Portfólio, **Depoimentos**, Processo, Planos, Sobre e Contato.

## 🎨 Identidade Visual
- Primária: `#00BCD4` • Secundária: `#00A2B8`
- Fundo: `#0A1220` • Texto: `#E9EEF6` • Muted: `#A7B1C2`
- Fontes: **Poppins** (títulos), **Inter** (texto)

## 🔗 Configurações que você deve alterar
- **WhatsApp**: procure por `https://wa.me/5521975226075` e ajuste se necessário (formato `https://wa.me/55DDDNUMERO`).
- **E-mail**: `nova.studios.art@outlook.com` → troque pelo seu se preferir.
- **Portfólio**: substitua `assets/work-*.jpg` pelos seus prints e ajuste `alt`/`title`.

## 🧪 SEO & Social (básico)
- `<title>` e `<meta name="description">` já configurados.
- Open Graph + Twitter card com `assets/social-cover-1200x630.png`.
- Boas práticas: títulos `h1/h2`, `alt` nas imagens, performance (CSS externo).
- (Opcional) Sitemap simples: crie `/sitemap.txt` com as URLs públicas.

## ☁️ Publicar no GitHub Pages
1. Faça commit/push de `index.html` e `assets/` na branch `main`.
2. Em **Settings → Pages**, escolha a branch e a pasta `/root`.
3. Acesse: `https://nova-studios-rgb.github.io/nova-portfolio/`

## ✅ Checklist antes de publicar
- [ ] Troquei WhatsApp e e-mail
- [ ] Substituí as imagens do portfólio
- [ ] Conferi a logo em fundo claro/escuro (usar `logo-dark.svg` ou `logo-light.svg` se necessário)
- [ ] Testei no celular (responsividade)

## 🤝 Licença & Créditos
© 2025 NOVA Studios — Todos os direitos reservados.
