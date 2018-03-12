# Traffic Sign Classification
The scope of this project is to explore German Traffic Sign data (http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) by showing sample images and visualizing data on histogram graph. Then, the main goal after understand the data is to build a deep learning model using TensorFlow library to classify new traffic sign images.

See `Traffic_Sign_Classifier.ipynb` for codes, visualization and discussion.

## Dependencies
- Python 3
- Pickle
- matplotlib
- OpenCV
- Numpy

## Other files usage:
- `model.ckpt.*`: to test traffic sign image, re-load evaluation function in the notebook and restore the training model.
- `signnames.csv`: the list of all the traffic sign that were trained in training samples. 
- `test_images`: random traffic sign images from Google Images.
