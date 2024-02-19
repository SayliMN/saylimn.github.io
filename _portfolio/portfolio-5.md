---
title: "### Classification of IDC in Breast Cancer Histopathology Images"
# excerpt: "#### GloVe, Word2Vec<br/>"
collection: portfolio
---

<p style="font-size:15px; color:gray; font-style: italic; margin-top: 25px;">Keywords: Image classification, Convolutional neural network, Optimizers, Machine learning algorithms, Visualization, Image processing </p>


<p style="font-size:15px">
    1. Breast cancer is the most common form of cancer in women, and invasive ductal carcinoma (IDC) is the most common form of breast cancer. The goal was to identify IDC when it was present in otherwise unlabeled histopathology images
</p>
<p style="font-size:15px">
    2. The dataset contained 5547 breast histopathology images, each with a pixel size of 50 x 50 x 3. Among these images, there were 2759 negative (-) IDC counts and 2788 positive (+) IDC counts
</p>
<p style="font-size:15px">
    3. Classification was assessed across multiple ML algorithms and six different convolutional neural networks with each network architecture paired with three different optimizers, namely, Adam, Adadelta and RMSprop
</p>
<p style="font-size:15px">
    4. Accuracy and loss for each network were observed in order to conclude better performing convolutional neural network
</p>
<p style="font-size:15px">
    5. The Support Vector Machine performed well in predicting IDC labels among 6 other machine learning models, followed by the Random Forest Classifier. In neural networks, the CNN with Adam optimizer outperformed other models, ranking as the top performer
</p>

<p>
    <img src="/images/IDC.png" alt="IDC" style="display: block; margin-left: auto; margin-right: auto; width: 600px;">
</p>
<p>
    <img src="/images/cnn.png" alt="cnn architecture" style="display: block; margin-left: auto; margin-right: auto; width: 600px;">
</p>

<p style="margin-top:10px">
    <img src="https://img.shields.io/badge/Python-green" alt="Python">
    <img src="https://img.shields.io/badge/Jupyter%20Notebook-orange" alt="Jupyter Notebook">
    <img src="https://img.shields.io/badge/Google%20Colab-cornflowerblue" alt="Google Colab">
    <img src="https://img.shields.io/badge/Keras-navy" alt="Keras">
    <img src="https://img.shields.io/badge/OpenCV-orchid" alt="OpenCV">
</p>