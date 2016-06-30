# Toolbar Basic - a tool-bar plugin

## About

This is a plugin for the [Atom Tool Bar](https://atom.io/packages/tool-bar) package.

This is forked from AlexNewson's original repo, and it's better if you use that as I've changed this to reflect stuff I use.

## Buttons

* **Open file**
* **Open folder**
* **Save file**
* **List projects** (requires `project-manager` package)
* -
* **Find in buffer**
* -
* **Toggle fullscreen**
* **Toggle tree-view**
* **Split screen right**
* **Split screen down**
* **Toggle minimap**
* **Toggle exposé** (requires `expose` package)
* -
* **Auto indent**
* **Fold all**
* **Unfold all**
* **Beautify** (requires `atom-beautify` package)
* -
* **Run script** (requires `script` package)
* **Run by line** (requires `script` package)
* **Stop script** (requires `script` package)
* **Configure** (requires `script` package)
* -
* **Opens a terminal window (split bottom)**  (requires `term2` or `term3` or `terminal-plus` package)
* **Reload window** (if in Dev Mode)
* **Toggle devtools** (if in Dev Mode)
* **Git commands** (requires `git-control` package)
* -
* **Markdown Preview**
* **HTML preview** (requires `atom-html-preview` package)
* -
* **Command Pallette**
* **Settings**

**Note**: The toolbar buttons that require other packages will only appear if you have those packages installed

## Installation

First you have to install the `tool-bar` package which is required:

```bash
apm install tool-bar
```

Then you install the `tool-bar-basic` package by AlexNewson:

```bash
apm install tool-bar-basic
```

## License

[The MIT License](https://github.com/AlexNewson/tool-bar-basic/LICENSE.md)
