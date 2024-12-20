## Hi there 👋
这是我的代码存储仓库， [pc的个人介绍](https://pengshi12138.github.io)

# 图像数据输入命名规范
+ 干扰组文件夹命名名称 `{Metadata_cell}-{Metadata_treatment}-{Metadata_hour}` ，分别表示细胞系、实验组干扰、实验时间。
+ 在干扰组文件夹下，按照数字组成不同视野的图像集，名称为 `{Metadata_site}` ，值必须为整数数字类型。
+ 在不同视野的图像集下，可以存在不同类型的图像，可以是
  - `DD、DA、AA` FRET三通道图像
  - `Mit` 线粒体图像
  - `BF_1` 明场图像，后面数字表示可以拍摄多张图像
  - `Hoechst` 细胞核图像

**图像的存储格式都为tif格式，16位的图像数据**

# 1. 基于CellProfiler的传统机器学习分析明场(BF)以及荧光图像(FI)算法程序
项目存放于[CellProfiler-ML-Model](https://github.com/College-of-Biophotonics-SCNU/CellProfiler-ML-Model)

# 2. 基于深度学习模型分析FRET与高内涵图像
## 没写，懒了
项目存放于[FRET-MHCS-CNN](https://github.com/College-of-Biophotonics-SCNU/FRET-MHCS-CNN)
# 3. 基于FRET双杂交计算的FRET特征提取以及分析程序
项目存放于[FRET-two-hybrid-processing-algorithm](https://github.com/College-of-Biophotonics-SCNU/FRET-two-hybrid-processing-algorithm)
## 3.1 基于python numpy框架的cpu运算程序
## 3.2 基于pytorch gpu运算程序
## 3.3 基于Ed图像的特征提取程序
## 3.4 基于Ed效率特征以及表型特征的分析程序
### 3.3.1 与细胞器荧光图像的关系
### 3.3.2 与细胞明场图像的关系
### 3.3.3 与FRET蛋白共定位之间的关系
### 3.3.4 特征融合

# 4. 基于Cellpose和CellProfiler对于FRET三通道图像的分割以及明场图像分析程序
项目存放于[CellposeSegmentationAnglysisModel](https://github.com/College-of-Biophotonics-SCNU/CellposeSegmentationAnglysisModel)
## 4.1 Cellpose对于FRET三通道进行单细胞分割模型
## 4.2 基于CellProfiler对于明场图像的特征提取程序
## 4.2 基于PCA算法对于明场特征分析模型

# 5. 基于Cellpose和CellProfiler对于亚细胞器分割以及特征提取程序
项目存放于[CellposeSubcellularModel](https://github.com/College-of-Biophotonics-SCNU/CellposeSubcellularModel)
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
