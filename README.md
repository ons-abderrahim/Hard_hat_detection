# Hard_hat_detection

This project aims to detect hard hats in images and videos by training a YOLOv5 model on a dataset of annotated images. The model is trained to identify hard hats in various orientations, lighting conditions, and backgrounds.
## Requirements

- Python 3.x
- PyTorch
- OpenCV
- YOLOv5

## Usage

To test the project, you will find two Jupyter Notebook files in the repository:
1. "YOLOv5_Custom_Training_hard_hat_detection.ipynb" for implementing the hard hat dataset into the YOLOv5 dataset 
2. "YOLOv5_model_deployment.ipynb" for the deployment of the model.

To test the "YOLOv5_model_deployment.ipynb" file, you will need to upload the "best.pt" file, which contains the trained weights of the model, and the image you want to test. Please rename the image as "image.jpg" before uploading it.
You can use Jupyter Notebook to run the .ipynb files.

## Results

The model achieved a mAP of 96.7%, 90.8% precision and 95.8% recall on the test set.

## Future Work

- Increasing the number of images in the dataset to improve model performance
- Training the model on a larger variety of hard hats and backgrounds
- Implementing the model on a real-time application

## References

- [YOLOv5](https://github.com/ultralytics/yolov5)
- [Roboflow](https://roboflow.com/)

## Contributing

If you would like to contribute to this project, please create a pull request.

## Contact

If you have any questions or feedback, please contact me at [ons.abderrahim@ieee.org]
