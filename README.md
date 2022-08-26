# cv2-bridge

1.start a simulation of any bot which publishes an image topic.<br>
2.run rostopic list inorder to list the topic being published<br>
3.create a new .py file in yourworkspace/src folder and copy the code present in cv2_bridge file.<br>
4.make sure to edit the image topic in the code according to the topic published by the bot<br>
5.run "chmod +x <filename>.py" to make it executable.<br>
6.in the same folder create a new launch file (<filename.launch>) and copy the code in bridge.launch file .<br>
7.now run "roslaunch <your folder> <filename.launch>".<br>
8.a new dialog box showing the python image appears.<br>
