# A-Benchmark-Dataset-for-Aircraft-Detection-in-Optical-Remote-Sensing-Imagery
A dataset named Aircraft Detection in Complex Optical Scene (ADCOS), which is obtained from multiple platform sources including Google Earth, Microsoft map, Worldview-3, Pleiades, Orbview-3, Jilin-1 and Ikonos satellites. 

## Dataset Description
The problem is that existing aircraft detection datasets rarely simultaneously consider the  diversity of target features and the complexity of environmental factors, which has become an important factor restricting the effectiveness and reliability of aircraft detection algorithms. Although a large amount of research has been devoted to breaking through few-sample-driven aircraft detection technology, most algorithms still struggle to effectively solve the problems of  missed target detection and false alarms caused by numerous environmental interferences in bird-eye optical remote sensing scenes. To further aircraft detection research, we have established a new dataset, Aircraft Detection in Complex Optical Scene (ADCOS), sourced from various platforms including Google Earth, Microsoft Map, Worldview-3, Pleiades, Ikonos, Orbview-3, and Jilin-1 satellites. It integrates 3903 meticulously chosen images of over 400 famous airports worldwide, containing 33,831 annotated instances employing the oriented bounding box (OBB) format. Notably, this dataset encompasses a wide range of various targets characteristics including multi-scale, multi-direction, multi-type, multi-state, and dense arrangement, along with complex relationships between targets and backgrounds like cluttered backgrounds, low contrast, shadows, and occlusion interference conditions. Furthermore, we evaluated nine representative detection algorithms on the ADCOS dataset, establishing a performance benchmark for subsequent algorithm optimization.

![image1-1](https://github.com/user-attachments/assets/e7f4d8d2-3a36-42c8-befb-7ff716a94068)
Figure 1 Building steps of the proposed dataset.

Table 1 Image source statistics of ADCOS dataset.
![图1](https://github.com/user-attachments/assets/73a60962-cd89-4215-b366-0b3789f21410)

![图2](https://github.com/user-attachments/assets/2f6be52b-30c3-4835-86e6-9945c2fc8c5a)

Figure 2 Typical scenes that reﬂect the complex relationship between targets and background. (a) Low-contrast issue. (b) Cluttered background interference. (c) Shadow issue. (d) Occlusion issue.

![image39](https://github.com/user-attachments/assets/5f00b176-ee81-4c06-93fe-46b71cf98827)
Figure 3 Experimental results of typical advanced detection methods: (a) Rotated faster R-CNN, (b) S2A-Net, (c) Oriented RepPoints, and (d) ground truth. It should be noted that green represents
ground truth, red represents algorithm prediction results, and yellow represents error detection.

Table 2 Evaluation results of all comparative algorithms.
![图3](https://github.com/user-attachments/assets/a07fa071-9879-44f1-b40d-d51a67e4083b)


## Dataset Download and Usage License
The dataset is available on the following links:

**Baidu Driver**: https://pan.baidu.com/s/1wrR9IihjmDujEkbCL3g4oQ (extraction password: nuui)

**Google Driver**: Coming soon.

Star this project and we will update the corresponding data consistently. **If you want use our dataset, please follows these rules:**

• Use of Google Earth images must respect the "Google Earth" terms of use.

• All images and their associated annotations in ADCOS can be used for academic purposes only, but any commercial use is prohibited.

## Citation 
If you need to use our dataset to make research, **please cite our essay (A Benchmark Dataset for Aircraft Detection in Optical Remote Sensing Imagery) (The essay is acceped and the link is below)**.
```
@article{hu2024benchmark,
  title={A Benchmark Dataset for Aircraft Detection in Optical Remote Sensing Imagery},
  author={Hu, Jianming and Zhi, Xiyang and Zhang, Bingxian and Shi, Tianjun and Cui, Qi and Sun, Xiaogang},
  journal={Remote Sensing},
  volume={16},
  number={24},
  pages={4699},
  year={2024},
  publisher={MDPI}
}
```
## Contact
If you have any problem or feedback in using SCCOS dataset, please contact me at hujianming@hit.edu.cn.
