# vtsls-lsp

VS Code's TypeScript/JavaScript language server wrapper (vtsls) for Claude Code.

## Features

- Full VS Code-quality TypeScript/JavaScript code intelligence
- Go to definition, find references, hover documentation
- Better auto-imports than typescript-language-server
- All VS Code TypeScript refactorings and code actions

## Supported Extensions

`.ts`, `.tsx`, `.js`, `.jsx`, `.mts`, `.cts`, `.mjs`, `.cjs`

## Prerequisites

Install vtsls globally:

```bash
# Using bun
bun add -g @vtsls/language-server

# Using npm
npm install -g @vtsls/language-server

# Using pnpm
pnpm add -g @vtsls/language-server
```

## Installation

```bash
# Add the marketplace (one time)
/plugin marketplace add ajanraj/claude-lsp-plugins

# Install the plugin
/plugin install vtsls-lsp@claude-lsp-plugins
```

## More Information

- [vtsls on npm](https://www.npmjs.com/package/@vtsls/language-server)
- [GitHub Repository](https://github.com/yioneko/vtsls)
