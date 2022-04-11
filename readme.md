# Task 1.1- Data Visualization
Fisrt to complete the given task we go through the given data.
We go through json files and find that there were many type as the coordinate of a point on the car which could be anywhere on the car as bumper, light...etc.
We downloaded all the given files and stored them in the current directory.
then we us python libraries to read the json files and craete array of polygonlabels.
Then we got bounding box with the given polygon labels and unnormalize the points with the given formula.
We plotted the rectangle using CV2.
WE filled the colour in the bounding box This part was a liitle hactic but somehow we managed to do it with the help of internet
https://stackoverflow.com/questions/17241830/opencv-polylines-function-in-python-throws-exception
https://www.geeksforgeeks.org/python-opencv-cv2-cvtcolor-method/?ref=lbp
https://www.geeksforgeeks.org/python-opencv-cv2-cvtcolor-method/?ref=lbp

I took help from these sourses to complete the assignment.

This is showing all the defects on the car and making boundary around them.
