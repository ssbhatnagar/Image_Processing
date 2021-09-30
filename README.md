# Image_Processing
Libraries used in this task - 
1. Open CV
2. Matplotlob
3. Numpy

I used OpenCV for this task which is a useful library for computer vision. I performed some rough work to get the coordinates of the bounding box that includes -
1. Calculating the size of images (1600X1200).
2. Then I performed some estimation for getting the coordinates of the bounding box. Firstly I cropped the image in the top half to get the top right corner coordinate then I cropped it in the bottom half to get the left corner coordinates.
3. Repeated the above step for the second image.
4. Then used cv2.rectangle() method for generating a bounding box along with the Region of Interest.
5. Lastly I cropped them along the ROI.

Challenges faced - The main challenge was to calculate the coordinates of the bounding box. It took some time and effort to figure out the perfect coordinates as per the need.
