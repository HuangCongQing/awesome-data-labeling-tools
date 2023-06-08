# data-labeling-tools
图像images/点云point clouds标注工具汇总


@[双愚](https://github.com/HuangCongQing) , 若fork或star请注明来源


## 图像标注开源工具
1. labelme


## 点云标注开源工具


#### 1.PCAT 只显示点云,可以标注目标以及道路边界点,生成.txt文件.
* 链接:https://github.com/halostorm/PCAT_open_source

#### 2.supeivise 在线标注,只能标注目标,很准确,生成.json文件
* 链接:https://supervise.ly/lidar-3d-cloud

#### 3.L-CAS  只显示点云,只能标注目标
* 链接: https://github.com/yzrobot/cloud_annotation_tool/tree/devel


#### 4.LATTE  显示图像以及点云,但是只是标注点云2D的目标边界框并生成对应图像的语义分割信息.
* 链接: https://github.com/bernwang/latte

#### 5.semantic-segmentation-editor 点云语义分割标注工具
* 链接: https://github.com/MR-520DAI/semantic-segmentation-editor

#### 6.Point-Cloud-Annotation-Tool

用于在点云中注释3D框的工具。支持KITTI-bin格式的点云。注释格式与Applo 3D格式相同。数据示例可在[此处](http://data.apollo.auto/help?name=data_intro_3d&data_key=lidar_obstacle_label&data_type=0&locale=en-us&lang=en)找到。

* github链接: https://github.com/springzfx/point-cloud-annotation-tool


安装：https://blog.csdn.net/r1141207831/article/details/103881962
  运行系统：Ubuntu16.04
  运行环境：ROS Kinetic
  依赖库：pcl 1.8, vtk 8.1, Qt5


#### 7. ch-sa/labelCloud 点云目标检测标注
标注工具：https://github.com/ch-sa/labelCloud


#### 8. CloudCompare

标注教程：[三维点云——数据标注_Dujing2019的博客-CSDN博客_点云](https://blog.csdn.net/Dujing2019/article/details/104068721)



## 点云标注的供应商:
1.NIuXie
* 链接:http://www.newlshare.com/adas.html


2.倍赛
* 链接:https://www.basicfinder.com/services/label/


3.playment
* 链接: https://playment.io/



## License

Copyright (c) [双愚](https://github.com/HuangCongQing/data-labeling-tools). All rights reserved.

Licensed under the [MIT](./LICENSE) License.

