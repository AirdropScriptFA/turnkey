# 🔐 Turnkey Automation Script

Automate tasks using wallet addresses, proxies, and private keys with ease.

## 📁 Files Overview

- `index.js` – Main script logic  
- `package.json` – Dependencies  
- `pk.txt` – Private key(s) for authentication  
- `proxy.txt` – List of proxies  
- `wallet.txt` – List of wallet addresses  
- `LICENSE` – License info  
- `README.md` – Project documentation  

---

## ⚙️ Installation & Setup

Follow these steps to get started:

```bash
git clone https://github.com/AirdropScriptFA/turnkey.git
cd turnkey
```

```bash
npm i
```

### 🔑 Configure Files

1. Add your private key:
   ```bash
   nano pk.txt
   ```
   > Enter your private key (you can get it from the respective site or app).

2. Add your proxy list:
   ```bash
   nano proxy.txt
   ```
   > Format: `ip:port` or `ip:port:user:pass` (one per line)

3. Add wallet addresses:
   ```bash
   nano wallet.txt
   ```
   > Add one wallet per line. You can use different wallets.

---

## ▶️ Run the Script

```bash
npm start
```

---

## 📝 Notes

- Ensure the number of proxies and wallets matches or is sufficient for your use-case.
- Never share your `pk.txt`, `proxy.txt`, or private files.

---

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 🌐 Community & Support

- Telegram: [@forestarmy](https://t.me/forestarmy)  
- YouTube: [Forest Army Channel](https://youtube.com/forestarmy)

> Thank You NT EXHAUST 
