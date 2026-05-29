# qubic.eth

10102's thesis on Qubic — the bare metal blockchain. A hub for newcomers, builders, and watchers of the Qubic ecosystem.

Built by [10102](https://10102.io) · part of the [beyond.eth](https://beyond.eth.limo) collection.

Live at: [qubic.eth.limo](https://qubic.eth.limo)

## Stack

Pure HTML / CSS. No JS, no framework, no external dependencies.

```
public/
├── index.html
└── img/
    └── favicon.png   (TODO: add)
```

`.github/workflows/omnipin.yml` deploys `./public` to IPFS via [Omnipin](https://github.com/omnipin/omnipin) and updates the ENS contenthash on `qubic.eth`.

## Deploy

See [DEPLOYMENT.md](./DEPLOYMENT.md).
