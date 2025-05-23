# MineBack

**MineBack** is a lightweight external Java program that automatically backs up your Minecraft world, mods, configs, and scripts, then pushes the archive to a GitHub repository.  
This saves a lot of disk space when you have many backups of the same world.

This tool is especially useful for players who play heavily modded Minecraft — especially with custom recipes and configs — and want to keep their setup safe and version-controlled.

## Features

- 📦 Automatic backup of:
  - `saves/`
  - `mods/`
  - `config/`
  - `scripts/`
- 🕓 Runs on a timer or manually
- 🔐 Pushes backup archives to your GitHub repository using a personal access token
- 📁 Archives are named by timestamp: `backup-YYYY-MM-DD_HH-mm-ss.zip`
- 💬 Clean console output or basic GUI (planned)

## Requirements

- Java 8 or higher
- Git installed and available in system PATH
- GitHub account and personal access token

## License

MIT License – feel free to use, modify, and share.
