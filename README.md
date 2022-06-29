# Fashion-Color-Identification

Dataset - https://www.kaggle.com/datasets/imoore/6000-store-items-images-classified-by-color

Here is a novel dataset for image classification. 6239 images are classified into 12 categories based on their color.
I have modified the above dataset a little by adding a validation directory.

</br>
Here are some of the sample images from the training set

![Screenshot 2022-06-29 164045](https://user-images.githubusercontent.com/52671445/176423018-a1291e60-7278-4fbe-b694-da776c115edc.jpg)

</br>
This is a multiclass classification task, with 12 classes, I have used **InceptionV3 model** and transfer learning to train on the data set and achieved a **validation accuracy of 80%**.

</br>
Here are some of the model's predictions on the validatation data

![Screenshot 2022-06-29 163506](https://user-images.githubusercontent.com/52671445/176423508-fb1b6c10-11db-4ad7-aa3d-67a9455b2cc2.jpg)
![Screenshot 2022-06-29 163537](https://user-images.githubusercontent.com/52671445/176423524-987620c3-bf74-4c2a-b780-0978502eef3f.jpg)

</br>
Here are some the model's prediction for unseen data
![Screenshot 2022-06-29 163619](https://user-images.githubusercontent.com/52671445/176423740-711a0324-2ffb-4238-9510-9b5a6a73c9ac.jpg)
