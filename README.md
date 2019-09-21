# Fashion-MNIST
Identification of clothing type from article images


Download the **Dataset** from [Fashion MNIST](https://www.kaggle.com/zalando-research/fashionmnist/downloads/fashionmnist.zip/4) on Kaggle. The **Train** and **Test** csv files are then placed in the **same directory** where the IPYNB file resides.

**Keras ImageDataGenerator** has been used for performing Data Augmentation. 

We use a custom **CNN** model which has a **Global Average Pooling Layer** at the end instead of Dense layers to prevent overfitting.

We train the model using **Adam** as the optimizer for **500** epochs and use **Checkpoints** to save the model when it has the highest Validation accuracy.

We then load the Checkpoint model with the **best validation accuracy**, and use it to predict the Test cases, which got us a score of **0.9182 (91.82% accuracy)**.
