# Drag and drop

Drag and drop program

## Features

- Real-time hand detection.

- Cross-Platform Support: Runs on Windows, macOS, and Linux.

## Installation

### Prerequisites

- Python 3.8
- OpenCV

clone the repo or [download](https://github.com/aust21/drag-and-drop/archive/refs/heads/main.zip)

```
git clone https://github.com/aust21/drag-and-drop
cd drag-and-drop
```

### Set up a virtual environment

For Windows

```
python -m venv venv
venv\Scripts\activate
```

For Linux / mac

```
python3 -m venv venv
source venv/bin/activate
```

install the required modules

```
pip3.8 install -r requirements.txt
```

## Usage
Run the program

```
jupyter nbconvert --to notebook --execute main.ipynb
```
- To drag a box: put your index and middle fingers closely together
- To drop(let go) of the box: separate the fingers really far apart
 If you face any issues with jupyter extensions, try:
```
pip3.8 uninstall jupyter_contrib_nbextensions
```
Reattempt to run the application
```
jupyter nbconvert --to notebook --execute main.ipynb
```


## Acknowledgments
- [opencv](https://opencv.org/) for the powerful computer vision library.
- MediaPipe
