# DragFace

This repo is set up to document my project progress "DragFace"


### Have you ever wondered what would your face look like if you put on drag make-up?
"DragFace" is a GAN based machine learning project that transforms a normal selfie into a full-on Drag Face.

Model training code can be viewed [here]()

A detailed blog post is available on [Medium (Towards Data Science)]
(https://towardsdatascience.com/dragface-training-a-gan-for-drag-queen-transformation-7daf1958e517)

## Current Results:

![](/image/header.jpg)


## Next Steps
1. Look into how to improve the translated wigs appearances. Potentially modify the model so that the AdaLIN applies the ratio of instance vs. layer normalization varying as a function of the location on the image (facial area uses more instance normalization and the outer area uses more layer normalization)
2. Collect more data for model training. The current training set size is only 1000 per class. 
