# ROS
I have followed a folllowing steps to build this project:
1. first of all createa a directory catkin_ws/src , then build that workspace
2. then after navigating to src directory, i created a package for obstacle detection, then in src directory added a python code to do obstacle detection using yolov4 using openCv library
3. I created a custom messages to display bounding box messages
4. i have also added a launch file to launch it in one go
5. then, i edited package.xml file to add few dependencies related to the message generation and message runtime as well for cv_bridge and cv2
6. then i edited CmakeLists.txt file to add all dependencies and build information
7. then i moved to root folder and built it, as well installed it as well
8. then i ran a master node from a terminal, ran rosbag and then ran a obstacle detection node and analysed the results using rqt_image_view command.
