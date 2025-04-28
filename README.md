# Projet Award

Application de vote pour les awards Discord. Permet aux membres d'un serveur Discord de se connecter et de voter pour différentes catégories.

## Fonctionnalités

- Authentification avec Discord
- Salle d'attente en temps réel
- Système de vote
- Affichage des résultats

## Configuration

### Variables d'environnement requises

```env
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=votre_secret
DISCORD_CLIENT_ID=votre_client_id
DISCORD_CLIENT_SECRET=votre_client_secret
DISCORD_GUILD_ID=votre_guild_id
```

### Installation

```bash
npm install
npm run dev
```

### Production

Le projet est configuré pour être déployé sur Vercel. Assurez-vous d'ajouter les variables d'environnement dans les paramètres du projet Vercel.

## Développement

```bash
# Lancer en mode développement
npm run dev

# Build pour la production
npm run build

# Lancer en production
npm run start
```

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
