# FerretHood website

## Quick deploy
This is a static website. No server or paid hosting is required.

### Local test
Open `index.html` in a browser, or use any static-file server.

### Free hosting
Upload this folder to GitHub Pages, Cloudflare Pages, Netlify, or Vercel.

## Contract
Address: 0x39008E8f6Eb9a36C6864f95FBBaC75101e842f08
Chain ID: 4663 (Robinhood Chain)
Mint price is read from the deployed contract.
Max mint per transaction is read from the deployed contract.

## Important
The site only requests a wallet connection and a native ETH payment for minting. Never ask users for seed phrases or private keys.

Whitelist support:
The deployed contract requires a Merkle proof for whitelistMint(). This first version prepares the public mint flow. To enable whitelist minting on the site, add the whitelist address/proof data to the frontend after the final whitelist is available.
