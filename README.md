# 🌌 NOX BROWSER
**The High-Performance Gaming Browser built on .NET 6 & WebView2**
![Nox Browser Banner](banner.png)
## 🚀 Features
Nox Browser is designed for speed, aesthetics, and gamers who need a lightweight alternative to Chrome.

* **⚡ Neon GX UI:** A stunning dark mode interface with cyan neon accents.
* **📉 Data Saver Mode:** Physical image blocking to save bandwidth and load pages instantly.
* **📶 Live Ping Monitor:** Real-time latency tracking displayed right in the toolbar.
* **🏠 Custom Home Page:** Built-in "Speed Dial" with quick links to YouTube, Reddit, Twitch, and Discord.
* **📂 Multi-Tab System:** Fully functional tab management with "Click-to-Close" convenience.
* **🔒 Privacy Focused:** No telemetry, no tracking, just browsing.

## 🛠️ Installation

### Option 1: Download (Recommended)
You don't need to install anything. Just download and run.
1.  Go to the [**Releases Page**](https://github.com/SHARVANKUMARSINGH/NoxBrowser/releases)
2.  Download `NoxBrowser.exe`.
3.  Double-click to launch.

### Option 2: Build from Source
If you are a developer, you can build it yourself:
1.  Install **.NET 6.0 SDK**.
2.  Clone this repository.
3.  Run the build command:
    ```bash
    dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
    ```

## 💻 Tech Stack
* **Language:** C# (.NET 6.0)
* **Engine:** Microsoft WebView2 (Chromium-based)
* **GUI:** Windows Forms (Custom Painted)

---
*Made with ❤️ by kyugivj*
