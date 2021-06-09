# ML and Implementation Documentation

Machine Learning: preprocess data using rescale, normalization and augmented using image data generator. Split dataset into train, validation and test. Building model with keras and tensorflow.js.

1. Download the dataset, and upload to google drive.
2. Do preprocessing dataset (resize, normalization and augmentation).
3. Split dataset into training, validation and testing using “train_test_split()” from sklearn.model_selection library.
4. Transform the label into binary label using “LabelBinarizer()” from sklearn.preprocessing library.
5. Using xception model and modification the model with add flatten, dropout and dense to the last layer.
6. Training and validating the model.
7. Use the converter to convert the keras model into the json model.
8. Upload the json model to repository in server.
9. Build REST API to get result from prediction and send result in json
10. Deploy model and REST API 
11. Create register and login for photo authentication, then create function for upload photo, then get the prediction result from server
