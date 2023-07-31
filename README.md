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
![image](https://github.com/zigan/segmentation/assets/15936043/07eeb854-e7fc-48f4-bd1a-d728f11e5bd4|width=100px)
# Dataset
the daset used in this repo is The Oxford-IIIT Pet Dataset. After being annnotated the image became a trimap image. Which is an image with 3 scaled value with respect to the object, boundaries, and background
![image](https://github.com/zigan/segmentation/assets/15936043/a1ac3571-a5c3-4451-94ca-00787c2ad992|width=100px)
