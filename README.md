# fashionMNIST
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

The original MNIST dataset contains a lot of handwritten digits. Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try. "If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others."

Zalando seeks to replace the original MNIST dataset

# Accuracy and Model Details
My model consists of five layers with one input and output layer and three hidden layers respectively. Most of the details about it are clearly commented in my code. With the above architecture, I was able to achieve an accuracy of 88.3%.

# Labels
Each training and test example is assigned to one of the following labels:
<ul>
<li>0 T-shirt/top</li>
<li>1 Trouser</li>
<li>2 Pullover</li>
<li>3 Dress</li>
<li>4 Coat</li>
<li>5 Sandal</li>
<li>6 Shirt</li>
<li>7 Sneaker</li>
<li>8 Bag</li>
<li>9 Ankle boot</li>
</ul>

# Libraries Used
<ul>
<li>Pytorch</li>
<li>Numpy</li>
<li>Matplotlib</li>
</ul>
