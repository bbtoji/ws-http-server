# WebSocket Date Server and Client

This project demonstrates a simple real-time WebSocket application that streams the current date and time from a Python backend to a browser frontend using WebSockets.

## Features

- **Python Backend**:
  - HTTP server serves a simple HTML page.
  - WebSocket server broadcasts the current date and time every second.
- **HTML/JS Frontend**:
  - Connects to the WebSocket server.
  - Displays the current date and time in real time.

## Requirements

- Python 3.7+
- `aiohttp`
- `websockets`

Install dependencies:

```bash
pip install aiohttp websockets
