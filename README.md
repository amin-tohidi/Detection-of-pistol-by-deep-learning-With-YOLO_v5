# Detection-of-lumbar-weapon-pistol-by-deep-learning--With-YOLO-v5

paper :  http://pitc.jrl.police.ir/article_97719.html

download paper (1.43 MB ) :  http://pitc.jrl.police.ir/article_97719_3a0097328657fd607c204852d7361296.pdf

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



# Reference

[1] S. Sastry Kunapuli, P. Chakravarthy Bh, and U. Singh, “Designing and Implementing a Real Time Weapons Detection System on ODROID-XU4,” 2018 IEEE Int. WIE Conf. Electr. Comput. Eng. WIECON-ECE 2018, pp. 137–140, 2018, doi: 10.1109/WIECON-ECE.2018.8783187.

[2] Jain, A. Vikram, Mohana, A. Kashyap, and A. Jain, “Weapon Detection using Artificial Intelligence and Deep Learning for Security Applications,” Proc. Int. Conf. Electron. Sustain. Commun. Syst. ICESC 2020, no. Icesc, pp.3–198, 2020, doi: 10.1109/ICESC48915.2020.9155832.

[3] Liu et al., “SSD: Single shot multibox detector,” Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics), vol. 9905 LNCS, pp. 21–37, 2016, doi: 10.1007/978-3-319-46448-0_2.

[4] Ren, K. He, R. Girshick, and J. Sun, “Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks,” IEEE Trans. Pattern Anal. Mach. Intell., vol. 39, no. 6, pp. 1137–1149, 2017, doi: 10.1109/TPAMI.2016.2577031.

[5] S. S. Hashmi, N. U. Haq, M. M. Fraz, and M. Shahzad, “Application of Deep Learning for Weapons Detection in Surveillance Videos,” 2021 Int. Conf. Digit. Futur. Transform. Technol. ICoDT2 2021, May 2021, doi: 10.1109/ICODT252288.2021.9441523.

[6] Redmon and A. Farhadi, “YOLOv3: An Incremental Improvement,” Apr. 2018, Accessed: Aug. 14, 2021. [Online]. Available: http://arxiv.org/abs/1804.02767.

[7] Bochkovskiy, C.-Y. Wang, and H.-Y. M. Liao, “YOLOv4: Optimal Speed and Accuracy of Object Detection,” Apr. 2020, Accessed: Aug. 14, 2021. [Online]. Available: 
http://arxiv.org/abs/2004.10934.

[8] T. Bhatti, M. G. Khan, M. Aslam, and M. J. Fiaz, “Weapon Detection in Real-Time CCTV Videos Using Deep Learning,” IEEE Access, vol. 9, pp. 34366–34382, 2021, doi: 10.1109/ACCESS.2021.3059170.

[9] Simonyan and A. Zisserman, “Very deep convolutional networks for large-scale image recognition,” 3rd Int. Conf. Learn. Represent. ICLR 2015 - Conf. Track Proc., 2015.

[10] Szegedy, V. Vanhoucke, S. Ioffe, J. Shlens, and Z. Wojna, “Rethinking the Inception Architecture for Computer Vision,” Proc. IEEE Comput. Soc. Conf. Comput. Vis. Pattern Recognit., vol. 2016-Decem, pp. 2818–2826, 2016, doi: 10.1109/CVPR.2016.308.

[11] Szegedy, S. Ioffe, V. Vanhoucke, and A. A. Alemi, “Inception-v4, inception-ResNet and the impact of residual connections on learning,” 31st AAAI Conf. Artif. Intell. AAAI 2017, pp. 4278–4284, 2017.

[12] G. Howard et al., “MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications,” Apr. 2017, Accessed: Aug. 14, 2021. [Online]. Available: http://arxiv.org/abs/1704.04861.

[13] Narejo, S., Pandey, B., Rodriguez, C., & Anjum, M. R “IoT Based Weapons Detection System for Surveillance and Security Using YOLOV4 | IEEE Conference Publication | IEEE Xplore.” https://ieeexplore.ieee.org/document/9489224 (accessed Aug. 14, 2021).

[14] Karakaya, I. Safak, O. Gztilrk, M. Bal, and Y. E. Esin, “Gun Detection with Faster R-CNN in X-Ray Images,” 2020 28th Signal Process. Commun. Appl. Conf. SIU 2020 - Proc., Oct. 2020, doi: 10.1109/SIU49456.2020.9302457.

[14] Liu et al., “Deep Learning for Generic Object Detection : A Survey,” Int. J. Comput. Vis., vol. 128, no. 2, pp. 261–318, 2020, doi: 10.1007/s11263-019-01247-4.

[15] Deng, W. Dong, R. Socher, L. Li, K. Li, and L. Fei-fei, “ImageNet : A Large-Scale Hierarchical Image Database,” pp. 248–255, 2009.

[16] Y. Lin et al., “Microsoft COCO: Common objects in context,” Lect. Notes Comput. Sci. (including Subser. Lect. Notes Artif. Intell. Lect. Notes Bioinformatics), vol. 8693 LNCS, no. PART 5, pp. 740–755, 2014, doi: 10.1007/978-3-319-10602-1_48.

[17] Kuznetsova et al., “The Open Images Dataset V4: Unified Image Classification, Object Detection, and Visual Relationship Detection at Scale,” Int. J. Comput. Vis., vol. 128, no. 7, pp. 1956–1981, 2020, doi: 10.1007/s11263-020-01316-z.

[18] Russakovsky et al., “ImageNet Large Scale Visual Recognition Challenge,” Int. J. Comput. Vis., vol. 115, no. 3, pp. 211–252, 2015, doi: 10.1007/s11263-015-0816-y.

[19] Girshick, J. Donahue, T. Darrell, and J. Malik, “Rich feature hierarchies for accurate object detection and semantic segmentation,” Proc. IEEE Comput. Soc. Conf. Comput. Vis. Pattern Recognit., pp. 580–587, 2014, doi: 10.1109/CVPR.2014.81.

[20] Redmon, S. Divvala, R. Girshick, and A. Farhadi, “You only look once: Unified, real-time object detection,” Proc. IEEE Comput. Soc. Conf. Comput. Vis. Pattern Recognit., vol. 2016-Decem, pp. 779–788, 2016, doi: 10.1109/CVPR.2016.91.

[21] Krizhevsky and G. E. Hinton, “ImageNet Classification with Deep Convolutional Neural Networks,” pp. 1–9.

[22] Huang, Z. Liu, L. Van Der Maaten, and K. Q. Weinberger, “Densely connected convolutional networks,” Proc. - 30th IEEE Conf. Comput. Vis. Pattern Recognition, CVPR 2017, vol. 2017-January, pp. 2261–2269, 2017, doi: 10.1109/CVPR.2017.243.

[23] He, X. Zhang, S. Ren, and J. Sun, “Deep residual learning for image recognition,” Proc. IEEE Comput. Soc. Conf. Comput. Vis. Pattern Recognit., vol. 2016-December, pp. 770–778, 2016, doi: 10.1109/CVPR.2016.90.

[24] Li, T. Lai, S. Wang, Q. Chen, C. Yang, and R. Chen, “Weighted feature pyramid networks for object detection,” Proc. - 2019 IEEE Intl Conf Parallel Distrib. Process. with Appl. Big Data Cloud Comput. Sustain. Comput. Commun. Soc. Comput. Networking, ISPA/BDCloud/SustainCom/SocialCom 2019, pp. 1500–1504, 2019, doi: 10.1109/ISPA-BDCloud-SustainCom-SocialCom48970.2019.00217.

[25] Liu, L. Qi, H. Qin, J. Shi, and J. Jia, “Path Aggregation Network for Instance Segmentation,” Proc. IEEE Comput. Soc. Conf. Comput. Vis. Pattern Recognit., pp. 8759–8768, 2018, doi: 10.1109/CVPR.2018.00913.

[26] Tan, R. Pang, and Q. V. Le, “EfficientDet: Scalable and efficient object detection,” Proc. IEEE Comput. Soc. Conf. Comput. Vis. Pattern Recognit., pp. 10778–10787, 2020, doi: 10.1109/CVPR42600.2020.01079.

[27] “Labelimg.” https://github.com/tzutalin/labelImg.

[28] “Google Colab,” www.google.com, 1977. https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index#recent=true
