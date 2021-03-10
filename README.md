# MotionDetector-openCV-bokeh

Detect objects that enter and exit a video capture device's field of view and record the timestamps to .csv file. Analyze said objects by time, size, and velocity and visualize this in a web-integrated plot.

### Packages used:
> *cv2*, *pandas*, *bokeh*

### Credit:
The code in the initial commit is written by Ardit Sulce. After that, committed code is written by me.

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
* From CLI, enter `py analyze_motion_detector.py`
* Press 'q' to quit capturing
* Timestamps saved to `times.csv`
* Plot saved to `plot_times.html` and opens in browser
