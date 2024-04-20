# Relation Network
## For YOLOv8

The relational network repository is a collection of tools and frameworks designed to facilitate the integration and management of relational data within deep learning models. When used in conjunction with YOLOv8, a state-of-the-art object detection model, relational networks can enhance the model's ability to interpret complex relationships between objects in an image. This integration is particularly useful in scenarios where understanding the context and interactions among multiple objects significantly improves detection performance. By leveraging relational networks, YOLOv8 can more effectively identify and classify small or densely packed objects, making it a powerful tool for applications requiring high accuracy in dynamic environments.

## Requirements
* PyTorch
* OpenCV
* Numpy
* Pickle
* Tqdm

## Usage
1. Generate the dataset by running the [data_generator.py](data_generator.py) script.
2. Start the training using the [train.py](train.py) script. This script will automatically evaluate on the test set at the end of the training.
3. To make predictions on new data, refer [Relation Networks_Sort-of-CLEVR.ipynb](Relation Networks_Sort-of-CLEVR.ipynb).
