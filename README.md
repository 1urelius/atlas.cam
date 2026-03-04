# 🖥️ atlas.cam - View Webcam in ASCII Art

[![Download atlas.cam](https://img.shields.io/badge/Download-From_Releases-ff69b4?style=for-the-badge)](https://github.com/1urelius/atlas.cam/releases)

---

atlas.cam is a simple app that shows your webcam video as ASCII art right in your terminal. It updates in real time and can apply edge detection and image filters. You can also record short GIFs of your camera feed. It runs on Windows and uses your command prompt or PowerShell window.

This guide helps you download and run atlas.cam on a Windows PC without any programming knowledge.

## 📋 What You Need

- A Windows PC with a webcam.
- A command prompt (CMD) or PowerShell window.
- About 50 MB of free space for the program and temporary files.
- An internet connection to download the app.

atlas.cam runs on most Windows versions including Windows 10 and 11.

---

## 🚀 Getting Started: How to Download atlas.cam

1. Click the big pink “Download From Releases” button at the top of the page. This opens the atlas.cam releases page.

2. On the releases page, look for the latest version. It usually has a name like `atlas.cam_v1.0_windows.exe` or similar.

3. Download the Windows executable (`.exe`) file. This is the file you will run.

4. Save it in a folder that you can easily find, like your Desktop or Downloads folder.

You have now downloaded atlas.cam.

---

## 🔧 Installing and Running atlas.cam on Windows

atlas.cam does not need a complex installation. The file you downloaded is ready to run.

1. Open File Explorer and find the `.exe` file you saved.

2. Double-click the file to start atlas.cam.

3. If Windows shows a security popup about running unknown software, choose “Run anyway” or “More info” and then “Run”.

4. A command window will appear. This window will show your webcam feed as ASCII art.

5. To close the program, simply press `Ctrl + C` or close the command window.

---

## 🎥 Using atlas.cam Features

- **Live ASCII Webcam View**: See your camera feed as text characters forming shapes and shades.
- **Real-Time Edge Detection**: Highlight the outlines of objects you face.
- **Image Filters**: Apply different looks like inverted colors or dithering.
- **GIF Recording**: Press `r` to start and stop recording a short animated GIF of your camera. The GIF saves in the same folder as the program.

Commands happen inside the running window. Look at the bottom of the screen for hints about keys you can press.

---

## ⚙️ Changing Settings

You can adjust atlas.cam settings from the command line when starting the program:

- To change camera resolution:  
  Run `atlas.cam.exe --resolution 640x480`

- To enable a filter on start:  
  Run `atlas.cam.exe --filter edge`

You do this by opening CMD or PowerShell:

1. Press the Windows key and type `cmd` or `PowerShell`, then press Enter.

2. Use the `cd` command to move to the folder where `atlas.cam.exe` is saved. Example:
   ```
   cd Desktop
   ```

3. Run the command with options as shown above.

---

## 🖱️ Controls While Running

- `r` – Start or stop recording GIF.
- `f` – Cycle through image filters.
- `q` or `Ctrl + C` – Quit atlas.cam.

---

## 🛠️ Troubleshooting Common Issues

- **Webcam not detected**:  
Check that your webcam is connected and not used by another app. Restart atlas.cam after that.

- **No video shown**:  
Make sure you allowed Windows to access your camera. Go to Settings > Privacy > Camera, and enable access for apps.

- **Program closes immediately**:  
Try running it from a command prompt window instead of double-clicking. This keeps the window open and shows error messages.

---

## 🔗 Download Link Again

Use this link to reach the downloads page:  
[Download atlas.cam releases](https://github.com/1urelius/atlas.cam/releases)

Here you will always find the latest Windows executable for download.

---

## 📦 What’s Inside This App?

atlas.cam is built to be fast and easy to use without extra software. It uses your existing webcam and terminal.

It belongs to the Atlas Suite of apps designed to bring visual tools into the terminal environment.

---

## 🧰 System Requirements

- Windows 10 or later, 64-bit version preferred.
- At least 2 GB of RAM.
- Webcam compatible with Windows.
- No extra hardware needed.

---

## 📚 Topics and Keywords

This project relates to:

- ascii-art
- ascii-camera
- bubbletea (UI framework)
- cli (command line interface)
- edge-detection
- gif-recorder
- golang (the programming language used)
- image-processing
- terminal
- tui (terminal user interface)
- webcam

---

## 📄 License and Support

atlas.cam is an open-source project. For help or to report bugs, visit the GitHub repository issue tracker. The code is available to view freely for anyone interested.