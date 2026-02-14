# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 0.8.x   | :white_check_mark: |
| < 0.8   | :x:                |

## Reporting a Vulnerability

If you discover a security vulnerability in rustledger, please report it by emailing **security@rustledger.dev** (or opening a [private security advisory](https://github.com/rustledger/rustledger/security/advisories/new)).

Please include:

- A description of the vulnerability
- Steps to reproduce
- Potential impact
- Any suggested fixes (optional)

We will respond within 48 hours and work with you to understand and address the issue. Security fixes are prioritized and typically released within 7 days of confirmation.

## Security Considerations

rustledger handles financial data. Key security areas:

- **Parser**: Handles untrusted input; must not panic or allow DoS
- **File loader**: Prevents path traversal in `include` directives
- **WASM sandbox**: Isolated execution with no file system access by default
- **Dependencies**: Regularly audited with `cargo deny`

## Responsible Disclosure

We follow responsible disclosure practices. Please allow us reasonable time to address vulnerabilities before public disclosure.
