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

## Setup Sol Transfer Transaction

Step 1: create new Transaction

Step 2: create instruction using systemProgram.transfer({add required params})

Step 3: Add instruction into transaction

Step 4: Add recent blockhash using connection.getLatestBllockhash().blockhash

Step 5: Sign transaction using wallet.signTransaction(transaction)

Step 6: serialize transaction using signedTx.serialize()

Step 7: send transaction using connection.sendRawTransaction(rawTransaction)

Step 8: console.log(transcation signature)
