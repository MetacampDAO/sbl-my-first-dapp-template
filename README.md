# sbl-my-first-dapp-template

## Setup Wallet Adapter

Step 1: Google "solana wallet adapter"

Step 2: Click on **solana-labs**/wallet-adapter

Step 3: In the readMe file, click "For Solana Apps"

Step 4: Install the dependencies: $ yarn install

Step 5: Create a file named **Wallet.tsx** and paste the setup code provided by Solana labs

Step 6: Update required to import (line 13)

Step 7: Remove UnsafeBurnerWalletAdapter (Line 36), and add new walletAdapter

Step 8: take {children} as props and paste it inside the provider

Step 9: Wrap <App /> with the Wallet in main.tsx file

Step 10: Access connection via useConnection, and walllet via useWallet in the app.
