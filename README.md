# z-temir

z-temir 的安裝檔。最新版：**0.1.17c**

| 平台 | 下載 |
|---|---|
| macOS（Apple 晶片 M1/M2/M3…） | [z-temir-0.1.17c-macos-arm64.zip](releases/0.1.17c/z-temir-0.1.17c-macos-arm64.zip) |
| macOS（Intel） | [z-temir-0.1.17c-macos-amd64.zip](releases/0.1.17c/z-temir-0.1.17c-macos-amd64.zip) |
| Windows（x64） | [z-temir-0.1.17c-windows-amd64.zip](releases/0.1.17c/z-temir-0.1.17c-windows-amd64.zip) |
| Windows（ARM） | [z-temir-0.1.17c-windows-arm64.zip](releases/0.1.17c/z-temir-0.1.17c-windows-arm64.zip) |
| Linux（x64） | [z-temir-0.1.17c-linux-amd64.tar.gz](releases/0.1.17c/z-temir-0.1.17c-linux-amd64.tar.gz) |

檔案的 SHA-256 在各版本資料夾的 `SHA256SUMS.txt`。

## 安裝

- **macOS**：解壓縮後把 `z-temir.app` 拖到「應用程式」。第一次打開若出現「無法驗證開發者」，到「系統設定 → 隱私權與安全性」按「強制打開」。
- **Windows**：解壓縮後執行 `z-temir.exe`。需要 Windows 10 1809 以上和 WebView2 Runtime（Windows 11 內建）。
- **Linux**：解壓縮後執行 `./install.sh`（裝到 `~/.local/bin`）。需要 GTK 3 和 WebKitGTK 4.1，例如 `sudo apt install libgtk-3-0 libwebkit2gtk-4.1-0`。

## 所有版本

- [0.1.17c](releases/0.1.17c)
