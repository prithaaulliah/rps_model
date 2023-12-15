# Modul6_ML

Overview Dataset
Dataset yang digunakan :  Images dengan total gambar 1764 gambar. Terdiri dari 3 kelas yaitu paper, rock, scissor.

Splitting Dataset : Training = 70%, Validation = 20%, Testing = 10%

# Preprocessing dan Modelling
Preprocessing Model 1 & 2 : resize(150,150), rotation_range=15, horizontal_flip=True, shear_range = 0.2, brightness_range = (0.2,1.0), zoom_range = 0.2, fill_mode = 'nearest'.

1. ResNet Model
   Summary Model 1 

![Screenshot (583)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/de52a905-214a-49b4-b4eb-a226e2ef2ac6)

Graph Loss dan Accuracy Model Resnet:
![Screenshot (584)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/60c362e9-35b0-42ef-aadd-4f7ce06a4c08)

Evaluation Matrix Model Resnet
![image](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/46e4c9ef-dad5-4c85-a147-a0d8a8fbf5b2)

2. MobileNet Model
   Summary Model 2

![Screenshot (586)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/021c935d-18f5-45ee-949d-220dc6e7fcf1)

Graph Loss dan Accuracy Model Mobilenet:
![Screenshot (587)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/7887d442-a34d-487b-8f30-327871107daa)

Evaluation Matrix Model MobileNet

![Screenshot (588)](https://github.com/prithaaulliah/Modul6_ML/assets/71914321/0e66abc9-0c99-4a6a-b972-be95b467703c)



