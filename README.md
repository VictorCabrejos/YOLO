
# YOLO (You Only Look Once) Multi Object detection in images

This is an implementation of the popular YOLO algorithm which is extremely fast at detecting multiple objects in an image. 
The YOLO algorithm applies a neural network to an entire image. First it divides the image into an S x S grid and comes up with bounding boxes, which are boxes drawn around images and predicted probabilities for each of these regions.

The method used to come up with these probabilities is logistic regression. The bounding boxes are weighted by the associated probabilities. For class prediction, independent logistic classifiers are used.
