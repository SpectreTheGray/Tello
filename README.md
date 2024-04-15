# CODE4FUN_Tello
Tello library developed by the CODE4FUN team

:construction: This library is still in construction and is subject to change! Use at your own risk! :construction:

## Installation

```bash
git clone https://github.com/code4funSydney/Tello.git
```

```bash
cd Tello
```

```bash
python3 setup.py install
```

## To execute the Tello commands
Make sure you are outside of the Tello folder
Create a new Python file and paste the following code 

```python
from Tello import * # Imorting tello to use the Tello functions
start() # Starting the drone
takeoff() # drone taking off flying straight up
land() # drone landing
```
To execute and run the Python file 
```bash
python pythonfile.py
```

## Troubleshooting
If you are running into the issue where when you run the command for the drone to take off and it responds with an error like this
```bash
Error: Command 'takeoff' was unsuccessful for 4 tries. Latest response:	'error'
Traceback (most recent call last):
```
You must install the Tello app and fly the drone around to activate it. After that, the drone will be ready to program!


