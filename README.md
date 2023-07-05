# Circle Hough Transform

Finds the circles in an image based on the [Circle Hough Transform algorithm](https://en.wikipedia.org/wiki/Circle_Hough_Transform). It works by using the Canny edge detector for retrieving the main edges for the circles we want to detect. Then use the Hough Transform algorithm to vote for the circle parameters a, b, r (circle center and radius). We can utilise Python by broadcasting the pixel coordinates to get a faster runtime. From the circle candidates apply non-maximum suppression to retrieve the best circles based on the most voted parameters.


Project was completed at ANU in course COMP4528 Computer Vision
