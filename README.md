# Object-localisation-with-Tensorflow

# Project explanation:
The idea is to localize emojis with a bounding box, but is not like a normal computer vision project where we train the model with images and move a sliding window through the image and find the object, we calculate the intersection over the union between the grounding boxes and then train the model according to the IoU metric.

# Steps of the project:
Download and visualize data.
Create examples for training.
Bounding boxes plotting.
Data generator.
Model creation.
Custom metric: Intersection over union.
Compile the model.
Custom callback and model testing.
Model training.
