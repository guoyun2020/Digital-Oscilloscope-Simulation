# 一款基于Qt与OpenCV的仿真数字示波器
吉林大学信息工程专业大四上学期《综合实验（软件部分）》实验内容，个人提出的一种解决方案。 
## 思路 
### 下位机 
使用单片机AD转换采集原始数据，通过串口调试助手将数据保存为本地txt。 
### 上位机
使用Qt与OpenCV完成数据可视化界面，读取本地txt数据并实时绘制。 
## 效果
![avatar](/image/img2.png)   
![avatar](/image/img1.png)    
![avatar](/image/img3.jpg)    
## 进度
10.13  STM32 ADC单路电压采集、数据本地保存与读取、串口数据可视化。  
10.12  界面搭建、数据可视化（使用MATLAB生成正弦波测试）。
## Requirements
opencv_python==4.5.3.56  
numpy==1.19.3  
scipy==1.2.1  
PyQt5==5.15.4  


