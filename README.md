# lofi-player
> A simple Python-based MP3 player designed for focused lofi sessions.

This project is a lightweight music player that automatically loads and plays audio files from a local directory, providing a distraction-free listening experience.

---

## Features:

* **Auto-Loading**: Scans the music/ folder automatically for MP3 files.

* **Minimalist**: Runs entirely through a single Python script.

* **Local Playback**: No internet required; plays your personal lofi collection.

---

## Setup & Installation

### 1. Requirements

* Python 3.13+
* curses
* pygame

```bash
python3 -m pip install pygame
python3 -m pip install curses

```

### 2. Music Configuration

For the program to find your music, you must point to the directory where mp3's are stored once the program is launched in order for them to be played.

---

## How to Run

Navigate to the project folder and run the script:
```bash
python3 lofi.py
```

---

## License

This project is open-source and available under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software.
