# PHP Debug Snippets for Visual Studio Code

This Visual Studio Code extension allows PHP developers to insert quick debugging snippets into their code, specifically for printing and exiting. The `Print and Exit Debug Line` snippet combines `print_r()` and `exit` to quickly output variable values and stop script execution.

---

## 🚀 Features

- ✅ **Insert Debugging Snippet for PHP**
  - **Print and Exit Debug Line (`pepr`)**:
    - This snippet inserts an `echo "<pre>"; print_r($variable); exit;` line in your code to easily debug variables by printing them in a readable format and immediately exiting the script.

---

## 💡 Usage

| Shortcut | Action                                                                |
| -------- | --------------------------------------------------------------------- |
| `pepr`   | Inserts `echo "<pre>"; print_r($variable); exit;` for quick debugging |

To use, type `pepr` and press `Tab` to insert the line for debugging.

---

## 📂 File Support

- ✅ Works in all `.php` files
- Targets folders in PHP projects, including Laravel projects

---

## 🔧 Requirements

- Visual Studio Code `v1.99.0` or higher
- PHP project (Laravel support is optional)

---

## 📦 Installation

1. Download or build the `.vsix` file using `vsce package`.
2. In Visual Studio Code, press `Ctrl + Shift + P` → `Extensions: Install from VSIX...`.
3. Select your `.vsix` file to install.

Or, install directly from the Visual Studio Code marketplace by searching for "PHP Debug Snippets".

---

## 🔐 License

MIT License
