<div align="center">
    <h1>🥪 SOL SANDWICH BOT 🥪</h1>



</div>

---

<p align="center">
    <img src="https://img.shields.io/github/stars/sendlify/SolSandwich-Solana-Sandwich-bot">
    <img src="https://img.shields.io/github/forks/sendlify/SolSandwich-Solana-Sandwich-bot">
    <br>
    <img src="https://img.shields.io/github/issues/sendlify/SolSandwich-Solana-Sandwich-bot">
    <img src="https://img.shields.io/github/issues-closed/sendlify/SolSandwich-Solana-Sandwich-bot">
    <br>
    <img src="https://img.shields.io/github/languages/top/sendlify/SolSandwich-Solana-Sandwich-bot">
    <img src="https://img.shields.io/github/last-commit/sendlify/SolSandwich-Solana-Sandwich-bot">
    <br>
</p>

# 📖 Introduction
**SolSandwich** is a Sandwich bot that Frontruns and sandwiches a determined number of transactions on  **[Solana]() featuring**  a **Fast** but EXPERIMENTAL sniper bot.<br>

![SolSandwich](https://i.imgur.com/74EZzVS.png)



# ✨ Quickstart

This project has been made for Python 3.11

## 🛠️ Installation

💾 **Clone this repository**
```sh
Download this repository
```
💻 **Install the required libs**
```sh
pip install -r requirements.txt
```
▶️ **Start**
```sh
python main.py
```


# 🥪 SANDWICH FEATURES
You can modify your settings as follows:
- Pair to follow
- Address
- Selected Wallet
- Sandwich Amount
- Jito Tip
- Tx Slippage
- Priority Fees






# 🤖 Sniper Bot [EXPERIMENTAL]
**On top of most of the SolSandwich features that you can use, you are also able to snipe tokens.**

❗**Please note that the Sniper Bot Feature is experimental and subject to changes as there might be issues that I didn't notice.**

### ⚙️ How it works
Each second, the bot will send a GET request to **Solana**.

If there is a route available for a determined token, it will then execute it.

Please note that only tokens with sufficient liquidity and on-chain metadata are listed on Jupiter APIs: min. 250$ liquidty and buy/sell price impact are below 30%.
When these criteria are met, it will take a few seconds to automatically add the pair.

### 🆕 Add a token to snipe [EXPERIMENTAL]
- `⚡ Fast WSOL/USDC Sniper`
- `📈 Automated Trading`
- `💰 Take Profit/Stop Loss`
- `💧 Minimum Liquidity Check`
- `🔒 Token Security (Burn/Lock Check)`
- `✅ Ownership Renounce Check`
- `🚄 High-Speed Execution`

If token has a launch date:
- `Month`
- `Day`
- `Hours`
- `Minutes`



# 🗨️ Q&A
### Where are my private keys?
*Your private keys are stored in `wallets.json`.*
### Is there any fees when swapping using SolSandwich?
*There are no additional fees when performing swaps via the CLI; the costs should be the same as using the Jupiter UI.*
### Does sniper bot remains running if I close the SolSandwich?
*If you close SolSandwich, the sniper bot will stop running.*
### Is it possible to swap EVERY token?
*You can only swap tokens that are listed on Jupiter and pumpfun based on their criterias.*


# 📝 TO-DO
- [x] Clean up code ⚡
- [x] Add docstrings 📑
- [x] Display tokens owned 🪙
- [x] Favorite tokens displayed in first tokens for swap/limit orders/dca... ⭐
- [ ] Wallet Duplication detection
- [x] Display message when swap failed (slippage error...)
- [x] Disable swap / limits orders / etc, if not enough $SOL to cover the tx fees
- [x] Give possibility to exit current choice (swap, limit order, dca, donation...) 🏃🚪
- [ ] Adjust Wallets ID when one is deleted
- [x] Bridge 🌉
- [ ] Perpetual 💸
