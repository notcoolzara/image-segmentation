# Image Segmentation
This project implements an image segmentation model using the UNet architecture. The dataset consists of images and corresponding masks for segmentation tasks. The code includes data loading, training, evaluation, and visualization functionalities.

## Steps:
- Data Preparation: Load and preprocess images and masks.
- Model Definition: Set up the UNet model architecture for image segmentation.
- Training: Train the model on the training dataset using Adam optimizer and BCEWithLogitsLoss.
- Evaluation: Evaluate the model's performance on the test dataset using loss and Intersection over Union (IoU) metrics.
- Visualization: Visualize training loss and IoU score over epochs, and visualize predictions on test images.


# Prerequisites
pip install torch torchvision pillow matplotlib tqdm

# Result
![image](https://github.com/xmonstabebex/image-segmentation/assets/89215956/a2ba44d8-0440-43ad-a998-b646d346011d)
