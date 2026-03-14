# 🦥 Boomodoro

A minimal TUI pomodoro timer built with Rust, made for focus.

## Features

- 25/5/15 minute work and break cycles
- Desktop notifications on stage change
- Sound effects on key actions
- Session progress dots
- Single clean interface

## Keybindings

| Key | Action |
|-----|--------|
| `p` | Start / Stop |
| `j` | Skip to next stage |
| `r` | Reset |
| `q` | Quit |

## Installation

Download the latest binary from [Releases](../../releases) and run:

```bash
chmod +x boomodoro
./boomodoro
```

Or add it to your PATH:

```bash
sudo cp boomodoro /usr/local/bin/
```

## Building from source

```bash
git clone git@github.com:yourusername/boomodoro.git
cd boomodoro
cargo build --release
./target/release/boomodoro
```

## Windows Support

Currently Linux only. Windows support is a work in progress — contributions welcome. The main blocker is audio latency and terminal encoding. If you want to help, open an issue.

## Built with

- [ratatui](https://github.com/ratatui-org/ratatui) — TUI framework
- [crossterm](https://github.com/crossterm-rs/crossterm) — terminal control
- [rodio](https://github.com/RustAudio/rodio) — audio
- [notify-rust](https://github.com/hoodie/notify-rust) — desktop notifications
