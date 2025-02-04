# Scrap_Steel_Image_Dataset
《An RGB-D-Based Thickness Feature Descriptor and Its Application on Scrap Steel Grading》
A Scrap Steel Image Dataset for Object Detection.

![1](https://github.com/zichengzichengzi/Scrap_Steel_Image_Dataset/assets/43312794/0d6198d5-1eb2-4aca-92cb-f45c8650a944)



The dataset consists of 3440 labeled images, 29 label categories and a total of 6081 samples. It is the voc data format. If you would like to download this dataset. Please download the data from the link below, details of which are given below：

Dataset download address: https://pan.baidu.com/s/1KEIkiFh8u4EU9DabQUkDgg?pwd=hwvq 
![image](https://github.com/zichengzichengzi/Scrap_Steel_Image_Dataset/assets/43312794/a111fab7-1741-4656-aac6-c0f79a2f1068)

<img src="https://github.com/zichengzichengzi/Scrap_Steel_Image_Dataset/assets/43312794/304e2fde-6ff0-45fa-9fdf-b8fdf0a83ab1" alt="微信截图_20230913082106" style="zoom:150%;" />



We also provide RGB D image data in folders, with each scene including point clouds, depth images, and color images.

download address:https://pan.baidu.com/s/1TqSpqO4Jt_dqwtCSoEA88A?pwd=vbia 
![微信截图_20230908211413](https://github.com/zichengzichengzi/Scrap_Steel_Image_Dataset/assets/43312794/3005ed93-f683-4301-9271-36bfefcf5f1e)

We provide the executables and dependencies of our algorithm. It is a thickness detection method based on an organised point cloud for scrap steel grading.

System Requirements:

```
ubuntu 18.04 or centos8
pcl = 1.11.1
```

The third-party linked libraries in LD_LIBRARY will be successfully searched and executed in the terminal:

```
export LD_LIBRARY_PATH=LD_LIBRARY{Path to LD_LIBRARY folder}:$LD_LIBRARY_PATH
```

Once the link library has been configured you can run the executable to detect the thickness with the command, the output is in output_hou

```
./project_feigang_hou {point cloud path}
```

The output results are two files, where output2d.txt is the detected thickness 2D coordinates and thickness values, and output_hou.txt is the output histogram result after statistics.

```
@ARTICLE{10299583,
  author={Gao, Zicheng and Lu, Hexiao and Lei, Jie and Zhao, Jingbo and Guo, Hao and Shi, Chengbing and Zhang, Yong},
  journal={IEEE Transactions on Instrumentation and Measurement}, 
  title={An RGB-D-Based Thickness Feature Descriptor and Its Application on Scrap Steel Grading}, 
  year={2023},
  volume={72},
  number={},
  pages={1-14},
  keywords={Steel;Feature extraction;Image edge detection;Three-dimensional displays;Point cloud compression;Computer vision;Task analysis;Edge detection;point cloud;RGB-D image;scrap steel grading;thickness feature descriptor},
  doi={10.1109/TIM.2023.3328089}}

```
