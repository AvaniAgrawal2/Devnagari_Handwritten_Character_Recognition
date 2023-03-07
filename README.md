# Devnagari_Handwritten_Character_Recognition using NBC
Devanagari Handwritten Character Recognition (DHCR) is a popular area of research in the field of computer vision and machine learning. It involves recognizing handwritten characters of the Devanagari script, which is used to write several Indian languages including Hindi, Marathi, and Nepali.

Naive Bayes Classifier (NBC) is a popular machine learning algorithm used for classification tasks. It is a probabilistic classifier that uses Bayes' theorem to calculate the probability of a given input belonging to a particular class.

Dataset
The Devanagari Handwritten Character Dataset, which contains 78200 images of 46 different Devanagari characters.

Data Preprocessing
We will use NumPy libraries for image processing. First, we will resize all images to 32x32 pixels and convert them to grayscale. Then, we will flatten the 2D array of each image into a 1D array of 1024 pixels.

Model Training
We will split the dataset into training and testing sets. We will use 70% of the data for training and 30% for testing. Then, we will train a Naive Bayes classifier using the training data.

Model Evaluation
We will evaluate the performance of the Naive Bayes classifier on the test data using the accuracy metric.

Conclusion
We used the Naive Bayes algorithm to recognize handwritten characters. We achieved an accuracy of around 68% on the test data, which is decent but not very high. There are many ways to improve the performance of this classifier, including using more advanced algorithms, using more data, and performing more extensive data preprocessing.
