# ROS
I have followed the following steps to build this project:
1. first of all created a directory catkin_ws/src, then build that workspace
2. then after navigating to the src directory, I created a package for obstacle detection, then in the src directory added a python code to do obstacle detection using yolov4 using OpenCV library
3. I created custom messages to display bounding box messages
4. I have also added a launch file to launch it in one go
5. then, I edited the package.xml file to add few dependencies related to the message generation and message runtime as well for cv_bridge and cv2
6. then I edited the CmakeLists.txt file to add all dependencies and build information
7. then I moved to the root folder and built it, as well installed it as well
8. then I ran a master node from a terminal, ran the rosbag, and then ran an obstacle detection node and analyzed the results using the rqt_image_view command.
