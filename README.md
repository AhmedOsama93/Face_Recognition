# Face_Recognition
Developing a model to recognize faces using PCA to decrease dimensions  of images and Mean Square Error to detect faces.
#Principal Component Analysis(PCA)
* The goal: Find another basis of the vector space, which treats variations of data better. 

* Don’t choose the number of components manually. Instead of that, use the option that allows you to set the variance of the input that is supposed to be explained by the generated components
![image](https://user-images.githubusercontent.com/75946833/174461680-d017cbbd-2c76-42ae-b3ed-a00d72dbfe54.png)
* First Function:Convert the RGB image to Grayscale image (Black and white)
* ![22](https://user-images.githubusercontent.com/75946833/174462002-62a62cbf-b018-4f5d-80db-036187ec8a7e.JPG)

![22](https://user-images.githubusercontent.com/75946833/174462000-73ffd329-df13-4f62-b2c7-2c3b2315b008.JPG)

* Third Function:
Get the MSE between every two images and return the error
![image](https://user-images.githubusercontent.com/75946833/174461725-6fe4a8f0-b78c-480e-bb00-8507ba9838bf.png)
* Forth Function:
We take 4 images from user
One test and 3 for check.
First, we will convert the 4
Images to Grayscale.
![image](https://user-images.githubusercontent.com/75946833/174461743-c968cdc2-8634-4d2d-be9d-6a8fb593af16.png)
*Then we will resize our images 
![image](https://user-images.githubusercontent.com/75946833/174461747-329f24a8-07b6-4dc5-94d5-2db9c234b829.png)
* Security : ![image](https://user-images.githubusercontent.com/75946833/174461761-dbf6bc29-2f56-42aa-876f-5ecc8e56fd03.png)
