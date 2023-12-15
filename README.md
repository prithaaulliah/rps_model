![Screenshot (589)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/7ff58901-aa2a-45c3-b40f-69347c35c22c)# Modul6_ML

Overview Dataset
Dataset yang digunakan :  Images dengan total gambar 1764 gambar. Terdiri dari 3 kelas yaitu paper, rock, scissor.

Splitting Dataset : Training = 70%, Validation = 20%, Testing = 10%

# Preprocessing dan Modelling
Preprocessing Model 1 & 2 : resize(150,150), rotation_range=15, horizontal_flip=True, shear_range = 0.2, brightness_range = (0.2,1.0), zoom_range = 0.2, fill_mode = 'nearest'.

1. ResNet Model
   Summary Model 1 
![Screenshot (583)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/ed8dc68d-6b74-4eed-b545-5fe2654ccc1a)

Graph Loss dan Accuracy Model Resnet:
![image](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/db25cb31-3767-4a4b-9849-a5c7e0008da0)

Evaluation Matrix Model Resnet
![image](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/46e4c9ef-dad5-4c85-a147-a0d8a8fbf5b2)

2. MobileNet Model
   Summary Model 2
![Screenshot (586)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/df6eb134-0dff-4fb0-a11c-1e3547100b17)

Graph Loss dan Accuracy Model Mobilenet:
![Screenshot (587)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/7887d442-a34d-487b-8f30-327871107daa)

Evaluation Matrix Model MobileNet
![Screenshot (588)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/25613cbb-ceb1-47cd-b6d4-8bd71b0354d7)




