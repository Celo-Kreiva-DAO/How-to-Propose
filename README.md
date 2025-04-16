# How-to-Propose (Testnet)
This guide will take you through a step by step guide on how to propose to Celo Kreiva testnet
## Note Owning our NFTs gives you governance power! This whitelist mimics it, but since Snapshot doesn't support Alfajores natively and can’t fetch Alfajores NFT balances directly, we will be using the Sepolia testnet network for the voting. 

## Step 1: Meta Mask Setup (Alfajores)
### 🔧 Manual Setup
Open MetaMask and navigate to:
Click on your account icon → Settings → Networks → Add Network.​
Enter the following network details:
```
Network Name: Celo Alfajores

New RPC URL: https://alfajores-forno.celo-testnet.org

Chain ID: 44787

Currency Symbol: CELO

Block Explorer URL: https://alfajores.celoscan.io​
CoinFactory
```
Save the network to add it to your MetaMask.

## Step 2 Get Testnet Celo Tokens
### 🔗 Official Celo Alfajores Faucet
Visit: faucet.celo.org/alfajores

Enter your wallet address: Input your Celo-compatible wallet address (e.g., from MetaMask).

Complete the CAPTCHA: Verify you're not a bot.

Claim tokens: Click "Add Funds" to receive testnet CELO tokens.​
Celo Faucet

Note: Authenticating with GitHub can increase your token allowance per request.

## Step 3 Buy NFT
### 🎨 Rarible Testnet
* Visit https://testnet.rarible.com/items/collections
  
* Connect wallet, ensure you are on Alfajores network
  
* Purchase NFT with alfajores Celo Tokens
  
* Purchase [verification](https://alfajores.celoscan.io/tx/0xdd78654f065f5f19a8a9d839335690fc7cc147a7683b9dfb767406ee11216095)

## Step 4 Proposing & Voting
### ⚡️Visit https://testnet.snapshot.box/
* Click on New proposal to make a new Propose

* Click "For", "Against" or "Abstain" on an exsisting proposal.

Here is a demonstration:
[Snapshot Testnet](https://testnet.snapshot.box/#/s-tn:celokreiva.eth/proposal/0xcacf3f360f7a6caa7747ef036f100f8220fcc7fd1e720240af4c6df8cf2ae2d4)

```json
{
  "address": "0x8E2E9e58Ca4833D5c5C542C027849B46b921142E",
  "sig": "0x3e31b260bc23b25aff07767bbd8d8c4642d0687bb8efcd64ee208cb7d6877ad87a624df53df16c3a196ae3e4f5b3e23dd88a1b3908dfb5e6b2f92e675a3e55ea1c",
  "hash": "0xcacf3f360f7a6caa7747ef036f100f8220fcc7fd1e720240af4c6df8cf2ae2d4",
  "data": {
    "domain": {
      "name": "snapshot",
      "version": "0.1.4"
    },
    "types": {
      "Proposal": [
        {
          "name": "from",
          "type": "address"
        },
        {
          "name": "space",
          "type": "string"
        },
        {
          "name": "timestamp",
          "type": "uint64"
        },
        {
          "name": "type",
          "type": "string"
        },
        {
          "name": "title",
          "type": "string"
        },
        {
          "name": "body",
          "type": "string"
        },
        {
          "name": "discussion",
          "type": "string"
        },
        {
          "name": "choices",
          "type": "string[]"
        },
        {
          "name": "labels",
          "type": "string[]"
        },
        {
          "name": "start",
          "type": "uint64"
        },
        {
          "name": "end",
          "type": "uint64"
        },
        {
          "name": "snapshot",
          "type": "uint64"
        },
        {
          "name": "plugins",
          "type": "string"
        },
        {
          "name": "privacy",
          "type": "string"
        },
        {
          "name": "app",
          "type": "string"
        }
      ]
    },
    "message": {
      "from": "0x8E2E9e58Ca4833D5c5C542C027849B46b921142E",
      "timestamp": 1744788447,
      "space": "celokreiva.eth",
      "title": "Test Proposal",
      "body": "\"Owning our NFTs gives you governance power! This whitelist mimics it, but we need Snapshot to support Alfajores natively.\"",
      "type": "basic",
      "discussion": "",
      "choices": [
        "For",
        "Against",
        "Abstain"
      ],
      "privacy": "",
      "labels": [],
      "start": 1744788447,
      "end": 1744788747,
      "snapshot": 8128872,
      "plugins": "{}",
      "app": "snapshot-v2"
    }
  }
}
```
