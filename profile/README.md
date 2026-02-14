<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://rustledger.github.io/og-image.png?v=2">
  <source media="(prefers-color-scheme: light)" srcset="https://rustledger.github.io/og-image.png?v=2">
  <img alt="rustledger - Accounting in plain text" src="https://rustledger.github.io/og-image.png?v=2" width="100%">
</picture>

<p align="center">
  <strong>Accounting in plain text, under your control, forever.</strong>
</p>

<p align="center">
  <a href="https://rustledger.github.io">Website</a> &bull;
  <a href="https://github.com/rustledger/rustledger">Repository</a> &bull;
  <a href="https://docs.rs/rustledger-core">Docs</a> &bull;
  <a href="https://crates.io/crates/rustledger">Crates.io</a> &bull;
  <a href="https://www.npmjs.com/package/@rustledger/wasm">npm</a>
</p>

---

**rustledger** is a high-performance Rust implementation of [Beancount](https://beancount.github.io/), the double-entry bookkeeping language. It provides 10-30x faster parsing and validation while maintaining full compatibility with Beancount syntax.

### Packages

| Package | Description |
|---------|-------------|
| [rustledger](https://crates.io/crates/rustledger) | CLI toolkit (`rledger check`, `rledger query`, `rledger format`, etc.) |
| [rustfava](https://github.com/rustledger/rustfava) | Web interface for rustledger (Fava-compatible) |
| [@rustledger/wasm](https://www.npmjs.com/package/@rustledger/wasm) | WebAssembly bindings for browser & Node.js |
| [@rustledger/mcp-server](https://www.npmjs.com/package/@rustledger/mcp-server) | MCP server for AI assistants |
| [Docker](https://ghcr.io/rustledger/rustledger) | Container image with CLI tools |

### Installation

```bash
# Cargo (Rust)
cargo install rustledger

# Homebrew (macOS/Linux)
brew install rustledger/rustledger/rledger

# npm (Node.js/WASM)
npm install @rustledger/wasm

# Docker
docker run ghcr.io/rustledger/rustledger rledger check ledger.beancount
```

### Try It

Visit [rustledger.github.io](https://rustledger.github.io) to try rustledger in your browser - no installation required.
