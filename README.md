# GF1_WHU: GF-1 Cloud and Cloud Shadow Detection Dataset

**Introduction**

The SENDIMAGE Lab. of Wuhan University released this validation datasets which includes 108 GF-1 Wide Field of View (WFV) level-2A scenes and its reference cloud and cloud shadow masks. The datasets were used for evaluating the performance of [the MFC algorithm](http://sendimage.whu.edu.cn/en/mfc/) which is proposed for cloud and cloud shadow detection in GF-1 WFV imagery. The globally distributed validation images were acquired from May 2013 to August 2016. The reference masks were obtained by manually drawing cloud/cloud shadow borders after visual inspection by experienced users.

The scenes are provided in .tar.gz format, and the masks in .tif fromat in which each DN value denotes:

|**Value**|**Class**|
| :-: | :-: |
|0|NoValue|
|1|Clear|
|128|Cloud Shadow|
|255|Cloud|

![image](https://raw.githubusercontent.com/dr-lizhiwei/GF1_WHU-GF-1-Cloud-and-Cloud-Shadow-Detection-Dataset/main/Fig.%201.%20Global%20distribution%20of%20the%20validation%20data.jpg)

Fig. 1. Global distribution of the validation data (base map credit: NASA Visible Earth).

![image](https://raw.githubusercontent.com/dr-lizhiwei/GF1_WHU-GF-1-Cloud-and-Cloud-Shadow-Detection-Dataset/main/Fig.%202.%20The%20histogram%20distribution%20of%20cloud%20and%20cloud%20shadow%20fractions%20across%20the%20validation%20images.jpg)

Fig. 2. The histogram distribution of cloud and cloud shadow fractions across the validation images.

The full GF1\_WHU dataset can be downloaded at [**Baidu Disk**](https://pan.baidu.com/s/19uc0k-kUIN5uC2AbETg1eA) (password: rbwb) or [**Google Drive**](https://drive.google.com/file/d/1iicE9SzCsxXX7l76Bje3N0T1UPq_orcC/view?usp=sharing). Any questions, contact Dr. Zhiwei Li at dr.lizhiwei(at)gmail.com. This dataset is shared for academic purpose only. If you use the dataset, you should appropriately cite our paper:

Li, Z., Shen, H., Li, H., Xia, G., Gamba, P., & Zhang, L. (2017). Multi-feature combined cloud and cloud shadow detection in GaoFen-1 wide field of view imagery. *Remote Sensing of Environment*, 191, 342-358. ([PDF](http://sendimage.whu.edu.cn/wp-content/uploads/2017/02/2017_RSE_Multi-feature-combined-cloud-and-cloud-shadow-detection-in-GaoFen-1-wide-field-of-view-imagery.pdf))

