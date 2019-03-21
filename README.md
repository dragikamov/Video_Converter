# Faro Coding Task

1. The program should have a GUI where it is possible for the user, to choose a video from a folder and import it, also choose the folder to export the processed video.

2. Your program should convert the video frames to grayscale.

3. You should do a Canny Edge Detection on each frame. Please note that this part should be implemented from yourself and not use a preimplemented function of a library (as in opencv for e.x.).

4. The computed frame should be put together to a stream and be saved as a video to the chosen folder.

5. (Optional) Please do a real time edge detection and play the original and processed video, side by side on your GUI.

## Prerequisites

What things you need to install the software and how to install them

```
python 3.7.0 https://www.python.org/downloads/release/python-370/
numpy https://scipy.org/install.html
scipy https://scipy.org/install.html
PyQt5 https://www.riverbankcomputing.com/static/Docs/PyQt5/installation.html
opencv-python https://pypi.org/project/opencv-python/
```

To install `numpy`, `scipy`, `PyQt5` and `opencv-python` the python `pip3 install {library}` script can be used.

## Running the code

In order to run the code you would need to execute the following line in the terminal of your operating system

### Windows

```
python gui.py
```

### Linux/Mac

```
python3 gui.py
```

## Explanation

The video provided to me was of quality 4k 60fps and even after optimizing my code it was always so slow and so demanding from my computer. I was running the code on a computer with i9 processor with 32GB of RAM and it still wasn't enough for the computation to be fast enough. Therefore, I only ran a small section of the 4k video with my algorithm and that can be seen [here](). After that I decided to compress the video (with `resizing.py`) to 1080p resolution and a part of that video can be found [here]().  

**Please note** that the following algorithm has **60** threads, if your system doesn't support running 60 threads simultaneously please change the variable `nThreads` in `main.py`.

## Submitted files

```
cannyEdge.py
gui.py
main.py
resizing.py
README.md
```

The 4k images and video processed can be found [here](), and the 1080p video can be found [here]().

## Made by

* **Dragi Kamov** - [Github](https://github.com/dragikamov) - [LinkedIn](https://www.linkedin.com/in/dragikamov)