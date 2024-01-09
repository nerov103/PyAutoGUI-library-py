
# Project Title

PyAutoGUI lets your Python scripts control the mouse and keyboard to automate interactions with other applications. The API is designed to be simple. PyAutoGUI works on Windows, macOS, and Linux, and runs on Python 2 and 3,


## Documentation

[Documentation](https://pyautogui.readthedocs.io/en/latest/)

Welcome to PyAutoGUI’s documentation!
## Installation

Install my-project with npm

```bash
  pip install pyautogui
```
    
## FAQ

FAQ: Frequently Asked Questions
Send questions to al@inventwithpython.com

Q: Can PyAutoGUI work on Android, iOS, or tablet/smartphone apps.

A: Unfortunately no. PyAutoGUI only runs on Windows, macOS, and Linux.

Q: Does PyAutoGUI work on multi-monitor setups.

A: No, right now PyAutoGUI only handles the primary monitor.

Q: Does PyAutoGUI do OCR?

A: No, but this is a feature that’s on the roadmap.

Q: Can PyAutoGUI do keylogging, or detect if a key is currently pressed down?

A: No, PyAutoGUI cannot do this currently


## Usage/Examples

>>> import pyautogui

>>> screenWidth, screenHeight = pyautogui.size() # Get the size of the primary monitor.
>>> screenWidth, screenHeight
(2560, 1440)

>>> currentMouseX, currentMouseY = pyautogui.position() # Get the XY position of the mouse.
>>> currentMouseX, currentMouseY
(1314, 345)

>>> pyautogui.moveTo(100, 150) # Move the mouse to XY coordinates.

>>> pyautogui.click()          # Click the mouse.
>>> pyautogui.click(100, 200)  # Move the mouse to XY coordinates and click it.
>>> pyautogui.click('button.png') # Find where button.png appears on the screen and click it.

>>> pyautogui.move(400, 0)      # Move the mouse 400 pixels to the right of its current position.
>>> pyautogui.doubleClick()     # Double click the mouse.
>>> pyautogui.moveTo(500, 500, duration=2, tween=pyautogui.easeInOutQuad)  # Use tweening/easing function to move mouse over 2 seconds.

>>> pyautogui.write('Hello world!', interval=0.25)  # type with quarter-second pause in between each key
>>> pyautogui.press('esc')     # Press the Esc key. All key names are in pyautogui.KEY_NAMES

>>> with pyautogui.hold('shift'):  # Press the Shift key down and hold it.
        pyautogui.press(['left', 'left', 'left', 'left'])  # Press the left arrow key 4 times.
>>> # Shift key is released automatically.

>>> pyautogui.hotkey('ctrl', 'c') # Press the Ctrl-C hotkey combination.

>>> pyautogui.alert('This is the message to display.') # Make an alert box appear and pause the p

![Logo](https://i.ytimg.com/vi/RMdN3Vq7sTE/maxresdefault.jpg)


## About me
Hi, Ima Mr Nerov Ahmead

i'ma From Bangladesh

I read in class 10

i a python developer 

Thank You!