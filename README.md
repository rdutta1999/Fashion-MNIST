# Fashion-MNIST
Identification of clothing type from article images


Download the Dataset from [Fashion MNIST](https://www.kaggle.com/zalando-research/fashionmnist/downloads/fashionmnist.zip/4) on Kaggle.

Keras ImageDataGenerator has been used for performing Data Augmentation. The CNN model has Global Average Pooling at the end instead of Dense layers to prevent overfitting.

The final model having the best validation accuracy is saved as model.h5, and the test output is saved as test_output.csv.
