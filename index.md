# Portfolio
---
## Deep Learning

### Music Genres Recognition using Neural Networks

A Convolutional Neural Network (CNN) is used to model a music classification task. To achieve this, the GTZAN dataset is used (available in Kaggle) which comprises 100 audio samples for 10 different music genres, with each sample having a duration of 30 seconds.

Visual representations of each music sample are fed to the CNN as inputs, meaning audio data is transformed into images.

An accuracy of 84% and loss of 0.52 for the test set is obtained. The CNN model was trained using data augmentation tecnhiques in order to boost model performance (splitting each 30-second audio into 3-second samples along with noise injection), along with regularization techniques employed to ensure no overfitting is observed (Dropout, L2-regularization, and Reduce Learning Rate on Plateau).

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)]()
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)]()

<center><img src="images/Genre Recognition Project Banner.png"/></center>

---
<center>© 2023 David Issá. Powered by Jekyll and the Minimal Theme.</center>
