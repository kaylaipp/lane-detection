# Lane Detection
> Build a lane detector with Python and OpenCV :)
## To run 
```sh
python laneDetectionVideo.py
```

## Preview
![Final output video](https://github.com/kaylaipp/lane-detection/blob/main/media/final.gif)

[Original video](https://www.youtube.com/watch?v=IWIOafpMi4E)

## Steps 
1. Grayscale frame
<img src="https://github.com/kaylaipp/lane-detection/blob/main/media/grayFrame.png" width="400" height="225">
2. Gaussian blur grayscale frame
<img src="https://github.com/kaylaipp/lane-detection/blob/main/media/gaussianFrame.png" width="400" height="225">
3. Detect edges using Canny edge algorithm
<img src="https://github.com/kaylaipp/lane-detection/blob/main/media/edgeFrame.png" width="400" height="225">
4. Create mask for region of interest
<img src="https://github.com/kaylaipp/lane-detection/blob/main/media/roiMask.png" width="400" height="225">
<img src="https://github.com/kaylaipp/lane-detection/blob/main/media/roiFrame.png" width="400" height="225">
5. Detect lines through Hough transform
<img src="https://github.com/kaylaipp/lane-detection/blob/main/media/houghLinesFrame.png" width="400" height="225">
6. Average lines from Hough transform and draw on frame
<img src="https://github.com/kaylaipp/lane-detection/blob/main/media/averagedLines.jpg" width="400" height="225">

