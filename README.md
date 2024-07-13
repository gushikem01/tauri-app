# Tauri + React + Typescript

This template should help get you started developing with Tauri, React and Typescript in Vite.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## How to install tauri on wsl2

1) at first install packages

```
sudo apt-get install pkg-config \
  libdbus-1-dev \
  libgtk-3-dev \
  libsoup2.4-dev \
  libjavascriptcoregtk-4.0 \
  libwebkit2gtk-4.0
```

2) export display

```
export DISPLAY=192.168.0.9:0
```

192.168.0.9 is your ipaddress

3) install VcXsrv Windows X Server 

4) yarn tauri dev
