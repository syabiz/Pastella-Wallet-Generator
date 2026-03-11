# 🌸 Pastella Wallet Generator HTML

A client-side wallet generator for the **[Pastella (PAS)](https://pastella.org)** cryptocurrency — runs entirely in your browser with no data sent to any server.

🔗 **Live Demo:** [https://syabiz.github.io/pages/Pastella-Wallet-Generator/](https://syabiz.github.io/pages/Pastella-Wallet-Generator/)

---

## ✨ Features

### 🔑 Generate New Wallet
Instantly create a brand-new Pastella wallet with:
- A **25-word mnemonic seed phrase**
- **Wallet address** (PAS1...)
- **Private key** (Seed Hex)
- **Public key**

All keys can be copied to clipboard with a single click.

---

### 🔁 Recover Wallet from Mnemonic
Already have a wallet? Restore it by entering your **25 mnemonic words** (space-separated) to retrieve your address, private key, and public key.

---

### 🎨 Vanity Address Generator
Search for a custom Pastella address that contains a specific pattern after the `PAS1` prefix.

**Options:**
| Setting | Description |
|---|---|
| **Pattern** | The text you want to appear in your address (Base58 characters) |
| **Max Trials** | Maximum number of attempts before stopping |
| **Pattern Position** | Match at the beginning (after `PAS1`) or anywhere in the address |
| **Case Sensitive** | Toggle whether the search is case-sensitive |

Live stats are shown during search: trials count, wallets/second speed, and elapsed time.

---

## 🔒 Privacy & Security

> ⚠️ **Security Warning:** Never share your private key or mnemonic seed with anyone. Anyone who has your mnemonic can access your funds completely. Make sure no one is watching your screen when creating a new wallet.

- ✅ **100% client-side** — all computation happens in your browser
- ✅ **No server communication** — no data is ever transmitted
- ✅ **No installation required** — open the page and use it directly

---

## 🚀 Usage

Simply open the [live demo](https://syabiz.github.io/pages/Pastella-Wallet-Generator/) in any modern browser.

Or clone and run locally:

```bash
git clone https://github.com/syabiz/Pastella-Wallet-Generator.git
cd Pastella-Wallet-Generator
# Open index.html in your browser
```

---

## 🔗 Pastella Network Links

| Resource | Link |
|---|---|
| 🌐 Main Site | [pastella.org](https://pastella.org) |
| 🔍 Explorer | [explorer.pastella.org](https://explorer.pastella.org) |
| ⛏️ Mining Pool | [pool.pastella.org](https://pool.pastella.org) |

---

## 👤 Author

Created by **[Syabiz](https://github.com/syabiz)**

---

## ☕ Support

If this tool has been helpful to you, perhaps there's a reward of a cup of coffee and a pack of cigarettes for me? 😄

| Network | Address |
|---|---|
| 🪙 Pastella (PAS) | `PAS1Dj6xgtVS56REDFbheSJe76ac44fq1dY4obnUgzSj2JGkVPGUDB` |
| ₿ Bitcoin (BTC) | `bc1qn6t8hy8memjfzp4y3sh6fvadjdtqj64vfvlx58` |
| ⟠ Ethereum (ETH) | `0x512936ca43829C8f71017aE47460820Fe703CAea` |
| ◎ Solana (SOL) | `6ZZrRmeGWMZSmBnQFWXG2UJauqbEgZnwb4Ly9vLYr7mi` |

Every bit of support is deeply appreciated! 🙏

---

## 📄 License

This project is open source. See the repository for license details.
