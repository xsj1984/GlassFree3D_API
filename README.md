# GlassFree3D_API

使用WebGPU实现裸眼三维3D的展示

webGPU的运行效率高于OGL3.0，低于vulkan和DX12。

在windows版的chrome浏览器下运行效率和potplayer相一致，无卡顿。（需完善测试数据）

需要一个演示的网址：https://demo.cgt3d.cn（建设中）

## 研发计划

1.实现web版的裸眼3D播放器，直接加载网络视频，进行裸眼3D的播放（2025年7月25日之前）

2.实现2D视频转裸眼3D视频的功能

3.实现视频生成裸眼3D图片的功能

## 相关资料

### 相关开源项目或商用软件
1.Lookingglass开源裸眼3D代码(目前只能适配lookingglass的设备)：https://github.com/Looking-Glass
 
2.臻像科技光场插件：https://imagetru3d.com/software

3.3D通软件： https://www.3dvstar.com/3dList.html

### 裸眼3D编码原理

* Image preparation for 3D LCD   https://kdocs.cn/l/cnj16hHtex8S
 

### 单视图生成多视角视图的论文
1.VistaDream 论文：https://arxiv.org/abs/2410.16892  代码：https://github.com/WHU-USI3DV/VistaDream

### 深度图的获取
1.苹果单视图深度图的获取 https://github.com/apple/ml-depth-pro

### nerf gs数据集的获取
1.blender NERF 

项目定位：一个在 Blender 中创建合成 NeRF 和高斯溅射数据集的工具，旨在让用户能够轻松、快速地获取渲染图和相机参数。

### 人像三维化

https://repo-sam.inria.fr/fungraph/freestylegan/


## 裸眼3D硬件的生产厂家
1. 臻像科技  https://imagetru3d.com/
   
2. 北京天马辉电子技术有限责任公司 http://www.tmhjt.com/
   
3. 上海易维视：http://www.evistek.com/



## 裸眼3D的科研单位
1.北京邮电大学桑新柱教授团队

2.北京航空航天大学王琼华教授团队

3.

## 裸眼3D的内容生产商

需核实：https://zhuanlan.zhihu.com/p/8740945067


## 光栅设计与加工
