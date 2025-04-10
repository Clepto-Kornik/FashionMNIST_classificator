# FashionMNIST_classificator
In this exercise I have created a multiclass classificator with the use of a CNN network. The model provides satisfactory results with the 92% accuracy on the testing set.

## Fashion MNIST dataset

The Fashion MNIST is a dataset developed by Zalando Research. It comprises 70,000 grayscale images categorized into 10 fashion-related items. The dataset is divided into a training set of 60,000 images and a test set of 10,000 images.

The 10 labels of the dataset include:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot


### Dataset technical description:
- Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total.
- Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. 
- The training and test data sets have 785 columns. 
- The first column consists of the class labels (see above), and represents the article of clothing. 
- The rest of the columns contain the pixel-values of the associated image.
