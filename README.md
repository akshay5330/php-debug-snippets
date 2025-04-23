# PHP Debug Snippets for Visual Studio Code

This Visual Studio Code extension allows PHP developers to insert quick debugging snippets into their code. It includes snippets for printing variables using `print_r()`, `var_dump()`, or `json_encode()` along with `exit` to stop script execution for debugging.

---

## 🎥 Demo

<video width="100%" controls>
  <source src="https://github.com/akshay5330/php-debug-snippets/raw/main/assets/videos/vd.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## 🚀 Features

- ✅ **Insert Debugging Snippets for PHP**
  - **Print and Exit Debug Line (`pepr`, alias: `prdie`)**:
    - Inserts `echo "<pre>"; print_r($variable); exit;`
  - **Var Dump and Exit (`vdie`)**:
    - Inserts `echo "<pre>"; var_dump($variable); exit;`
  - **JSON Encode and Exit (`jsonex`)**:
    - Inserts `echo json_encode($variable, JSON_PRETTY_PRINT); exit;`
  - **Comment Debug Line (`clrdbg`)**:
    - Inserts a commented debug line for quick cleanup or temporary disablement

---

## 💡 Usage

| Shortcut | Action                                                          |
| -------- | --------------------------------------------------------------- |
| `pepr`   | Inserts `echo "<pre>"; print_r($variable); exit;`               |
| `prdie`  | Alias for `pepr`                                                |
| `vdie`   | Inserts `echo "<pre>"; var_dump($variable); exit;`              |
| `jsonex` | Inserts `echo json_encode($variable, JSON_PRETTY_PRINT); exit;` |
| `clrdbg` | Inserts a commented debug line                                  |

To use a snippet, type its shortcut (e.g., `pepr`) and press `Tab`.

Using clrdbg in Real Projects

The clrdbg snippet simplifies PHP debugging by commenting out debug lines (e.g., `// DEBUG: echo "<pre>"; print_r($variable); exit;`) for temporary disablement. In Laravel projects, it ensures clean code by marking debug statements for easy removal before deployment.

---

## 📂 File Support

- ✅ Works in all `.php` files
- Ideal for PHP projects, including Laravel applications

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

[MIT License](https://github.com/akshay5330/php-debug-snippets/blob/main/LICENSE.txt) © 2025 [Sahil Kothiya](https://github.com/akshay5330)
