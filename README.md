# CNN Based Protein Structure Classification

#### Abstract
The Aim is to study and predict the various protein structures in cellular images using Keras-CNN and having Tensorflow at backend for speedy prediction. I will be approaching to the prediction following the below mentioned sequaential process:

1. Encoding of binary target labels out of the given multilabel list per image.
2. Visual analysis of target protein distribution in the train set.
3. A simple image generator that yields images of a target-protein-wishlist. Each sample that has at least one match with this list is returned.
4. Some ideas on validation.
5. A baseline model build with keras that is supported by:
	• A modelparameter class that holds all parameters that are necessary to build the model, to load the data and to preprocess the images.
    • A data generator that can be used with CPU/GPU computing to perform training and validation.
	• An image preprocessor that rescales, reshapes and normalizes the images for feeding into the model.
6. Ideas on how to improve the baseline model by tracking loss with a keras callback, Tune hyperparameters.

#### Our goal
• Predict various protein structures in cellular images
• there are 28 different target proteins
• multiple proteins can be present in one image (multilabel classification)
• 27 different cell types of highly different morphology
#### Data 

• https://www.kaggle.com/allunia/protein-atlas-exploration-and-baseline/data




