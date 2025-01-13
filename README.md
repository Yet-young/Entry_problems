# Entry_problems
# 任务一：半月集分类

分类前半月集数据如图所示：
![image](./pictures/half_moon_undivided.png)

分类后结果：

​	![](D:\jupyter\Entry_problems\Half_moon\half_moon_boundary.png)

# 任务二：基于numpy的mnist图像分类

训练过程中准确率与损失函数图像：

![image-20250113094644216](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113094644216.png)

测试集测试结果：

![image-20250113094741629](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113094741629.png)

# 任务三：基于pytorch的mnist图像分类

分别采用lenet、vgg、resnet-18以及vit测试其在mnist数据集上的准确度，训练过程对比图如下所示：

![image-20250113101619441](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113101619441.png)

![image-20250113101532393](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113101532393.png)

![image-20250113101701675](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113101701675.png)

vit结果如下所示：

![image-20250113103609267](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113103609267.png)

测试集测试结果：

|   模型    | 准确率 |
| :-------: | :----: |
|   lenet   | 98.5%  |
| resnet-18 | 98.6%  |
|    VGG    | 98.7%  |
|    VIT    | 97.67% |

# 任务四：Tiny-VOC图像分类

首先将Annotations中的图像标注转化为模型可处理的迭代器，再分别测试任务三中的四种模型在VOC上的准确度，下面是训练过程中对比图：

![image-20250113104957391](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113104957391.png)

![image-20250113105012202](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113105012202.png)

![image-20250113105030757](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113105030757.png)

vit结果如下所示：

![image-20250113105603257](C:\Users\Yet Young\AppData\Roaming\Typora\typora-user-images\image-20250113105603257.png)

测试集测试结果：

|   模型    | 准确率 |
| :-------: | :----: |
|   lenet   |  96%   |
| resnet-18 | 97.9%  |
|    VGG    | 98.1%  |
|    VIT    | 97.28% |
