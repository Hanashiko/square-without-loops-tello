# Tello Square Flight

A simple Python script that commands a DJI Tello drone to fly in a square pattern without using loops.

## How it works

The drone takes off, flies forward 100 cm, rotates 90° clockwise, and repeats this four times to complete a square before landing.

## Requirements

- Python 3
- [djitellopy](https://github.com/dafly/djitellopy)
- DJI Tello drone connected via Wi-Fi

## Usage

```bash
pip install djitellopy
python main.py
```
