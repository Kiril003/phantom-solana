# Releases

The current build for evaluation is in this repository: [nightpost.apk](https://github.com/Kiril003/phantom-solana/raw/main/nightpost.apk). The same file is served at [phantom-os.dev/download](https://phantom-os.dev/download).

| | |
|---|---|
| Build | 17 (`versionCode 17`, versionName `0.1.0-tier1+353c226e`) |
| Android | 10 or newer (minSdk 29), arm64-v8a |
| Size | 74.6 MB |
| SHA-256 | `97d2506d68d425d40b0d0b02ab8b9beb5c72e2f247ae805edfd8545d4b1bde49` |
| Signing certificate SHA-256 | `d249e0fb73743d219047fc18ece1eaffdf193892f1c859a6b7af46cd98be4357` |
| Network | Solana devnet, test funds, no real money |

Check it yourself:

```bash
sha256sum nightpost.apk
apksigner verify --print-certs nightpost.apk
```

Mainnet comes only after an independent security audit.
