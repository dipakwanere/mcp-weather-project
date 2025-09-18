How do you get started with MCP in VS Code

# Create a new directory for our project
uv init weather
cd weather

# Create virtual environment and activate it
uv venv
.venv\Scripts\activate

TIP: Check .python-verrsion file for python version > 3.10.0 and pyproject.toml file as well. 

# Install dependencies
uv add "mcp[cli]" # not needed --> httpx

# Create our server file
project_name
server (folder)
     weather.py(file)

TIP: Make sure you have python version> 3.10.0 and you 
Don't forget to install the uv before start using it with "pip install uv"

Run following cmd to run the server: 
uv run mcp dev server/weather.py


It will open the server in brower. 

now it's time to install the server
~  uv run mcp install server/weather.py


you will need claude desktop app installed on your machine. 
Go to setting > developer section and there you can add the details 

similarly
