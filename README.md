# win-cred-retriever-app

© 2025 frauikram : Windows Credential Retriever App
A lightweight Python CLI tool to list and retrieve Windows Credential Manager Generic Credentials.

## Features
 - List all stored Generic Credentials.
 - Retrieve the password/token for any Generic Credential.
 - Windows-only, works fully offline.
 - MIT Licensed for personal or commercial use.

## Requirements

- Windows OS
- Python 3.8+
- No external dependencies

## Usage

```bash
# List all Generic Credentials
python listcred_cli_tool.py --list

# Get a credential's value by name
python listcred_cli_tool.py --get "<credname>"
```
Returns the stored password or secret for the provided credential name.

## Author:  
© 2025 github.com/frauikram

## License
MIT
