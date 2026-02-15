# Fingerskier Claude Plugins

A plugin marketplace for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) by Fingerskier.

## Add this marketplace

```bash
claude plugin marketplace add fingerskier/claude-plugins
```

## Available plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| [dude](https://github.com/fingerskier/dude-claude-plugin) | RAG and cross-project memory with auto-retrieve/persist hooks | `claude plugin install dude@fingerskier-plugins` |
| [fleet](https://github.com/fingerskier/fleet-claude-plugin) | AWS services monitor — EC2, S3, Lambda, ECS, CloudWatch, CloudFormation | `claude plugin install fleet@fingerskier-plugins` |

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
