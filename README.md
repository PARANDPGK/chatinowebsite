# CHATINO — Official Website

A bilingual (Persian/English), responsive React + TypeScript + Vite landing page for the Chatino Telegram service.

## Requirements
- Node.js 20.19+ or 22.12+
- npm

## Run locally
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
npm run preview
```

The production output is generated in `dist/` and can be deployed to any static hosting provider (Nginx, Cloudflare Pages, Vercel, Netlify, etc.).

## Brand assets
- `src/assets/logos/chatino-primary.jpg`: supplied blue/purple primary mascot.
- `src/assets/logos/chatino-support.jpg`: supplied green support mascot.

Both supplied logo files are used as-is. The page includes official links to:
- Bot: https://t.me/TheChatinoBot
- Channel: https://t.me/TheChatino
- Support: https://t.me/ChatinoTeam

## Notes
- Language preference is saved in localStorage.
- The page intentionally avoids unverified feature claims, fake statistics, forms, or fictional product screenshots.
- Google Fonts are referenced as optional remote typography. For fully self-hosted deployment, place licensed Peyda/Estedad font files in `src/assets/fonts` and add local `@font-face` declarations in `src/styles/global.css`.
