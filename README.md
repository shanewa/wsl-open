# wsl-open
Open a folder from WSL with Windows Explorer

# Quick Start

1. Copy [open](./open) tool to your `~/bin` from your WSL2.

2. Modify `INSTALL_PATH` in `open` file based on your WSL distribution version. Here, I'm using `Ubuntu-22.04`.

```
INSTALL_PATH='\\wsl$\Ubuntu-22.04'
```

3. Set the right permission of the `open` tool.

```
chmod +x open
```

4. Switch to a folder in WSL2, then open this folder with Windows Explorer.

```
cd xxx
open
```
