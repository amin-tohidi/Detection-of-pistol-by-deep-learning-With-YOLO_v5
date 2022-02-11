# Detection-of-lumbar-weapon-pistol-by-deep-learning--With-YOLO-v5

paper :  http://pitc.jrl.police.ir/article_97719.html

ddownload paper (1.43 MB ) :  http://pitc.jrl.police.ir/article_97719_3a0097328657fd607c204852d7361296.pdf

In this project, with the help of a personal dataset called Pashtaw, we have created a lumbar weapon detection system through surveillance cameras to identify armed individuals to increase the security of public places such as airports, banks, jewelry stores, etc.

Our weapon detection system, due to the quality of the Pashtaw dataset, was able to detect small arms with an accuracy of %99/51 on validation data.


# Result Train YOLO_v5 on my gun dataset (PASHTAW)

https://user-images.githubusercontent.com/76064876/139333114-9f4fdc4d-c05c-4715-b399-eb1deb5c0acd.mp4

# YOLO_v5

The network we used in this project was the YOLO_v5 neural network, which, as it is clear from the code, we used two small and X-large YOLO_v5 network architectures.
The small network has less accuracy, but instead performs the detection operation faster, but on the other hand, the X-large network, due to the large number of training parameters, detects the weapon more accurately but in more time.

# Dataset  (Pashtaw)

To teach the YOLO network, we used a personal database called Pashto, which contains about 2,000 images of labeled pistols. In making this database, the issue of keeping the weapon away from CCTV cameras was considered.
In the image below, you can see examples of dataset images

![112](https://user-images.githubusercontent.com/76064876/139485790-3aba94ba-7347-4afb-8e14-8c682d40732b.JPG)

<b>Among the datasets, 1,500 were used for training and 500 for system evaluation. </b>

# Paper 

download paper (1.43 MB ) :  http://pitc.jrl.police.ir/article_97719_3a0097328657fd607c204852d7361296.pdf

Undoubtedly, the issue of increasing security in public places has always been the focus of researchers and relevant officials. Significant measures have been taken to increase security in places such as the metro, the airport and places of pilgrimage, including inspection systems, the installation of surveillance cameras and the deployment of an officer. But all of the above is done by human resources, which factors such as fatigue, distraction and many other factors affect the quality of monitoring. One of the security measures is carrying a weapon and pulling a gun. The solution presented in this article is to use deep learning algorithms in the form of weapons detection in surveillance cameras. In addition to monitoring public places, the proposed system can provide as much security as possible. Banks, goldsmiths, chain stores, and the like help As armed robbers prevent employees from informing the police, the automatic weapons detection system quickly contacts security officers if it detects a weapon. And provides information. In this study, two large and small versions of the YOLO_v5 deep neural network were used to detect the lumbar weapon. And the performance of these networks was compared with each other. Finally, the proposed system of automatic detection of pistols after training with the Pishtaw data set performs the detection operation of the pistol with 99.01% accuracy.


# Contact us 
amin.tohidifar@gmail.com

