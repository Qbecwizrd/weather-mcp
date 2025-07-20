# 🌦️🤖 Weather MCP Chatbot

A Python project using FastMCP to serve real-time US weather alerts via a chat interface!  
Async server (`weather.py`) + interactive client (`client.py`) = instant weather info with memory.  
Configurable, extendable, and fun to use! ☔🗣️

## Features

- 🚀 Fast async weather alert server (National Weather Service)
- 🗣️ Interactive chat client with conversation memory
- 🔑 Easy API key management via `.env`
- 🛠️ Simple config with `weather.json`

## Quick Start

1. **Install dependencies**  
   ```sh
   pip install -r requirements.txt
   ```

2. **Set your API key**  
   Edit `.env` with your `GROQ_API_KEY`.

3. **Run the chat client**  
   ```sh
   python server/client.py
   ```

## File Structure

- `server/weather.py` — FastMCP weather server
- `server/client.py` — Chat client
- `server/weather.json` — MCP server config
- `.env` — API keys

## License

MIT
