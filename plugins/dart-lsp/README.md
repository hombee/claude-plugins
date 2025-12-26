# Dart LSP Plugin for Claude Code

Language Server Protocol support for Dart and Flutter development in Claude Code.

## Features

- **Diagnostics** - Real-time errors, warnings, and lints from Dart analyzer
- **Auto-completion** - Code completion for Dart and Flutter widgets
- **Go-to-definition** - Jump to symbol definitions
- **Find references** - Locate all usages of a symbol
- **Hover information** - Type info and documentation on hover
- **Refactoring** - Rename symbols, extract methods, and more
- **Formatting** - Automatic code formatting with `dart format`

## Prerequisites

- [Dart SDK](https://dart.dev/get-dart) installed and available in PATH
- For Flutter projects: [Flutter SDK](https://flutter.dev/docs/get-started/install)

## How It Works

This plugin configures Claude Code to use the Dart language server (`dart language-server`) which provides full LSP support for both Dart and Flutter projects.

The language server automatically:

- Reads `analysis_options.yaml` for custom lint rules
- Resolves package imports from `pubspec.yaml`
- Provides Flutter-specific features like widget outlines

## Configuration

The plugin uses sensible defaults. The LSP server is configured with:

```json
{
  "suggestFromUnimportedLibraries": true,
  "closingLabels": true,
  "flutterOutline": true
}
```

## Keywords

Dart, Flutter, LSP, Language Server Protocol, Claude Code, code completion, static analysis, IDE support
