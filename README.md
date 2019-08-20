# Auto-Cropping: Demonstrating how can we use Segmentation to automate copping 

Background removal is a task that is quite easy to do manually, or semi manually (Photoshop, and even Power Point has such tools) if you use some kind of a “marker” and edge detection. However, fully automated background removal is quite a challenging task.So i was quite inspired by this [idea](https://towardsdatascience.com/background-removal-with-deep-learning-c4f2104b3157).So I thought to work with this in a **Secure and private AI** project showcase challenge.

I used several techniques to perform and segmentation but with Mask-RCNN pretrained model I was not able to get a proper segementation.
<p align="center">
    <img src="g3doc/img/mask_rcnn.png" width=600></br>
</p>

Finally i studied about DeepLab is a state-of-art deep learning model for semantic image segmentaion it help me achieving my desired results for Demo.

<p align="center">
    <img src="g3doc/img/vis1.png" width=600></br>
    <img src="g3doc/img/vis2.png" width=600></br>
    <img src="g3doc/img/vis3.png" width=600></br>
</p>

