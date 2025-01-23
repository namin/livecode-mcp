# io.livecode.ch
MCP server for io.livecode.ch

## Dependencies

- Uses `requests` to call io.livecode.ch
- Uses the [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)


## Setup

- `uv pip install "mcp[cli]"`
- `mcp install server.py`
- `mcp dev server.py --with requests`
