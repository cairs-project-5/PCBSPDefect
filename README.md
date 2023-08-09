# PCBSPDefect and PCBMTL
## Project RP5.2, Integrity of Sensor Data
By Sik-Ho Tsang, Zhaoqing Suo, Tom Tak-Lam Chan, Huu-Thanh Nguyen, and Daniel Pak-Kong Lun

### Abstract
For increasing the reliability of the printed circuit board (PCB) manufacturing process, automated optical inspection is often employed for soldering defect detection. However, traditional approaches built on handcrafted features, pre-defined rules, or thresholds are often susceptible to the variation of the acquired images’ quality and give unstable performances. To solve this problem, a deep learning-based soldering defect detection method is developed in this paper. Like many real-life deep learning applications, the number of available training samples is often limited. This creates a challenging low-data scenario, as deep learning typically requires massive data to perform well. To address this issue, we propose a multi-task learning model, namely PCBMTL, that can simultaneously learn the classification and segmentation tasks under low-data regimes. By acquiring the segmentation knowledge, classification performance is substantially improved with few samples. The segmentation also allows the visualization of what the network has learned. To facilitate the study, a soldering defect image dataset, namely PCBSPDefect, is built. It focuses on the dual in-line packages (DIP) at the PCB back side (BDIP), DIP at the PCB front side (FDIP), and flat flexible cables (FFC). Experimental results show that the proposed PCBMTL outperforms the best existing approaches by over 5% to 17% of average accuracy for different datasets.

### PCBSPDefect Dataset
The PCBSPDefect dataset will be available once the paper is published.

### PCBMTL Approach
The PCBMTL Approach will be available once the paper is published.

### Citations
```
To be updated
```
