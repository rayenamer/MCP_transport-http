
# MCP Transport HTTP

A lightweight HTTP transport module for MCP (Message Control Protocol).

## Features

- Simple HTTP interface for MCP messaging
- Easy setup and configuration
- Fast and efficient message handling

## Prerequisites

- Python 3.8+
- [uv](https://github.com/astral-sh/uv) package manager

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rayenamer/MCP_transport-http.git
   cd MCP_transport-http
   ```

2. Install dependencies using uv:
   ```bash
   uv sync
   ```

## Usage

### Running the Server
Start the MCP HTTP transport server:
```bash
uv run main.py
```

The server will start and listen for incoming HTTP requests.

### Configuration
Edit `pyproject.toml` to configure server settings:
```toml
[project]
name = "mcp_transport_http"
version = "0.1.0"

[tool.mcp]
host = "0.0.0.0"
port = 8080
```

## Project Structure
```
MCP_transport-http/
├── .gitignore
├── README.md
├── index.html          # Default web interface
├── main.py             # Main server application
├── pyproject.toml      # Project configuration
└── uv.lock             # Dependency lock file
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
```


