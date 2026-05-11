# 🎮 JoyCon Music Studio

Turn Nintendo Switch Joy-Con controllers into musical instruments using HD Rumble technology.

JoyCon Music Studio lets you:

* 🎼 Play MIDI files directly on one or multiple Joy-Con controllers
* 🎹 Perform in real time from a MIDI keyboard
* 🎛️ Use virtual MIDI ports such as loopMIDI
* 🎮 Assign any MIDI track to any Joy-Con
* 📊 Display detailed note information during playback
* 🔊 Feel music as precise HD Rumble vibrations

---

## ✨ Features

### 🎼 MIDI Player

Load a `.mid` file, choose which tracks to play, assign them to connected Joy-Con controllers, and experience the music through HD Rumble.

### 🎹 Live MIDI Mode

Connect a MIDI keyboard or select any MIDI input port and play notes live on Joy-Con controllers in real time.

### 🎮 Multi Joy-Con Support

Use one or several Joy-Con controllers simultaneously. Each controller can play a different MIDI track.

### 📈 Debug Information

Display note names, MIDI note numbers, frequencies, amplitudes, and timing information during playback.

---

## 🖥️ Requirements

* Windows 7 or later (Windows 10/11 recommended)
* Nintendo Switch Joy-Con controllers
* Bluetooth support
* BetterJoy (for virtual controller support) https://github.com/Davidobot/BetterJoy/releases/tag/v7.1
* MIDI keyboard or virtual MIDI port (optional)

---

## 📦 Included Applications

### joycon-midi-player.exe

Play standard MIDI files.

### joycon-live-midi.exe

Convert live MIDI input into HD Rumble vibrations.

---

## 🚀 Example Use Cases

* Feel your favorite songs through vibration
* Perform live with a MIDI keyboard
* Turn Joy-Con controllers into tactile musical instruments
* Create experimental musical performances
* Explore HD Rumble technology

---

## 🛠️ Technologies Used

* Rust
* midly
* hidapi
* BetterJoy
* HD Rumble reverse engineering

---

## 📷 Example Output

```text
🎮 Joy-Con 1 | note 3 | D4 (MIDI 62) | 293.66 Hz | amp 0.39
```

---

## 📜 License

MIT License

---

## ❤️ Credits

Created by Akatsudo.

Inspired by the incredible HD Rumble capabilities of Nintendo Switch Joy-Con controllers.
