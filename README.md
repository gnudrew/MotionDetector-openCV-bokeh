# MotionDetector-openCV-bokeh

A script that detects when objects enter and exit the frame of a video capture device and writes these timestamps to a .csv file.
Another script that builds a web-integrated plot to visualize the time data.

### Packages used:
> *cv2*, *pandas*, *bokeh*

### Credit:
The code in the initial commit is written by Ardit Sulce. The code in the following commits is my own, unless noted otherwise.

### To run the app: 
To run with times saved to .csv but no plot:
* Connect video capture device, such as webcam
* Open CLI in this directory
* Enter `py motion_detector.py`
* Display window will show the video feed with rectangles drawn around detected objects
* Press 'q' to quit capturing
* Timestamps saved to `times.csv`

To run with times saved to .csv with a web-integrated plot:
* Same as above, except..
* From CLI, enter `py plot-motion_detector.py`
* Press 'q' to quit capturing
* Timestamps saved to `times.csv`
* Plot saved to `plot_times.html` and opens in browser
