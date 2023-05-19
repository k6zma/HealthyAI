# **HealthAI** _The project is under development_

## **Used technology stack:**

<img src="https://img.shields.io/badge/PYTHON-black?style=for-the-badge&logo=python&logoColor=gold"/><img src="https://img.shields.io/badge/PYTORCH-black?style=for-the-badge&logo=PyTorch&logoColor=orange"/><img src="https://img.shields.io/badge/JUPYTER-black?style=for-the-badge&logo=jupyter&logoColor=orange"/><img src="https://img.shields.io/badge/LINUX-black?style=for-the-badge&logo=linux&logoColor=yellow"/><img src="https://img.shields.io/badge/GIT-black?style=for-the-badge&logo=git&logoColor=orange"/><img src="https://img.shields.io/badge/NUMPY-black?style=for-the-badge&logo=NumPy&logoColor=013243"/><img src="https://img.shields.io/badge/PANDAS-black?style=for-the-badge&logo=Pandas&logoColor=pink"/><img src="https://img.shields.io/badge/VSC-black?style=for-the-badge&logo=Visual Studio Code&logoColor=007ACC"/><img src="https://img.shields.io/badge/GITHUB-black?style=for-the-badge&logo=GitHub&logoColor=white"/>

## **Data link**:

https://drive.google.com/drive/folders/1PHT2ZVzbfxccRnOb5tl2r4Enrk7YXlMP?usp=share_link

## **Idea of project**:

<p>My project is a system based on neural networks that allows you to quickly and accurately identify possible lung diseases from photographs. The system is able to detect such dangerous diseases as pneumonia, tuberculosis and coronavirus, which will help doctors quickly and accurately diagnose and prescribe the necessary treatment.</p>

## **1) Data analysis**

<p>The entire dataset was compiled from various datasets from Kaggle.com. At the moment, the dataset consists of four classes:</p>

- Pneunomia
- Covid-19
- Normal
- Tuberculosis

<p>Unfortunately, medical data is a very valuable resource that is very difficult to find unless you work with a medical company, so there is a rather strong class imbalance in the first version.</p>

![disbal_train_v1](img/LungsCheck/LungsCheck_V1/disbal_train.png "Lungs Images train")

![disbal_test_v1](img/LungsCheck/LungsCheck_V1/disbal_test.png "Lungs Images test")

![disbal_val_v1](img/LungsCheck/LungsCheck_V1/disbal_val.png "Lungs Images val")

<p>In order to get rid of it, it was decided to equalize the number of elements in each class according to the minimum number.</p>

## **3) Results**

<p>LungsModel V2 is currently being trained</p>
