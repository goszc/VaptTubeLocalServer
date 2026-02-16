# YouTube Downloader Engine (Release)

[Português](#português) | [English](#english)

---

## Português

Standalone executável para o motor local do YouTube Downloader.

### 🛡️ Prova de Fidelidade e Segurança

Priorizamos a transparência. Este executável é gerado diretamente do código-fonte aberto.

-   **Arquivos**: `YoutubeDownloaderEngine.exe` e `ffmpeg.exe`.
-   **Status**: Limpo. Provável "Falso Positivo" devido ao PyInstaller.

#### Por que alguns antivírus detectam como ameaça?
Este app usa **PyInstaller** e **Uvicorn**. Como é um script Python compilado que abre um servidor local e ícone de bandeja, scanners heurísticos (como Windows Defender ou Avast) podem rotulá-lo como "Trojan" ou "Malware" apenas por ser um `.exe` não assinado digitalmente. **Isa é um Falso Positivo.** O código é aberto e roda 100% local.

---

### 🚀 Tutorial de Instalação e Uso

#### 1. Download
Baixe os dois arquivos deste repositório:
- `YoutubeDownloaderEngine.exe` (O motor principal)
- `ffmpeg.exe` (Necessário para processamento de áudio/vídeo)

#### 2. Execução
Clique duas vezes em `YoutubeDownloaderEngine.exe`.
- Uma janela abrirá mostrando os logs do servidor.
- **Porta**: O servidor roda em `8999`.

#### 3. Minimizar para a Bandeja
Você pode fechar a janela ou clicar em **"Minimize to Tray"**. O app continuará rodando em segundo plano. No ícone da bandeja (perto do relógio):
- **Botão direito -> Show Engine**: Abre a janela novamente.
- **Botão direito -> Exit**: Fecha o servidor completamente.

#### 4. Iniciar com o Windows
Para o motor iniciar sozinho ao ligar o PC:
1. Abra a janela do Engine.
2. Marque a caixa **"Start Minimized with Windows"**.

---

## English

Standalone executable for the YouTube Downloader local engine.

### 🛡️ Security & Fidelity Proof

We prioritize transparency. This executable is built directly from the open-source code.

-   **Files**: `YoutubeDownloaderEngine.exe` and `ffmpeg.exe`.
-   **Status**: Clean / False Positive likely due to PyInstaller.

#### Why do some antiviruses flag this?
This application is built using **PyInstaller** and **Uvicorn**. Because it is a compiled Python script that starts a local server and tray icon, heuristic scanners (like Windows Defender) may label it as "Trojan" strictly because it's an unsigned .exe. **This is a False Positive.** The code is open source and runs entirely locally.

---

### 🚀 Installation & Usage Tutorial

#### 1. Download
Download both files from this repository:
- `YoutubeDownloaderEngine.exe` (Main engine)
- `ffmpeg.exe` (Required for audio/video processing)

#### 2. Run
Double-click `YoutubeDownloaderEngine.exe`.
- A window will appear showing server logs.
- **Port**: The server runs on `8999`.

#### 3. Minimize to Tray
You can close the window or click **"Minimize to Tray"**. The app keeps running in the background. In the system tray (bottom right icons):
-   **Right-click -> Show Engine**: Restore the window.
-   **Right-click -> Exit**: Stop the application.

#### 4. Start with Windows
To have the engine run automatically when you turn on your PC:
1.  Open the Engine window.
2.  Check the box **"Start Minimized with Windows"**.

---

## 🔧 Troubleshooting / Resolução de Problemas

- **"Windows protected your PC" / "O Windows protegeu o seu PC"**:
  - Clique em **More Info** (Mais Informações) -> **Run Anyway** (Executar assim mesmo).
- **Firewall**: 
  - Permita o acesso para que o app se comunique localmente (localhost).
