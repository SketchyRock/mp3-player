# mp3-player
> A terminal MP3 player for focused lofi sessions, written in Python.

This project is a lightweight music player that plays the MP3 files in a local folder you choose, providing a distraction-free listening experience.

---

## Features:

* **Folder-based**: Point it at a folder and it plays the MP3 files inside.

* **Minimalist**: A lightweight terminal-based player.

* **Local Playback**: No internet required; plays your personal MP3 collection.

---

## Setup & Installation

### 1. Prerequisites

* Python 3.13+
* `pygame` (installed by `requirements.txt`)
* `curses`, which ships with Python on macOS and Linux. On Windows, `requirements.txt` installs `windows-curses`.

### 2. Installation
```bash
python3 -m pip install -r requirements.txt
```

### 2. Music Configuration

The first time you run it, the player asks for the path to your music folder. It only plays files from that folder.

---

## How to Run

Navigate to the project folder and run the script:
```bash
python3 main.py
```

---

## License

This project is open-source and available under the MIT License.

---

# TODO:
* add user friendly instructions for using the application
* add playlist functionality with sub dirs
* create better documentation for the new modules created
