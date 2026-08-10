# Q00 Homebrew Tap

Homebrew formulae for [Ouroboros](https://github.com/Q00/ouroboros).

## Install

```sh
brew tap q00/tap
brew install ouroboros-ai
```

The formula builds from the PyPI sdist with the `[mcp]` extra included, so `ouroboros setup` and the MCP server work out of the box. Built and tested on Apple Silicon (macOS); the build compiles a Rust dependency, so the first install takes a few minutes.

## Formulae

| Formula | Description |
|---|---|
| `ouroboros-ai` | Spec-first harness for AI coding agents with answer-key withholding |
