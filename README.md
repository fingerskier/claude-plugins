# Fingerskier Claude Plugins

A plugin marketplace for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) by Fingerskier.

## Add this marketplace

```bash
claude plugin marketplace add fingerskier/claude-plugins
```

## Available plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| [dex](https://github.com/fingerskier/dex-claude-plugin) | Scheduler plugin for Claude Code | `claude plugin install dex-claude-plugin@fingerskier-plugins` |
| [dude](https://github.com/fingerskier/dude-claude-plugin) | RAG and cross-project memory with auto-retrieve/persist hooks | `claude plugin install dude@fingerskier-plugins` |
| [micropython](https://github.com/fingerskier/micropython-claude-plugin) | Interact with MicroPython devices within Claude | `claude plugin install micropython-claude-plugin@fingerskier-plugins` |
| [tail](https://github.com/fingerskier/tail-claude-plugin) | Run background processes and stream logs back to Claude | `claude plugin install tail@fingerskier-plugins` |

## Install a plugin

After adding the marketplace:

```bash
claude plugin install dude@fingerskier-plugins
```

## Update

```bash
claude plugin marketplace update fingerskier-plugins
```

## License

[MIT](./LICENSE)
