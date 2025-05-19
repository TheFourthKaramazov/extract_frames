# Video Frame Extractor

A Python CLI tool to extract evenly spaced frames from one or more `.mp4` video files.  
Frames are saved as `.png` images into an auto-named folder next to the input video.

## Requirements

- Python 3.7+
- numpy
- OpenCV (cv2)

## Installation

```bash
pip install numpy opencv-python
```

## Usage

```bash
python extract_frames.py [video1.mp4 video2.mp4 ...] --num-frames N
```

## Example

``` bash
python extract_frames.py ./test_video.mp4 -n 100
```
This will extract 100 evenly spaced frames from test_video.mp4 (ensure that your video is long enough at FPS for given number of frames) saved to

``` bash
./test_video_frames/frame_0000.png
./test_video_frames/frame_0001.png
...
```




