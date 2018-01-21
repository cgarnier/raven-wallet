# Raven-coin

> A dockerized RavenCoin wallet

# Usage

  * Run ravend

```bash
docker run --rm --name raven-wallet -v "$HOME/.raven:/root/.raven" -d raven-wallet
```

  * Run commands
```bash
docker exec -it raven-wallet raven-cli getblockchaininfo
```

# Caution

You should volume `/root/.raven` to be sure to persist your wallet data.
