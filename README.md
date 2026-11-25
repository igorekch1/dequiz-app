# deQuiz

AI-powered Web3 quiz platform on Base. Users take a quiz, and their results are turned into a unique AI-generated artwork minted as an ERC-721 NFT.

Built as a Web3 hackathon project in 2024 by the EZIC-IO team. My focus was the Web3 integration: wallet interactions, NFT minting, OpenAI image generation and IPFS storage.

- Live demo: https://dequiz-app.vercel.app
- Devfolio (screenshots and demo): https://devfolio.co/projects/dequiz-b35c
- Original repository: https://github.com/EZIC-IO/dequiz-app

## How it works

1. The user connects a wallet and takes a quiz.
2. Quiz results are used to build a prompt for OpenAI image generation.
3. The generated image and NFT metadata are uploaded to IPFS.
4. The user mints a unique ERC-721 NFT on Base.

## Tech stack

- Next.js, React, TypeScript
- Tailwind CSS, shadcn/ui
- Wagmi, thirdweb
- Base (Ethereum L2), ERC-721
- OpenAI API, IPFS
- pnpm, ESLint, Prettier

## Getting started

```bash
pnpm install
cp .env.example .env.local   # fill in the required keys
pnpm dev
```

Then open http://localhost:3000.

## License

Apache-2.0. See [LICENSE](LICENSE).
