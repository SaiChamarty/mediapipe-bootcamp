# mediapipe-bootcamp

## What does it do?
This is a program that uses a previously trained model to recognize body-pivot points, when camera is opened and a human is seen.

## Important details for running
As mediapipe is not available for the latest version of python, I used python 3.11 and run the program in a virtual environment with python 3.11:
```
python3.11 -m venv venv311
```

And then we can activate the virtual environment and run our code.
```
source ./venv311/bin/activate
```
## How to run the program?
Install the dependencies:
```
pip install opencv-python mediapipe numpy
```

Once the dependencies are in, run the program using the following command:
```
python main.py
```