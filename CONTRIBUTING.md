# Contributing to rustledger

Thank you for your interest in contributing to rustledger!

## Getting Started

1. Fork the repository
2. Clone your fork
3. Create a feature branch: `git checkout -b feature/your-feature`
4. Make your changes
5. Run tests: `cargo test --all-features`
6. Run lints: `cargo clippy --all-features -- -D warnings`
7. Commit with [conventional commits](https://www.conventionalcommits.org/): `git commit -m "feat: add feature"`
8. Push and open a Pull Request

## Development Setup

```bash
# Clone
git clone https://github.com/rustledger/rustledger
cd rustledger

# Build
cargo build --all-features

# Test
cargo test --all-features

# Lint
cargo clippy --all-features -- -D warnings
cargo fmt --all -- --check
```

## Code Standards

- Use `Result<T, E>` for fallible operations
- Prefer `?` operator over `.unwrap()` in production code
- Add tests for new functionality
- Document public APIs with doc comments
- Follow existing code style

## Commit Messages

We use [conventional commits](https://www.conventionalcommits.org/):

- `feat:` - New features
- `fix:` - Bug fixes
- `docs:` - Documentation changes
- `refactor:` - Code refactoring
- `test:` - Test additions/changes
- `chore:` - Maintenance tasks

## Questions?

Open a [discussion](https://github.com/rustledger/rustledger/discussions) or reach out to the maintainers.
