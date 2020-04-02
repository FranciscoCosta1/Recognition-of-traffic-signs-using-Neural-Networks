# Recognition of traffic signs using Neural Networks

Academic Project for the course of **Deep Learning Neural Networks**

Group: Francisco Costa, João Gouveia, Pedro Rivera, Nuno Rocha

Programming Language: **Python**

Most relevant libraries used: **Pandas, Numpy, Tensorflow, Matplotlib, Seaborn, Sklearn...**

Under the concept of Convolutional Neural Networks (**CNNs**), this project aims to answer a challenge usually faced in this growing industry: ### **the recognition of traffic signs**.

After a first phase of data exploration and preprocessing, it was decided to follow two different approaches: one in which a model is built from scratch, and another using the pretrained model VGG16 (exploratory).

The public dataset GTSRB (German Traffic Sign Recognition Benchmark ) is available on this [link](https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/published-archive.html). 

In detail we used the [GTSRB-Training_fixed](https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/GTSRB-Training_fixed.zip) for the training and validation sets and for testing purposes we selected the [GTSRB_Online-Test-Images-Sorted](https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/GTSRB_Online-Test-Images-Sorted.zip).

With the model built from scratch, it was achieved a precision_test and recall_test of **97%**.
