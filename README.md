The main text of the paper can be found at: [IML_project (1).pdf](IML_project%20(1).pdf)

A demo can be seen at [DEMO_vedio](https://www.bilibili.com/video/BV1oT4y147je/?spm_id_from=333.1387.homepage.video_card.click)

In recent years, real-time object detection has garnered significant attention due to
its wide range of applications, including in the gaming industry. This paper imple-
ments three algorithms, YOLOv7, SSD, and Faster R-CNN for real-time object
detection in the game Counter Strike 2. Due to the innovation of the application,
**we independently created the dataset of CSGO** the data set can be found on [dataset](https://huggingface.co/datasets/skpy/CS2/tree/main). 

Then, by combining these
algorithms, our proposed approach aims to achieve superior performance in detect-
ing various objects in real-time game play. We conducted extensive experiments to
compare the accuracy, speed, and overall performance. We innovatively proposed
numerous applications, for example, by real-time target distance calculation we
realize auto-aiming and for better accuracy, we combine the three output results,
using K-means,voting, and confidence to finally generate a better prediction.

![](1.png)
![](2.png)
![](3.png)
![](4.png)
![](5.png)
