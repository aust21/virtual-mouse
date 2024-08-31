# Drag and Drop

A real-time hand detection program for intuitive drag and drop interactions.

## Features

- Real-time hand detection for interactive drag and drop functionality
- Intuitive gesture controls: use finger positions to drag and release objects
- Cross-Platform Support: Runs on Windows, macOS, and Linux.

## Installation

### Prerequisites
Before you begin, ensure you have the following installed

- Python 3.8
- OpenCV
- Anaconda or jupyter notebook

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
pip install jupyter
```

```
pip3.8 install -r requirements.txt
```

## Usage
Run the program

```
jupyter nbconvert --to notebook --execute main.ipynb
```
### Gesture controls:
To drag a box: Bring your index and middle fingers close together
To drop a box: Separate your index and middle fingers

## Troubleshooting
If you encounter issues with Jupyter extensions, try the following:

1. Uninstall the problematic extension:
```
pip3.8 uninstall jupyter_contrib_nbextensions
```

2. Reattempt to run the application
```
jupyter nbconvert --to notebook --execute main.ipynb
```
If problems persist, please open an issue on the GitHub repository.


## Acknowledgments
- OpenCV for providing a powerful computer vision library
- MediaPipe for advanced hand-tracking capabilities
- The open-source community for continuous support and contributions
