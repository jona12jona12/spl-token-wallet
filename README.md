This repository contains the code needed to recover your seed phrase when you have the sollet.io vault data. Forked from https://github.com/project-serum/spl-token-wallet.git.

I modified the `wallet-seed.js` and the `LoginPage.js` files to read from given variables instead of Chrome Cache.

Please refer to this article for context: https://medium.com/@alevymyers/recovering-a-lost-seed-phrase-from-sollet-io-windows-10-97a59e61ae08

# SPL Token Wallet

Example Solana wallet with support for [SPL tokens](https://spl.solana.com/token) and Serum integration.

See [sollet.io](https://www.sollet.io) or the [Sollet Chrome Extension](https://chrome.google.com/webstore/detail/sollet/fhmfendgdocmcbmfikdcogofphimnkno) for a demo.

Wallet keys are stored in `localStorage`, optionally encrypted by a password.

Run `yarn start` to start a development server or `yarn build` to create a production build that can be served by a static file server.

See the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started) for other commands and options.
