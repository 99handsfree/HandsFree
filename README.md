# HandsFree

**No-code desktop automation for Windows.** Turn repetitive mouse, keyboard and web tasks into scripts that run with one key.
You pick settings from menus instead of writing code, and if you'd rather not build a script yourself, an AI can write it for you.

## Features

- **Record & replay**: do the task once and it becomes a reusable script
- **No programming**: choose a command, fill in its options; coordinates, colours and images are picked straight from the screen
- **Find image / colour / text (OCR)**: act only when a button, colour or piece of text appears on screen; text recognition is built in
- **Web automation**: click buttons, fill in forms and read tables on web pages, unaffected by scrolling or window size
- **Flow control**: if / else, loops, for-each over lists, subroutines, background watchers
- **Data**: read and write files, CSV tables, clipboard, dates and times, text and list processing
- **🤖 AI writes the script**: paste the built-in *AI instruction pack* into ChatGPT, Gemini or another AI, describe what you want, and paste the script it writes back into HandsFree
- **Hotkeys, schedules, auto-start**: global start/stop hotkeys, run daily at a set time, or when a window appears
- **Step debugging, breakpoints, undo / redo** (Ctrl+Z / Ctrl+Y)
- **Share scripts**: bundle a script and its images into a folder anyone can run with a double-click
- **Chinese / English interface**, switchable with one click
- 11 built-in lessons and 8 example scripts

## Download & install

1. Download the latest `HandsFree.zip` from **[Releases](../../releases)**
2. Unzip it anywhere. Keep the whole folder together; the `.exe` does not work on its own
3. Run `HandsFree.exe`

**Requirements**: Windows 10 or 11 (64-bit). Web automation uses the Microsoft Edge (or Google Chrome) already on your PC.
Nothing else to install: no Python, no OCR engine.

### What you'll see the first time

- **"Windows protected your PC"** (SmartScreen): the program is not code-signed yet. Click **More info → Run anyway**.
- **"Do you want to allow this app to make changes to your device?"**: click **Yes**. HandsFree needs administrator rights to control programs that also run as administrator (some games, for example).
- Some antivirus products warn about any program that controls the mouse and keyboard. That is expected for automation tools.

## Free trial & activation

- **Free for 7 days** from the first launch, with every feature unlocked.
- After the trial, activate with a card number: copy the whole card number, then click **Paste Card Number → Activate** in the activation window.
- Activation works completely offline.
- **To buy a card number, contact: [99handsfree@gmail.com](mailto:99handsfree@gmail.com)**

## Responsible use

Only automate computers, accounts and websites you are allowed to, and follow the terms of service of the sites and games you use.

## Third-party components

HandsFree is closed-source software. It ships with open-source components (Qt / PySide6, pynput, Tesseract OCR, OpenCV, NumPy and others),
distributed under their own licences. The full list is in `第三方元件授權.txt` (third-party licences) and the complete licence texts are in the
`licenses` folder of the download. The LGPL components (Qt and pynput) can be replaced by the user: Qt as separate DLL files, pynput as source code in the `pynput` folder.
