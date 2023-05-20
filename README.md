# Forum dApp

## Description
A decentralized forum web application that utilizes smart contracts on the Ethereum testnet and file storage on the Filecoin & IPFS network using web3.storage.

## Usage
The majority of data on the internet today is hosted by large storage providers such as Amazon, Google, and Microsoft. This simplifies the storage of application data for developers, but large corporate platforms like these create silos by locking developers and users alike into walled gardens of services. Furthermore, as the market continues to consolidate, a small oligopoly of providers is essentially becoming the internet's storage backbone.

The solution to this problem is to store data for apps and services on decentralized storage rather than large corporate platforms. Decentralized storage, on the other hand, can be difficult to manage and add extra time and effort to an already overburdened developer workflow and this is where web3.storage comes in. 

## Tools
- There are two smart contracts namely post and postManager
- The post smart contract will record the post information such as the wallet address, image and comments
- The post manager smart contract will hold references to all post smart contracts and will also create the post smart contracts when triggered
- Contents of the posts and comments will be stored on a JavaScript Object Notation (JSON) file and the JSON file will be updated when a post or comment is added
- The JSON file will be stored on the Filecoin and IPFS network through web3.storage and its content identifier (CID) will be stored on the postManager smart contract which will be updated when a post or comment is updated

## Live Demo
https://billowing-lake-2849.on.fleek.co/

## Result
![Create Post](https://github.com/raybnsr/Web-Company-Profile/assets/87411691/09847309-4a27-4053-8c63-9722c1b9efd6)
![Post](https://github.com/raybnsr/Web-Company-Profile/assets/87411691/4cf45443-4cfd-41df-9903-75a55c6d2e2d)


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.
