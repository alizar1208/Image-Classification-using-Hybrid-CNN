Given a dataset of 1500 CT scans of various body parts such as head, abdomen, chest and head, the goal was to train machine learning models to train the models in order to classify the images. These are the steps that I followed to optimize the accuracy of the model:
 1. Apply required preprocessing steps.
 2. Construct a CNN to extract the features from the images.
 3. Extract the features constructed by the convolutional layers from an intermediate dense layer.
 4. Apply KNN to the extracted features.
 5. Apply Randim Forest with hyperparameter tuning to the extracted features.
 
 
