# Simulador Token Futebol — PWA

## Publicar (precisa de HTTPS para instalar)
Suba a pasta inteira em qualquer host estático: Vercel, Netlify, Cloudflare Pages, GitHub Pages ou sua VPS (Caddy/Nginx).

- Vercel: `npx vercel --prod` dentro da pasta
- Netlify: arraste a pasta em app.netlify.com/drop
- Caddy: `file_server` apontando para a pasta

Abrir o `index.html` direto do gerenciador de arquivos (content:// ou file://) NÃO ativa o PWA.

## Instalar no celular
- Android/Chrome: botão "📲 Instalar App" no topo (ou menu ⋮ → Instalar app)
- iPhone/Safari: Compartilhar → Adicionar à Tela de Início

## Atualizar versão
Ao alterar arquivos, mude `CACHE = 'token-futebol-vN'` em `sw.js`.

## Arquivos
index.html · manifest.json · sw.js · vendor/jspdf.umd.min.js · icons/
