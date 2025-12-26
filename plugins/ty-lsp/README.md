# ty-lsp

Astral's extremely fast Python type checker and language server (ty) for Claude Code.

## Features

- 10-100x faster than mypy and Pyright
- Full LSP support with code navigation, completions, and diagnostics
- Built by Astral (creators of Ruff and uv)
- Written in Rust for maximum performance

## Supported Extensions

`.py`, `.pyi`

## Prerequisites

Install ty:

```bash
# Using uv (recommended)
uv tool install ty@latest

# Using standalone installer
curl -LsSf https://astral.sh/ty/install.sh | sh

# Using pip
pip install ty

# Using pipx
pipx install ty
```

## Installation

```bash
# Add the marketplace (one time)
/plugin marketplace add ajanraj/claude-lsp-plugins

# Install the plugin
/plugin install ty-lsp@claude-lsp-plugins
```

## More Information

- [ty Documentation](https://docs.astral.sh/ty/)
- [GitHub Repository](https://github.com/astral-sh/ty)
