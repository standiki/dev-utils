# Dev-Utils 🚀

A collection of lightweight shell scripts to automate daily developer workflows and simplify terminal tasks.

## 🌟 Why this project?
As a developer, I noticed myself repeating the same Git and environment commands every day. This repo is a central place for scripts that save time and reduce "terminal fatigue." It is built with beginners in mind, providing clear hints for every command.

## 🛠️ Included Tools
Find specific scripts and hints in the subdirectories:
- [Git Utilities](./scripts/git)
- [Common Utilities](./scripts/common)

## 🚀 Quick Start
1. Clone the repo:
   `git clone git@github.com:standiki/dev-utils.git`
2. Navigate to the script directory and chose the script category, e.g `git`:
`cd scripts/git`
3. Run a script manually:
`./1-gpull man`

## 🌍 Global Access (Recommended)
To run these scripts from any folder on your machine without typing the path:
1. Open your shell profile: `vi ~/.zshrc` (or `~/.bashrc`)
2. Add the script folders to your PATH: (Make sure to update the paths to match yours)
   `export PATH="$PATH:$HOME/dev-utils/scripts/git:$HOME/dev-utils/scripts/common"`
3. Refresh your shell: `source ~/.zshrc`
4. Now, just type: `1-gpull`

Voilà! 🎉 Happy hacking 👨‍💻

## ⚖️ License
This project is licensed under the [MIT License](LICENSE). Feel free to fork, clone, and improve!
