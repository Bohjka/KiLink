# KiLink

Collects and lists links shared in Kick.com chat in real time. Includes preview support for Twitter/X links.

## Installation

1. Download the latest `.exe` from [Releases](../../releases)
2. Run `KiLink.exe` — no installation required

## Features

- Connects to any Kick.com channel via WebSocket
- Automatically captures all links shared in chat
- Displays sender role (broadcaster, moderator, VIP)
- Built-in Twitter/X link preview
- Tracks new and opened links
- Save channel name and auto-connect on startup

## Usage

Type a channel name into the `kick.com/` field and click **Connect**.

## Development

If you want to run from source:

- Python 3.10+
- Install dependencies:

```bash
pip install -r requirements.txt
python main.py
```

## License

This project is provided for personal and educational use only.
Commercial use and modification of the source code are prohibited. See [LICENSE](LICENSE) for details.
