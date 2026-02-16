# YouTube Downloader Engine (Release)

This repository hosts the official standalone executable for the YouTube Downloader Local Engine.

## 🛡️ Security & Fidelity Proof

We prioritize transparency. This executable is built directly from the open-source code.

-   **File Name**: `YoutubeDownloaderEngine.exe`
-   **Status**: Clean / False Positive likely due to PyInstaller.

### Why do some antiviruses flag this?
This application is built using **PyInstaller** and **Uvicorn**. Because it is a compiled Python script that launches a local server and interacts with the system tray, some heuristic scanners (like Windows Defender or Avast) may label it as a "Trojan" or "Malware" strictly because it's an unsigned .exe file doing these actions.

**This is a False Positive.** The code is open source and runs entirely locally on your machine. No data is sent to external servers other than YouTube (for downloading).

### Verify the Hash (Checksum)
To prove you have the genuine file, you can verify its SHA-256 hash.

1.  Open PowerShell in the folder where you downloaded the file.
2.  Run: `Get-FileHash YoutubeDownloaderEngine.exe`
3.  Compare the output hash with the one listed in the "Releases" tab (if applicable).

---

## 🚀 Installation & Usage

### 1. Download
Download the `YoutubeDownloaderEngine.exe` file from the latest release or this repository.

### 2. Run
Double-click the file to start the engine.
-   A window will appear showing the server logs and status.
-   **Port**: The server runs on port `8999`.

### 3. Minimize to Tray
You can close the window or click **"Minimize to Tray"**. The app will keep running in the background. form the system tray (bottom right icons), you can:
-   **Right-click -> Show Engine**: Restore the window.
-   **Right-click -> Exit**: Completely stop the application.

### 4. Start with Windows (Optional)
To have the engine run automatically when you turn on your PC:
1.  Open the Engine window.
2.  Check the box **"Start Minimized with Windows"**.
3.  The next time you restart, the engine will start quietly in the background, ready to download.

---

## 🔧 Troubleshooting

-   **"Windows protected your PC"**: Click **More Info** -> **Run Anyway**. (See "Security" above).
-   **Firewall Alert**: Allow access for the application to communicate on your local network (localhost).
