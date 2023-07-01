# data-labeling-tools
图像images/点云point clouds标注工具汇总


@[双愚](https://github.com/HuangCongQing) , 若fork或star请注明来源

![yuque_diagram (1)](https://github.com/HuangCongQing/awesome-data-labeling-tools/assets/20675770/22a86a93-1d7a-43ab-bc0f-6e1b2b3a5853)



自动驾驶相关交流群，欢迎扫码加入：[自动驾驶感知(PCL/ROS+DL)：技术交流群汇总(新版)](https://mp.weixin.qq.com/s?__biz=MzI4OTY1MjA3Mg==&mid=2247486575&idx=1&sn=3145b7a5e9dda45595e1b51aa7e45171&chksm=ec2aa068db5d297efec6ba982d6a73d2170ef09a01130b7f44819b01de46b30f13644347dbf2#rd)


## 图像标注开源工具
1. labelme(常用)

对图像进行多边形，矩形，圆形，多段线，线段，点形式的标注（可用于目标检测，图像分割，等任务）。
对图像进行进行 flag 形式的标注（可用于图像分类 和 清理 任务）。
视频标注
生成 VOC 格式的数据集（for semantic / instance segmentation）
生成 COCO 格式的数据集（for instance segmentation）

2. LabelImg

教程：
● https://zhuanlan.zhihu.com/p/550021453
● https://blog.csdn.net/knighthood2001/article/details/125883343

## 点云标注开源工具


#### 1.PCAT 只显示点云,可以标注目标以及道路边界点,生成.txt文件.(常用)
* 链接:https://github.com/halostorm/PCAT_open_source

#### 2.supeivise 在线标注,只能标注目标,很准确,生成.json文件
* 链接:https://supervise.ly/lidar-3d-cloud

#### 3.L-CAS  只显示点云,只能标注目标
* 链接: https://github.com/yzrobot/cloud_annotation_tool/tree/devel


#### 4.LATTE  显示图像以及点云,但是只是标注点云2D的目标边界框并生成对应图像的语义分割信息.
* 链接: https://github.com/bernwang/latte

#### 5.semantic-segmentation-editor 点云语义分割标注工具
* 链接: https://github.com/MR-520DAI/semantic-segmentation-editor

#### 6.Point-Cloud-Annotation-Tool(常用)

用于在点云中注释3D框的工具。支持KITTI-bin格式的点云。注释格式与Applo 3D格式相同。数据示例可在[此处](http://data.apollo.auto/help?name=data_intro_3d&data_key=lidar_obstacle_label&data_type=0&locale=en-us&lang=en)找到。

* github链接: https://github.com/springzfx/point-cloud-annotation-tool


安装：https://blog.csdn.net/r1141207831/article/details/103881962
* 运行系统：Ubuntu16.04
* 运行环境：ROS Kinetic
* 依赖库：pcl 1.8, vtk 8.1, Qt5

Docs: https://www.yuque.com/huangzhongqing/hre6tf/qaauez?singleDoc# 《【det】point_cloud_annotation_tool》


#### 7. ch-sa/labelCloud 点云目标检测标注
标注工具：https://github.com/ch-sa/labelCloud

#### 8. xtreme1

https://github.com/xtreme1-io/xtreme1

Xtreme1 unlocks deep insights into data annotation, curation and ontology management for tackling machine learning challenges in computer vision and LLM. The platform's AI-fueled tools elevate your annotation game to the next level of efficiency, powering your projects in 2D/3D Object Detection, 3D Instance Segmentation and LiDAR-Camera Fusion like never before.


![image](https://github.com/HuangCongQing/awesome-data-labeling-tools/assets/84139543/88603dc5-7f49-4eae-9008-c16adea146df)


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

