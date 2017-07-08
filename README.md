# Image Retraining

Classification of images using TensorFlow. Pre-trained Inception v3 model is used to implement Transfer learning that retrains from the existing weights of fully-trained model for a set of categories like ImageNet for new classes of images.

The file **`retrain.py`** is to be run to train the model and generate graph and label files.

The command is:

`python retrain.py --output_graph=retrained_graph.pb --output_labels=retrained_labels.txt --image_dir=path_to_dataset`

The file **`label_image.py`** is to predict the result for test image

The command is:

`python label_image.py path_to_image_image.jpg`
