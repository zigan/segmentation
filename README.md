My note about segmentation from previous available tutorial. 
<br>I reproduce the code from the main reference:
https://towardsdatascience.com/efficient-image-segmentation-using-pytorch-part-1-89e8297a0923
<br>additional reference:
<br>https://www.v7labs.com/blog/image-segmentation-guide
<br>https://setosa.io/ev/image-kernels/
<br>https://www.robots.ox.ac.uk/~vgg/data/pets/
<br>https://towardsdatascience.com/a-basic-introduction-to-separable-convolutions-b99ec3102728

# Segmentation
![image](https://github.com/zigan/segmentation/assets/15936043/76f91339-a8ed-4d4b-9173-105ed2a41882|width=100px)
<br>Image segmentation is a technique to isolate pixels belonging to specific objects in an image.
Image segmentation partitions/segments : Objects. Backgrounds, and Boundaries. Image segmentation extends image classification by outlining the object's boundary to pinpoint the corresponding object. There are three types of segmentation:
* Semantic Segmentation
* Instance Segmentation
* Panoptic Segmentation
<br>
## Dataset
<br>The daset used in this repo is from [The Oxford-IIIT Pet Dataset](https://www.kaggle.com/datasets/julinmaloof/the-oxfordiiit-pet-dataset) . After being annnotated the image became a trimap image. Which is an image with 3 scaled value with respect to the object, boundaries, and background.
<br>
<img src="https://github.com/zigan/segmentation/assets/15936043/a1ac3571-a5c3-4451-94ca-00787c2ad992.type" width="50%" height="50%">
<br> The trimap image is used as the segmentation target.
<br>
## Convolution
<br> An image kernel is a small matrix used in machine learning for 'feature extraction', a technique for determining the most important portions of an image. The process known as convolution.
<br><img src="https://github.com/zigan/segmentation/assets/15936043/8eed8d17-989d-44fb-bd8e-4279999768d8.type" width="40%" height="40%">
<br>
## Depth-wise Separable Convolution
<br><img src="https://github.com/zigan/segmentation/assets/15936043/cb358010-4e9c-44b2-91f6-7085033d52ef.type" width="50%" height="50%">



