# Detection-of-lumbar-weapon-pistol-by-deep-learning--With-YOLO-v5

In this project, with the help of a personal dataset called Pashtaw, we have created a lumbar weapon detection system through surveillance cameras to identify armed individuals to increase the security of public places such as airports, banks, jewelry stores, etc.

Our weapon detection system, due to the quality of the Pashtaw dataset, was able to detect small arms with an accuracy of %99/51 on validation data.


# Result Train YOLO_v5 on my gun dataset (PASHTAW)

https://user-images.githubusercontent.com/76064876/139333114-9f4fdc4d-c05c-4715-b399-eb1deb5c0acd.mp4

# YOLO_v5

The network we used in this project was the YOLO_v5 neural network, which, as it is clear from the code, we used two small and X-large YOLO_v5 network architectures.
The small network has less accuracy, but instead performs the detection operation faster, but on the other hand, the X-large network, due to the large number of training parameters, detects the weapon more accurately but in more time.
