# MCP Weather Project

This project is a weather application built using the MCP framework and FastMCP server. It fetches weather alerts and forecasts from the National Weather Service (NWS) API and provides them via asynchronous tools.

## Features

- Fetch active weather alerts for US states
- Get detailed weather forecasts for specific latitude and longitude
- Easy to run and extend using MCP framework

## Prerequisites

- Python 3.10 or higher
- Virtual environment (recommended)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mcp-weather-project.git
   cd mcp-weather-project
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On Unix or MacOS
   source venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the MCP development server:
   ```bash
   uv run mcp dev server/weather.py
   ```
   This will start the server and open it in your browser.

2. To install the server:
   ```bash
   uv run mcp install server/weather.py
   ```

3. Make sure you have the Claude desktop app installed and configured for full functionality.

## Project Structure

- `server/weather.py`: Main server code with MCP tools for weather alerts and forecasts.
- `main.py`: Entry point placeholder.
- `README.md`: Project documentation.
- `.gitignore`: Git ignore rules including virtual environment exclusion.
- `pyproject.toml`: Python project configuration.

## Notes

- Ensure Python version is 3.10 or higher (see `.python-version` and `pyproject.toml`).
- Virtual environment folder `venv/` is excluded from Git.
- The project uses asynchronous HTTP requests with `httpx`.

## Contributing

Feel free to open issues or pull requests for improvements or bug fixes.

## License

Specify your license here.

---

For any questions or help, please contact the project maintainer.
