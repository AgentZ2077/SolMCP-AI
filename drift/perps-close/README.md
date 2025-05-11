
# SolMCP-AI

SolMCP-AI is an AI platform built on Solana and MCP, enabling seamless integration of AI models with blockchain for automated tasks and secure data interaction.

## Structure

The repository is organized as follows:

```
solmcp-ai/
  ├── mcp/
  │   ├── jupiter/
  │   ├── kamino/
  │   └── lulo/
  ├── server/
  │   ├── main.py
  ├── config/
  │   └── .env.example
  └── .gitignore
```

## Setup

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Set up environment variables by modifying `.env.example` with your Blink API key and other required credentials.

3. Run the server:
   ```
   python server/main.py
   ```

## Features

- **Solana Integration**: Build on Solana blockchain for fast and secure interactions.
- **MCP Protocol**: Provides an API to connect AI agents with blockchain data and actions.
- **AI Agents**: Automate token swaps, manage liquidity, and perform tasks using AI.

## Requirements

- Python 3.10+
- `uv` package manager
