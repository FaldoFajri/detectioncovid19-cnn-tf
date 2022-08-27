# detectioncovid19-cnn-tf
Detection of Covid-19 on X-Ray Image of Human Chest Using CNN and Transfer Learning

At the end of 2019, a new disease called Coronavirus Disease (COVID-19) originated in Wuhan, China. This disease is caused by respiratory tract infections, ranging from the common cold to serious diseases such as Middle East Respiratory Syndrome (MERS) and Severe Acute Respiratory Syndrome (SARS). In Indonesia, there are tests to detect COVID-19, such as PCR and Rapid Test. This detector takes a long time and is less accurate in producing a diagnosis. This study aims to classify chest X-ray images using CNN and Transfer Learning methods to diagnose COVID-19. The proposed model has 4 scenarios: CNN Handcraft Model, Transfer Learning (VGG 16, VGG 19, and ResNet 50). This model is accompanied by data augmentation and data balancing techniques using undersampling techniques. The dataset used in this study is the “Covid-19 (COVID-19 and Normal) Radiographic Database” with 13,808 data divided into two classes, namely COVID-19 and Normal. Each model built will produce values for accuracy, precision, recall, and confusion matrix. The results of CNN Scenario 1 accuracy is 95%, in Scenario 2 VGG 16 the accuracy is 93%, Scenario 3 VGG 19 is 90% and Scenario 4 ResNet 50 is 80%.

Dataset : https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

Publication : https://doi.org/10.29207/resti.v6i3.4118
