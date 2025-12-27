# pyrefly-lsp

Meta's Pyrefly - a fast Python type checker and language server for Claude Code.

## Features

- Blazing fast: 1.85M+ lines of code per second
- Full LSP support with code navigation, completions, and diagnostics
- Built by Meta (Facebook) in Rust
- Drop-in replacement for Pylance/Pyright

## Supported Extensions

`.py`, `.pyi`

## Prerequisites

Install Pyrefly:

```bash
# Using uv (recommended)
uv tool install pyrefly

# Using pip
pip install pyrefly
```

> Don't have uv? Install it from [astral.sh/uv](https://docs.astral.sh/uv/getting-started/installation/)

## Installation

```bash
# Add the marketplace (one time)
/plugin marketplace add ajanraj/claude-lsp-plugins

# Install the plugin
/plugin install pyrefly-lsp@claude-lsp-plugins
```

## More Information

- [Pyrefly Website](https://pyrefly.org/)
- [GitHub Repository](https://github.com/facebook/pyrefly)
- [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=meta.pyrefly)
