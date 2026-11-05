# JarvisOS HUD

Tauri 2 display HUD for the JarvisOS core (`jarvis-os`). Typed commands and chat go to the core over a local WebSocket (`ws://localhost:8765`); replies and status come back. There is no voice: no microphone, speech-to-text, text-to-speech or wake word.

## Run

```
npm install
npm run tauri dev
```

Start the core first (`main.py` in `jarvis-os`) so the HUD can connect.

## IDE Setup

[VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
