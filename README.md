# GF1_WHU: GF-1 Cloud and Cloud Shadow Detection Validation Dataset

The Gaofen-1 cloud and cloud shadow detection validation dataset, termed GF1_WHU, was created by researchers at Wuhan University. It has been used for the performance evaluation of cloud detection methods (e.g., [the MFC algorithm](http://sendimage.whu.edu.cn/en/mfc/)) for Gaofen-1 WFV images, which have a 16-m spatial resolution and four multispectral bands spanning the visible to the near-infrared spectral regions. This collection of validation data includes 108 Level2A scenes collected from May 2013 to August 2016 from different global land-cover types under varying cloud conditions. All associated reference masks label both cloud and cloud shadow. 

The images are provided in .tar.gz format, and the masks in .tif format in which each DN value denotes:

|**Value**|**Class**|
| :-: | :-: |
|0|Nonvalue|
|1|Clear|
|128|Cloud Shadow|
|255|Cloud|

![image](https://raw.githubusercontent.com/dr-lizhiwei/GF1_WHU-GF-1-Cloud-and-Cloud-Shadow-Detection-Dataset/main/Fig.%201.%20Global%20distribution%20of%20the%20validation%20data.jpg)

Fig. 1. Global distribution of the validation data (base map credit: NASA Visible Earth).

![image](https://raw.githubusercontent.com/dr-lizhiwei/GF1_WHU-GF-1-Cloud-and-Cloud-Shadow-Detection-Dataset/main/Fig.%202.%20The%20histogram%20distribution%20of%20cloud%20and%20cloud%20shadow%20fractions%20across%20the%20validation%20images.jpg)

Fig. 2. The histogram distribution of cloud and cloud shadow fractions across the validation images.

The full GF1\_WHU dataset can be downloaded from [Baidu Disk](https://pan.baidu.com/s/19uc0k-kUIN5uC2AbETg1eA) (password: rbwb) or [Google Drive](https://drive.google.com/file/d/1iicE9SzCsxXX7l76Bje3N0T1UPq_orcC/view?usp=sharing). For any questions, contact <a href='https://zhiweili.net/'>Dr. Zhiwei Li</a> at <a href="mailto:dr.lizhiwei@gmail.com">dr.lizhiwei(AT)gmail.com</a>. This dataset is shared for academic purposes only. If you use the dataset, you should appropriately cite our paper:

**Li, Z., Shen, H., Li, H., Xia, G., Gamba, P., & Zhang, L. (2017). Multi-feature combined cloud and cloud shadow detection in GaoFen-1 wide field of view imagery. *Remote Sensing of Environment*, 191, 342-358.** ([PDF](http://sendimage.whu.edu.cn/wp-content/uploads/2017/02/2017_RSE_Multi-feature-combined-cloud-and-cloud-shadow-detection-in-GaoFen-1-wide-field-of-view-imagery.pdf))

