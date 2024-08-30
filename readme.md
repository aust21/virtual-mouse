# Drag and drop

Drag and drop program

## Features

- Real-Time hand detection.

- Cross-Platform Support: Runs on Windows, macOS, and Linux.

## Installation

### Prerequisites

- Python 3.x
- OpenCV

clone the repo or [download](https://github.com/aust21/drag-and-drop/archive/refs/heads/main.zip)

```
git clone https://github.com/aust21/drag-and-drop
cd video-filters
```

### Set up virtual environment

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
pip install -r requirements.txt
```

## Usage
Run the program

```
jupyter nbconvert --to notebook --execute main.ipynb
```
To drag a box: put your index and middle fingers closely together
To drop(let go) of the box: separate the fingers really far apart

## Acknowledgments
- [opencv](https://opencv.org/) for the powerful computer vision library.
- MediaPipe
