# Claude Plugins Marketplace

Hombee plugin marketplace for Claude Code.

## Installation

### Add the Marketplace

**From command line:**

```bash
claude plugin marketplace add hombee/claude-plugins
```

**Inside Claude Code:**

```
/plugin marketplace add hombee/claude-plugins
```

### Install a Plugin

**From command line:**

```bash
claude plugin install dart-lsp@hombee-plugins
```

**Inside Claude Code:**

```
/plugin install dart-lsp@hombee-plugins
```

## Available Plugins

### dart-lsp

Dart and Flutter Language Server Protocol support for Claude Code.

**Features:**

- Real-time diagnostics (errors, warnings, lints)
- Auto-completion with Flutter widget support
- Go-to-definition and find references
- Hover documentation
- Code refactoring
- Automatic formatting

[View plugin documentation](./plugins/dart-lsp/README.md)

## Verify Installation

After installation, open any `.dart` file. The LSP should provide:

- Real-time error diagnostics
- Auto-completion suggestions
- Hover documentation

## License

MIT
