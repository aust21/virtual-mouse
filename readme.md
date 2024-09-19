# Drag and Drop

A real-time hand detection program for intuitive drag and drop interactions.

## Features

- Real-time hand detection for interactive drag and drop functionality
- Intuitive gesture controls: use finger positions to drag and release objects
- Cross-Platform Support: Runs on Windows, macOS, and Linux.

## Installation

### Prerequisites
Before you begin, ensure you have the following installed

- Python3

1. Clone the repo or [download](https://github.com/aust21/drag-and-drop/archive/refs/heads/main.zip)

```
git clone https://github.com/aust21/drag-and-drop
cd drag-and-drop
```

### Set up a virtual environment

1. Create a virtual environment

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
2. Create a kernel
```bash
python3 -m ipykernel install --user --name=myenv --display-name "Python (myenv)"
```
 
3. Install the required modules

```
pip3 install -r requirements.txt
```

## Usage
Run the program

```
jupyter nbconvert --to notebook --execute main.ipynb
```
### Gesture controls:

- Show your index finger to the camera to interact
- Raise all fingers (give a high five) to exit the program
- Hold your index and middle fingers close together to perform a click

## Troubleshooting
If you encounter issues with Jupyter extensions, try the following:

1. Uninstall the problematic extension:
```
pip3 uninstall jupyter_contrib_nbextensions
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
