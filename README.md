# dApp-context-hub

AI context files (`llms.txt`) for dApp protocols. Feed these to LLMs to get accurate, up-to-date integration guidance.

## Protocols

| Protocol | Path | Description |
|---|---|---|
| [OCash](protocols/ocash/llms.txt) | `protocols/ocash/` | Privacy-preserving ZKP SDK (UTXO + zk-SNARK) |
| [PancakeSwap](protocols/pancakeswap/llms.txt) | `protocols/pancakeswap/` | DEX (V3 concentrated liquidity, SmartRouter) |

## Usage

Point your AI tool at the raw file:

```
https://raw.githubusercontent.com/PolyhedraZK/dApp-context-hub/main/protocols/pancakeswap/llms.txt
```

Or clone and reference locally:

```bash
git clone https://github.com/PolyhedraZK/dApp-context-hub.git
```

## Contributing

Add a new protocol:

1. Create `protocols/<protocol-name>/llms.txt`
2. Follow the format: overview, install, quick start, API reference, key types, common pitfalls
3. Keep it concise — LLM context windows are finite
4. Open a PR

## License

MIT
