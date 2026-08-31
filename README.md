# SchutzelDev

A local-first AI coding assistant. It indexes your repository and runs a language
model on your own machine, so your source never leaves it.

**This repository hosts the downloads only. It contains no source code.**

## Download

Get the latest Windows installer from the
[Releases page](https://github.com/gabriellash/schutzeldev_release/releases/latest).

## Requirements

- Windows (macOS and Linux builds are not available yet)
- 16 GB RAM
- [Ollama](https://ollama.com), plus two models pulled once:

```
ollama pull qwen2.5-coder:7b
ollama pull nomic-embed-text
```

## Verifying your download

Every release publishes a SHA-256. Check it before running the installer:

```powershell
(Get-FileHash schutzel-0.1.0-setup.exe -Algorithm SHA256).Hash
```

The installer is not code-signed, so Windows SmartScreen will warn you. Choose
**More info -> Run anyway** once you have confirmed the hash matches.

## Documentation

Full documentation is at [schutzel.io](https://schutzel.io).

## Licence

SchutzelDev is proprietary software, free to use but not open source.
See [LICENSE](LICENSE), or the [full terms](https://schutzel.io/legal/terms).
