# 💻 Windows SHA256 Context Menu 📁

Add SHA256 hash calculation functionality to your Windows Explorer context menu.

## 📋 Features

* 📝 Calculate SHA256 hash of any file directly from context menu
* 📋 Automatic copy to clipboard
* ⚡️ Fast execution with minimal overhead
* 🐟 Clean PowerShell implementation
* 📦 No external dependencies

## 🔧 Installation

### Step-by-Step Instructions

1. 📥 Download the `add_sha256_context.reg` file
2. 💻 Double-click to merge it into your registry
3. 📝 Confirm the registry modification prompt

## 🎯 Usage

### How to Use

1. 🖈 Right-click any file in Windows Explorer
2. 📝 Select "Get SHA256" from the context menu
<img width="200" alt="image" src="https://github.com/user-attachments/assets/d2ddb279-cc2a-40b9-9d71-6ab60e5cdd93">

4. 🔗 The hash will be displayed and copied to clipboard

## 🗑️ Uninstallation

### How to Remove

1. 📥 Download the `remove_sha256_context.reg` file
2. 💻 Double-click to run it

## 🔒 Security

* Uses only built-in Windows PowerShell commands
* No external dependencies or network access
* Read-only operation - never modifies your files
* Runs with user permissions only

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
