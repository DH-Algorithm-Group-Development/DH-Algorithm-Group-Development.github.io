# AGD更新记录
## 2021年一季度版本
### 已完成

#### [新功能]交互绘制截面并切割点云-[王振鹏]
- 形式：HDevelop界面
- 模块：测量(3D)
- 功能：显示3D点云，使用鼠标绘制线段生成平面，返回该平面切割后的点云
- ![image](https://user-images.githubusercontent.com/47802547/124056195-de35a680-da57-11eb-8c04-327222f80d9e.png)
- ![image](https://user-images.githubusercontent.com/47802547/124056146-c5c58c00-da57-11eb-8863-fa57642a9ebb.png)

#### [新功能]区域外圈生成轮廓-[王振鹏]
- 形式：HDevelop脚本
- 模块：测量(2.5D)、
- 功能：生成区域外部紧邻像素构成的轮廓
- ![image](https://user-images.githubusercontent.com/47802547/124056323-0de4ae80-da58-11eb-83b7-ebceff97e7ec.png)
- ![image](https://user-images.githubusercontent.com/47802547/124056344-1937da00-da58-11eb-8cd3-1dce7f9a0445.png)

#### [新功能]路径计算和偏移-[王振鹏]
- 形式：HDevelop脚本
- 模块：机器人
- 功能：在XYZ图上绘制轮廓，并根据设置的位姿生成方式生成路径姿态，并且可以设置偏移方向来移动路径
- ![image](https://user-images.githubusercontent.com/47802547/124056390-3bc9f300-da58-11eb-8fc2-183c362ea76d.png)

#### [新功能]第三方库配置例程-[王振鹏]
- 形式：C++界面
- 模块：公共 
- 功能：基于CMake配置Halcon、QT、PCL、OpenCV、GoogleTest相关库的例程

#### [新功能]点云向柱面投影-[王振鹏]
- 形式：HDevelop脚本
- 模块：测量(3D)
- 功能：基于给定的柱面轴和半径，将侧面数据卷曲成圆柱或者将圆柱展开为侧面数据
- ![image](https://user-images.githubusercontent.com/47802547/124056527-7895ea00-da58-11eb-98ef-c99f9f750c56.png)
- ![image](https://user-images.githubusercontent.com/47802547/124056548-8186bb80-da58-11eb-800b-c8ccdc338c06.png)

#### [新功能]提取点云边缘-[王振鹏]
- 形式：HDevelop脚本
- 模块：测量(3D)
- 功能：基于设定的边缘角度提取点云边缘
- ![image](https://user-images.githubusercontent.com/47802547/124056585-96634f00-da58-11eb-80b3-1fa41841753d.png)

#### [新功能]在线引导例程-[王振鹏]
- 形式：HDevelop脚本
- 模块：机器人
- 功能：在线式引导例程，用于焊缝跟踪

#### [新功能]正向投影测量-[郭佼]
- 形式：HDevelop脚本
- 模块：预处理
- 功能：基于设定的参数将点云投影为XYZ图像
- ![image](https://user-images.githubusercontent.com/47802547/124056960-3e791800-da59-11eb-8562-2dd5fa3f1f69.png)
- ![image](https://user-images.githubusercontent.com/47802547/124056975-43d66280-da59-11eb-8168-c952af27dee4.png)

#### [新功能]点云图像填补-[郭佼]
- 形式：HDevelop脚本
- 模块：预处理
- 功能：基于设定的填补方式，对XYZ图数据缺失的部分进行数据修补
- ![image](https://user-images.githubusercontent.com/47802547/124057743-a4b26a80-da5a-11eb-99a8-3c99cf7fb00c.png)
- ![image](https://user-images.githubusercontent.com/47802547/124057961-0672d480-da5b-11eb-8981-cf6135998ed7.png)

## 2021年二季度版本
### 已完成

#### [新功能]简易激光三角法标定工具-[王振鹏]
- 形式：HDevelop界面
- 模块：相机标定
- 功能：可交互式的2D相机+线激光器配合Halcon标定板的激光三角测量标定工具
- ![image](https://user-images.githubusercontent.com/47802547/124058304-b5171500-da5b-11eb-8a1c-c03fd306b055.png)

#### [新功能]多相机标定工具-[王振鹏]
- 形式：HDevelop界面
- 模块：相机标定
- 功能：可交互式的多相机配合Halcon标定板的内外参标定工具

#### [新功能]机器人精度评估工具-[王振鹏]
- 形式：文档
- 模块：参数计算
- 功能：根据不同的方案类型，输入部分精度，生成机器人方案整体精度
- ![image](https://user-images.githubusercontent.com/47802547/124062055-a54eff00-da62-11eb-8d0d-4d781bac536d.png)

#### [新功能]点云自动配准工具-[郭佼]
- 形式：C++界面
- 模块：匹配
- 功能：界面式的点云配准工具，可以选择点云和设置匹配参数，并且导入和输出配准结果

### 进行中

#### [新功能]相机采图工具-[郭佼]
- 形式：C++界面
- 模块：采集演示
- 功能：针对常用3D相机进行界面设置和采集演示
- 状态：归属SVB开发序列，等待上游更新

#### [新功能]相机内参外参参数可视化设置工具-[王振鹏]
- 形式：C++界面
- 模块：参数计算
- 功能：界面式的3D相机视野相关参数可视化工具，可以导入常用相机配置文件和外部模型
- 状态：开发中

### 计划项
#### [新功能]点云去噪
- 形式：HDevelop脚本
- 模块：预处理
- 功能：基于测量需求对点云噪声进行去除

#### [新功能]生成拟合曲面
- 形式：HDevelop脚本
- 模块：测量(3d)
- 功能：针对选取的点云数据基于设定的曲面类型进行拟合，返回拟合参数和曲面数据


