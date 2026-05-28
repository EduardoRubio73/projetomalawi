# Nação Ubuntu Malawi — Doe Saúde

Campanha de arrecadação de medicamentos para a Caravana da Saúde 2026 no Malawi.

## Estrutura

```
nacao-ubuntu/
├── index.html          # Página principal
├── manifest.json       # PWA manifest
├── vercel.json         # Config Vercel
└── public/
    ├── favicon.ico
    └── icons/
        ├── icon-16x16.png
        ├── icon-32x32.png
        ├── icon-48x48.png
        ├── icon-180x180.png    (Apple Touch Icon)
        ├── icon-192x192.png    (Android)
        └── icon-512x512.png    (PWA splash)
```

## Deploy no Vercel

1. Abra o projeto no VSCode
2. Instale o Vercel CLI (opcional): `npm i -g vercel`
3. Rode: `vercel` na raiz do projeto
4. Ou conecte o repositório no painel [vercel.com](https://vercel.com)

## Funcionalidades

- ✅ Link WhatsApp com mensagem pré-preenchida para Izabel
- ✅ Botão copiar chave PIX (Ricardo Alves Marujo)
- ✅ Busca de medicamentos na lista
- ✅ Totalmente responsivo (mobile-first)
- ✅ PWA com ícones e manifest
- ✅ SEO básico (meta tags + OG)
- ✅ Navegação fixa com smooth scroll
