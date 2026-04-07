# log-analyzer

[![CI](https://img.shields.io/github/actions/workflow/status/user/log-analyzer/ci.yml?branch=main)]()
[![Python](https://img.shields.io/badge/python-3.11+-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

**log-analyzer** log file analyzer with pattern matching, aggregation, and alerting. Built with simplicity and performance in mind.

## Features

- Plugin Architecture: Extensible design with entry-point based plugins
- Type Hints: Full type annotation coverage for IDE support
- Rich CLI: Interactive CLI with colored output and progress bars
- Async Support: Native asyncio integration with sync fallback
- Minimal Dependencies: Only standard library dependencies for core features

## Installation

```bash
pip install log-analyzer
# or
pipx install log-analyzer
```

## Quick Start

```python
from log_analyzer import Client

client = Client(
    timeout=30,
    retries=3,
)

result = client.run()
print(result)
```

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
