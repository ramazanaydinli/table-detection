# table-detection

Aim of this work is obtaining information from tables given in image. For this purpose, TensorFlow, Keras-OCR and OpenCV used. Chosen model is EfficientDet D1 640x640. Model is trained using ICDAR-2019 CascadeTabNet data. Example result is given below:

Briefly, input is at the top and output is at the bottom:

![image](https://user-images.githubusercontent.com/80748060/211228547-7f2bf1d1-deb0-4c8a-95ce-0477ad80899f.png)


If you want longer explanation here are the steps:


Input Image:

![table_6](https://user-images.githubusercontent.com/80748060/211228407-aae1e544-7b55-40c0-9a8a-2c6bc4dacc28.png)


Prediction Result:

![image](https://user-images.githubusercontent.com/80748060/211228440-6c6507b1-2f81-4222-8335-dcf21b8f96bc.png)


Isolated part of the image according to the predicted bounding boxes:

![image](https://user-images.githubusercontent.com/80748060/211228468-9f546784-4130-4cc9-9b85-5c64d7adbfba.png)


Keras-OCR reading results:

![image](https://user-images.githubusercontent.com/80748060/211228479-6ce23748-0a34-4ba8-8907-befe7b627281.png)


After some process, final output given in the pandas dataframe:

![image](https://user-images.githubusercontent.com/80748060/211228503-ba31cae7-a29a-4e8c-ac70-c29f777b7123.png)
