# Fingerskier Claude Plugins

A plugin marketplace for [Claude Code](https://docs.anthropic.com/en/docs/claude-code) by Fingerskier.

## Add this marketplace

```bash
claude plugin marketplace add fingerskier/claude-plugins
```

## Available plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| [amanuensis](https://github.com/fingerskier/claude-amanuensis) | Helps authors draft and edit in their own voice — captures style, expands sketches into prose, runs targeted review passes | `claude plugin install amanuensis@fingerskier-plugins` |
| [build123d](https://github.com/fingerskier/build123d-claude-plugin) | CAD modeling with build123d — create, inspect, and export parametric 3D models using Python | `claude plugin install build123d@fingerskier-plugins` |
| [remote-access](https://github.com/fingerskier/claude-remote-access) | Develop on remote/embedded devices over SSH — read, write, edit, glob, grep, and bash on an armv7l Pi or any SSH host | `claude plugin install remote-access@fingerskier-plugins` |
| [dex](https://github.com/fingerskier/dex-claude-plugin) | Scheduler plugin for Claude Code | `claude plugin install dex@fingerskier-plugins` |
| [dude](https://github.com/fingerskier/dude-claude-plugin) | RAG and cross-project memory with auto-retrieve/persist hooks | `claude plugin install dude@fingerskier-plugins` |
| [fleet](https://github.com/fingerskier/fleet-claude-plugin) | AWS services monitor — EC2, S3, Lambda, ECS, CloudWatch, CloudFormation | `claude plugin install fleet@fingerskier-plugins` |
| [micropython](https://github.com/fingerskier/micropython-claude-plugin) | Interact with MicroPython devices within Claude | `claude plugin install micropython@fingerskier-plugins` |
| [mozart](https://github.com/fingerskier/mozart-claude-plugin) | MIDI plugin — load, analyze, edit, and compose MIDI files | `claude plugin install mozart@fingerskier-plugins` |
| [openscad](https://github.com/fingerskier/openscad-claude-plugin) | OpenSCAD parametric modeling — generate, edit, and inspect 3D models | `claude plugin install openscad@fingerskier-plugins` |
| [skidl](https://github.com/fingerskier/skidl-claude-plugin) | Design electronic schematics and PCB layouts using SKiDL | `claude plugin install skidl@fingerskier-plugins` |
| [spotify](https://github.com/fingerskier/spotify-claude-plugin) | Control Spotify playback — play, pause, skip, search, queue, volume, and more | `claude plugin install spotify@fingerskier-plugins` |
| [tail](https://github.com/fingerskier/tail-claude-plugin) | Run background processes, stream/filter logs, and wait_for patterns/idle/exit — with whole-tree cleanup | `claude plugin install tail@fingerskier-plugins` |
| [song2html](https://github.com/fingerskier/song2html) | Read, write, parse, transpose, and render song chord charts | `claude plugin install song2html@fingerskier-plugins` |
| [terse](https://github.com/fingerskier/terse-claude-plugin) | Ultra-compressed communication — cuts 50-70% of output tokens | `claude plugin install terse@fingerskier-plugins` |
| [theology](https://github.com/fingerskier/theology-claude-plugin) | Exegetical theology research — rigorous, multi-perspective Biblical exegesis | `claude plugin install theology@fingerskier-plugins` |
| [second-opinion](https://github.com/fingerskier/second-opinion-claude-plugin) | Consult other AI CLIs (Gemini, Codex, Grok, Aider, Warp, vibe-tools) for an independent second opinion | `claude plugin install second-opinion@fingerskier-plugins` |

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
