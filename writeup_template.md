### Reflection

###1. There are some method which was used in this project. In this project,a function will be defined to solve the problem which can find the lines of any color. Firstly,the color of the image will be change to gray, and a OpenCV's method which named Canny edge detector will be used to mark all edges of the image which color is changed in last step.Then,the vertices will be sitting to ignore some edges which are useless.Secondly,the important red lines will be found by the Hough transform method,and mix this lines and the original image in one image. Finally,write the image on video.

###2. My code has an important shortcoming,my code just can find the straight line, if the line type is curve line, my code will be dead such as in the challenge video. I think it maybe need check the line is straight or not and choose use line method or use ellipse method of OpenCV, but i have no idea how to do that.


###3. My line always is not continue that have a huge different with the example video. I think it maybe can use some method to draw a whole line when we use the Hough transform get two points. If it use other language I maybe can solve but I'm not good at python.