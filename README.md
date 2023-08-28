# neepuEYE dataset
## Brief description
This is an image dataset named neepuEye dataset which contains some low-resolution near-infrared images that were captured under laboratory conditions. 
This dataset was splitted into two subsets: training subset and test subset. 

The training subset contains around 5500 images of 109 subjects.The training images are suitable for generating  samples that can be used to train an eye detector.

The test subset contains around 1300 images and 2300 eyes which are augmented data from 224 original images of 11 subjects. The test images can be used to validate an eye detector or a pupil localizer.
## Example images from the training subset 
|![Alt text](/Images/train/1/133_15.jpg)| ![Alt text](/Images/train/1/133_8_2.jpg)| ![Alt text](/Images/train/1/133_25.jpg)| ![Alt text](/Images/train/1/133_26_2.jpg)| ![Alt text](/Images/train/1/133_38.jpg)|
|    :---:    | :---:      | :---:      | :---:      | :---:      |
|![Alt text](/Images/train/2/136_1.jpg)| ![Alt text](/Images/train/2/136_13.jpg)| ![Alt text](/Images/train/2/136_7_2.jpg)| ![Alt text](/Images/train/2/136_37.jpg)| ![Alt text](/Images/train/2/136_37_2.jpg)|
|![Alt text](/Images/train/3/651_1_2.jpg)| ![Alt text](/Images/train/3/651_3_2.jpg)| ![Alt text](/Images/train/3/651_1.jpg)| ![Alt text](/Images/train/3/651_2.jpg)| ![Alt text](/Images/train/3/651_11.jpg)|
## Example images from the test subset
|![Alt text](/Images/test/1/905_5_orig.jpg)| ![Alt text](/Images/test/1/905_5_orig_flip.jpg)| ![Alt text](/Images/test/1/905_5_rotate.jpg)| ![Alt text](/Images/test/1/905_6_rotate.jpg)| ![Alt text](/Images/test/1/905_4_rotate_blur.jpg)|
|    :---:    | :---:      | :---:      | :---:      | :---:      |
|![Alt text](/Images/test/2/915_1_orig.jpg)| ![Alt text](/Images/test/2/915_1_orig_flip.jpg)| ![Alt text](/Images/test/2/915_1_rotate.jpg)| ![Alt text](/Images/test/2/915_1_rotate_blur_flip.jpg)| ![Alt text](/Images/test/2/915_2_rotate_blur.jpg)|
## Download our dataset
Baidu[[baidu]](https://pan.baidu.com/s/1WjVxmZpmuyMWtR4aH5v2nQ)
(pwd: av23)

Microsoft OneDrive[[OneDrive]](https://1drv.ms/u/s!AtAOkdZV4tWGiFqCzVUhGeiOiWS9)

## Citation
Please cite as:

Jie-chun Chen, Pin-qing Yu, Chun-ying Yao, Li-ping Zhao, Yu-yang Qiao,

Eye detection and coarse localization of pupil for video-based eye tracking systems,

Expert Systems with Applications,

2023,

121316,

ISSN 0957-4174,

https://doi.org/10.1016/j.eswa.2023.121316.

(https://www.sciencedirect.com/science/article/pii/S0957417423018183)

Abstract: A video-based eye tracking system generally captures NIR images, each of which contains one or two eyes of a subject. The subject’s point of gaze is then determined using 3D eye model and pupil centre corneal reflection technique. Eye detection and pupil localization play significant roles in video-based eye tracking systems. However, face rotation, wearing glasses, eye-shape variation and illumination variation make it difficult to detect an eye and localize a pupil accurately in the images captured by video-based eye tracking systems. In this paper, we proposed an eye detector that adopts a coarse-to-fine strategy. The eye detector consists of three classifiers: an ATLBP-THACs feature-based cascade classifier, a branch CNN and a multi-task CNN. We also proposed a method for coarse pupil localization. Coarse localization is an important step for pupil localization since it can provide initial pupil coordinates for a fine pupil localization method. Given a downscaled eye image, a shallow CNN is used to estimate the location of seven landmarks. On this basis, pupil center and radius are estimated. A method for small dim target enhancement is used to increase the contrast between pupil and background. The main goal of pupil enhancement is to make it easier to binarize an eye image. At last, component filtering is made by utilizing the estimated pupil center and radius. We collected a dataset named neepuEYE dataset that consists of 5500 NIR eye images from 109 people. The images can be used to generate augmented samples for training an eye detector since they contain eyes with different shape, orientation and pupil localization. Experimental results show that our eye detector is a fast and robust detector. Furthermore, our method for coarse pupil localization can obtain not only high detection rate but also high localization speed.

Keywords: eye detection; pupil localization; eye tracking; gaze tracking; NIR

## Contact with us
<pre><code>Email: chenjiechun@neepu.edu.cn</code></pre>
