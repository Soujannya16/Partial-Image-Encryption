# Partial-Image-Encryption

Skills used- Deep Learning, Python

**The main purpose of the project is to build a system that will ensure quick yet reliable and secured transfer of image**

## 1.1 Problem Statement
In the recent times, due to the pandemic and the travel bans imposed, many people had to resort to consulting doctors through video calls. As a result confidential medical data was transferred in voluminous amounts to people over the internet. Also, when medical personnel need some suggestion from doctors of different countries, personal medical data needs to be transferred over the network medium, and it should be fast as it involves the patient’s condition. Even in case of military data sharing, this is needed. This is when partial image encryption is needed and valued.

## 1.2 Solution
Encrypting a part of the image called ROI, such that it makes the total image unusable.
In this project, we have detected the object using YOLO deep learning model, and encrypted using a substitution model. The flowchart is described in the report.

## 1.3 How to run
- Download the cfg and weights from https://pjreddie.com/darknet/yolo/ of any version. The cfg we have used is uploaded.
- Put these 2 files, yolo.txt file, pie.ipnyb and the image you want to parially encrypt in the same folder. For the image, we can use any image from the dataset folder, the code is tested on these images.
- Run it with jupyter notebook or vscode or anything similar.

## 1.4 Future Scope
This can be applied to videos as well using this method for each frames. This could be used in encrypting faces and objects in videos.
