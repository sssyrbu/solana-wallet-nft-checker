# Solana-Wallet-NFT-Checker
### Here's a tool that provides info regarding recent activities (such as purchase, sale or listing of an NFT) and outputs name of the NFT collection, link to the item on MagicEden marketplace and the price. 
This tool provies info on 4 kinds of activities: list, buy, sell, delist. It is done with official Magic Eden API. 
There are two versions of the tool: discord bot and terminal program. Feel free to use it!

### 1. Terminal version
   ```
    pip install -r requirements.txt
   ```
  Ensure that you're using python version 3.10+
  ```
    python3 --version
  ```
  Type the wallet you're interested in in the required field and wait for any updates from the wallet. 

### 2. Discord bot version
  Install it on VPS or run in locally on your computer. Make sure to past your discord bot token on the 8th line:
  ```
    TOKEN = "YOUR TOKEN"
  ```
  Type /check as a discord command and then paste the wallet address as attribute and wait for updates.

  ## Feel free to use this tool while Solana hasn't gone extinct.
