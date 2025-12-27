# zls-lsp

ZLS - the Zig Language Server for Claude Code.

## Features

- Autocomplete and go-to-definition
- Hover information and documentation
- Semantic syntax highlighting
- Error and warning diagnostics
- Code actions and refactoring

## Supported Extensions

`.zig`, `.zon`

## Prerequisites

Install Zig and ZLS:

```bash
# Using Homebrew (recommended)
brew install zig zls

# Or install separately
brew install zls
```

> Don't have Homebrew? Install it from [brew.sh](https://brew.sh)

**Important:** ZLS version must match your Zig version. Using Homebrew ensures compatibility.

## Installation

```bash
# Add the marketplace (one time)
/plugin marketplace add ajanraj/claude-lsp-plugins

# Install the plugin
/plugin install zls-lsp@claude-lsp-plugins
```

## More Information

- [Zig Language](https://ziglang.org/)
- [ZLS Documentation](https://zigtools.org/zls/)
- [ZLS GitHub](https://github.com/zigtools/zls)
