# Video-Processing-and-Ball-Tracking
Ball Tracking and Event Logging in Video
This project implements a computer vision solution to track the movement of balls of different colors across various quadrants in a given video. The program records each event of a ball entering and exiting numbered quadrants and saves these events to a text file. The processed video and event log file are saved locally.

Table of Contents
Overview
Requirements
Installation
Usage
File Descriptions
Acknowledgments
Overview
The program performs the following tasks:

Loads the provided video.
Detects balls of specified colors (red, blue, and green).
Tracks the movement of these balls across predefined quadrants.
Logs each entry and exit event of the balls in the quadrants.
Saves the processed video with visual overlays and the event log to local files.
Requirements
Python 3.x
OpenCV
NumPy
Pandas
Matplotlib
Installation
Clone the repository:
sh
Copy code
git clone [GitHub Repository Link]
Change into the project directory:
sh
Copy code
cd ball-tracking-project
Install the required packages:
sh
Copy code
pip install -r requirements.txt
Usage
Place your video file in the project directory and update the video_path variable in the script with the path to your video file.

Run the script:

sh
Copy code
python ball_tracking.py
The script will process the video, track the balls, and save the processed video and event log to the local directory.

File Descriptions
ball_tracking.py: Main script for processing the video, tracking balls, and logging events.
requirements.txt: List of required packages.
events_log.txt: Log file containing the timestamp, quadrant number, ball color, and event type (entry/exit).
processed_video.avi: Processed video with ball tracking and event overlays.
Acknowledgments
This project was developed as part of an assignment for the AI Role application process. Special thanks to the assignment team for providing this opportunity.
