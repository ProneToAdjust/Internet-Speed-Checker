# Internet-Speed-Checker
A program that checks and displays your internet speed in a windows toast notification

## Usage
- Launch the executable and there will a toast notification indicating the start of the speed test, shortly afterwards, your internet speed would be displayed in another toast notification.
- I used this to check my internet speed on my computer start up by placing the executable in the start up folder: **C:\Users\<username>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup**

## Developing
- Python version: [3.8.1](https://www.python.org/downloads/release/python-381/)
#### Installing dependencies
```
pip install -r requirements.txt
```
#### Testing and debugging
```
python internet_speed_checker.py
```
#### Executable packaging
```
pyinstaller internet_speed_checker.spec
```
