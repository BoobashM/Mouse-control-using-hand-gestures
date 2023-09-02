Steps to execute the python program:
   1.Install the lastest version of python from https://www.python.org/downloads/.
   2.Install the required Python packages mentioned : 
       •numpy
       •opencv-python
       •wxPython
       •pynput
   3.After finishing the setup copy the code from the file and execute in the python shell


NOTE:
  1.Change the bgr value range according to your skin color, provide a range i.e. skin color appears different when exposed to different amount of light
  2.When your palm is open you can move the mouse with your hand gestures. When you form a fist a left click is performed.


The philosophy behind this project is as follows :
   1•We specify the color range of interest i.e. the color of the glove.
   2•Using the color range we filter only objects having that color code.
   3•Next, we select the region of interest. The region with the maximum area in our feed.
(This region of interest lies in the color range).
   4•Now, we associate the mouse controls with the movements of our ROI ( Region of interest, hand in this case).
