# LayerEdge BOT

## 🚨 Attention Before Running LayerEdge Script

- Do All the steps carefully for Errorless run !

## LayerEdge Node cli version Script features

- Auto check in
- Auto task
- Auto verify twitter
- Support proxy/no proxy
- Mutiple threads, multiple accounts

## RUNNING

- Clone Repository

```bash
git clone https://github.com/Not-D4rkCipherX/Layeredge-X.git
cd Layeredge-X
npm install
```

- Setup ``config.js`` if needed to customize options then

```bash
nano config.js
```

## Proxy (optional): http://user:pass@ip:port

```bash
nano proxy.txt
```

## Wallet Setup =>

```bash
nano wallets.json
```
- Insert your Wallet privatekeys in ``wallets.json``,
- Example =>
```bash
[
    {
      "address": "adrress here",
      "privateKey": "privatekey here"
    },
    {
      "address": "adrress_2 here",
      "privateKey": "privatekey_2 here"
    }
  ]
  ```

- Run the script

```bash
node main.js or node main-thread.js
```
