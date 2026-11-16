# Servalvo

Protótipo mobile-first em React e Vite para gestão de serviços, com catálogo visual em `/docs/system-ui`.

## Desenvolvimento

Requer Node.js 20.19+ ou 22.12+.

```sh
npm ci
npm run dev
npm run build
npm run preview
```

Os dados do painel são demonstrativos e mantidos apenas na memória. O catálogo contém exemplos interativos e um inventário de componentes planejados; os itens marcados como referência ainda não são componentes implementados. O service worker é ativado no build de produção e mantém recursos visitados em cache para uso offline limitado. Um servidor de produção deve encaminhar rotas da aplicação para `index.html`.
