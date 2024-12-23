
# SolanaWallet

A modern Solana wallet interface built with Next.js, TailwindCSS, ShadCN, Framer Motion, and v0 AI. This project was created as part of a frontend development workshop to showcase the integration of development, design, and web3 technologies.

## Features

- **Seamless Wallet Connection**: Easily connect your Solana wallet using `@solana/wallet-adapter-react`.
- **Token & Balance Management**: View your public key and current SOL balance.
- **Request Airdrop**: Get testnet SOL for development purposes.
- **Responsive UI**: Built with TailwindCSS for mobile-first design.
- **Animations**: Smooth animations with Framer Motion.

---

## Technologies Used

- **[Next.js](https://nextjs.org/)**: React framework for server-side rendering and static site generation.
- **[TailwindCSS](https://tailwindcss.com/)**: Utility-first CSS framework for rapid UI development.
- **[ShadCN](https://ui.shadcn.com/)**: Pre-configured TailwindCSS components for UI consistency.
- **[Framer Motion](https://www.framer.com/motion/)**: Powerful animation library for React.
- **[v0 AI](https://v0.dev/)**: Advanced generative AI tools for enhanced coding efficiency.

---

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/FPLCodes/frontend-workshop-superteam.git
   cd frontend-workshop-superteam
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm run dev
   ```

4. **Visit your app:**

   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## How It Works

1. **Wallet Integration**: 
   The wallet connection is handled using the `@solana/wallet-adapter-react` library.
2. **Balance Updates**: 
   Automatically fetches the wallet balance every 10 seconds using Solana's web3 API.
3. **Airdrop Feature**: 
   Allows users to request airdrops on the testnet with error handling for rate limits.

---

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the application for production.
- `npm run start`: Start the production server.

---

Enjoy coding and building decentralized applications on the Solana blockchain! 🚀
