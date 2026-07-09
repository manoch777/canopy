
B
456
canopy start
```

## How to Run It with 🐳 Docker

➪ To run a Canopy `Localnet` in a *containerized* environment, use the following commands:
```bash
make docker/build
make docker/up-fast
make docker/logs

or simply

make docker/up && make docker/logs
```

## Running Tests

➪ To run Canopy unit tests, use the Go testing tools:

```bash
make test
```

## How to Contribute

➪ Canopy is an open-source project, and we welcome contributions from the community. Here's how to get involved:

1. **Fork** the repository and clone it locally.
2. **Code** your improvements or fixes.
3. **Submit a Pull Request** (PR) for review.

➣ Please follow these [guidelines](CONTRIBUTING.md) to maintain high-quality contributions:

### High Impact or Architectural Changes

➪ Before making large changes, discuss them with the Canopy team on [Discord](https://discord.gg/pNcSJj7Wdh) to ensure alignment.

### Coding Style

- Code must adhere to official Go formatting (use [`gofmt`](https://golang.org/cmd/gofmt)).
- (Optional) Use [EditorConfig](https://editorconfig.org) for consistent formatting.
- All code should follow Go documentation/commentary guidelines.
- PRs should be opened against the `development` branch.

[![Pre-Release](https://img.shields.io/github/release-pre/canopy-network/canopy.svg)](https://github.com/canopy-network/canopy/releases)
[![Go Report Card](https://goreportcard.com/badge/github.com/canopy-network/canopy)](https://goreportcard.com/report/github.com/canopy-network/canopy)
[![Contributors](https://img.shields.io/github/contributors/canopy-network/canopy.svg)](https://github.com/canopy-network/canopy/pulse)
[![Last Commit](https://img.shields.io/github/last-commit/canopy-network/canopy.svg)](https://github.com/canopy-network/canopy/pulse)

## Contact

[![Twitter](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://x.com/CNPYNetwork)
[![Discord](https://img.shields.io/badge/discord-online-blue.svg)](https://discord.gg/pNcSJj7Wdh)
