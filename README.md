# Win Credential Retriever App

© 2025 [frauikram](https://github.com/frauikram)

A lightweight **Windows Credential Retriever App** to **list and retrieve Generic Credentials** stored in Windows Credential Manager.

---

## 🚀 Features

✅ List all stored Generic Credentials.  
✅ Retrieve the password/token for any Generic Credential.  
✅ Works fully offline on Windows.  
✅ MIT Licensed for personal or commercial use.

---

## 📥 Download

Download the latest `.exe` from the [Releases page](https://github.com/frauikram/win-cred-retriever-app/releases) to run without Python.

---

## 🖥️ Usage (Python CLI)

> Requires Windows OS, Python 3.8+, no external dependencies.

List all Generic Credentials:

```bash
python listcred_cli_tool.py --list
```

Get a credential's value by name:

```bash
python listcred_cli_tool.py --get "<credname>"
```

Returns the stored password or secret for the provided credential name.

---

## 🪪 License

Licensed under the [MIT License](LICENSE).

---

## 👤 Author

© 2025 [frauikram](https://github.com/frauikram)
