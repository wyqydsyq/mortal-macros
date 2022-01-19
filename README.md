# Mortal Macros

This is a collection of python scripts for macroing basic actions in Mortal Online 2.

They can be executed as standalone Python scripts however I recommend using [atbswp](https://github.com/RMPR/atbswp) to run the macros with the ability to toggle them on/off with hotkeys and run indefinitely until you turn it off.

## Requirements

  - Install Python 3
  - Install dependencies via pip:
    ```
      pip install pynput pyautogui wxPython
    ```
  - Clone or download & extract the contents of this repository
  - Clone or download & extract the contents of [atbswp](https://github.com/RMPR/atbswp) to the folder containing these macros 

## Usage

 - Open a command line to the folder you extracted these files to
 - Run atbswp:
    ```
    ./atbswp/atbswp/atbswp.py
    ```
 - Enable either "Infinite Playback" or "Set Repeat Count" and configure your preferred playback hotkey
 - Load the macro you want to run in the atbswp GUI
 - Start playback of the macro
 - Focus the MO2 game client window and make sure you are in locked mouse mode (press "Z" by default if you can see mouse cursor ingame)

## Macros

### Autowalk

Useful for levelling armor training, combat maneuvering, and footspeed skills.

### Autoattack

Useful for levelling strength, dexterity, melee combat, aggressive stance and endurance skills. Stand in front of a training dummy or a friend you want to stat up before starting. If using it to stat up a friend make sure you enable "thrust as default attack" in the game settings before starting.

### Autocast

Useful for levelling intelligence, psyche, resting and basically all mage skills.

You can configure the hotkeys used for chanelling a spell, self-casting it and resting by changing the variables at the top of the script. By default it will press "9" to channel spell, "E" to self-cast, "0" to rest.