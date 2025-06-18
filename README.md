
# Solana Explorer

Solex is a user-friendly Solana blockchain explorer offering real-time data. Track network performance, assets, and validator statuses with ease.

## Features

### Dashboard
- **SOL Price:** Real-time SOL price updates.
- **Last Blocks:** Display of the latest blocks on the Solana blockchain.
- **Transactions Per Second (TPS):** Live TPS metrics.
- **Trending Coins:** List of trending coins on Solana.
- **Validators:** Overview of active validators.

### Explorer
- **Wallet Assets:** Track and manage assets in your wallet, including coins and NFTs.

### Validators
- **Network Status:** Current status of the Solana network.
- **Delinquent Validators:** Information on validators that are not performing correctly.

## Getting Started

1. Set the environment variables:
   ```
   cp .env.dist .env
   ```
2. Install dependencies:
   ```
   npm i
   # or
   yarn
   # or
   pnpm i
   # or
   bun install
   ```
3. Run the development server:
   ```
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses `next/font` to automatically optimize and load Inter, a custom Google Font.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the Vercel Platform from the creators of Next.js.

Check out the Next.js deployment documentation for more details.

## Contributing

We welcome contributions from the community! Please fork this repository and submit pull requests.

## License

This project is licensed under the MIT License.

