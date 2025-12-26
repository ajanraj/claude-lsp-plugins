# Claude Code LSP Plugins

A marketplace of modern, fast language server plugins for Claude Code.

## Available Plugins

| Plugin | Language | Description |
|--------|----------|-------------|
| **vtsls-lsp** | TypeScript/JavaScript | VS Code's TypeScript language server - full VS Code-quality code intelligence |
| **ty-lsp** | Python | Astral's ty - 10-100x faster than Pyright |

## Quick Start

### 1. Add this marketplace

```bash
/plugin marketplace add ajanraj/claude-lsp-plugins
```

### 2. Install the language servers

```bash
# For TypeScript/JavaScript
bun add -g @vtsls/language-server

# For Python
uv tool install ty@latest
```

### 3. Install the plugins

```bash
/plugin install vtsls-lsp@claude-lsp-plugins
/plugin install ty-lsp@claude-lsp-plugins
```

### 4. Restart Claude Code

The LSP features will now be available for TypeScript and Python files.

## Why These Plugins?

### vtsls vs typescript-language-server

vtsls wraps VS Code's built-in TypeScript extension, giving you:
- Better auto-imports
- All VS Code refactorings
- Identical experience to VS Code

### ty vs Pyright

ty is Astral's new Python type checker (creators of Ruff and uv):
- 10-100x faster than Pyright
- Written in Rust
- Modern, actively maintained

## License

MIT
