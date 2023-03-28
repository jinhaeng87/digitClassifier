# Digit Classifier with Deep Learning

This project is the classic image recognizer or classifier of ten different digits via neural networking and deep learning.
Please note that the dataset used in the project can be retrieved from <a href>https://www.kaggle.com/competitions/digit-recognizer

## About Data
<p>It is a classic dataset of handwritten images of digit 0 through 9 from the infamous MNIST.<br>
The packet contains both sets for training and testing purposes, respectively and utilizing panda's dataframe, we can further investigate how the data is composed of </p>
<br>
~~~
train_df = pd.read_csv('train.csv')
test_df = pd.read_csv('test.csv')
~~~
~~~
train_df.head()
test_df.head()
~~~
