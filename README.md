# Entry_problems
# 任务一：半月集分类

分类前半月集数据如图所示：
![image](./pictures/half_moon_undivided.png)

分类后结果：

​	![image](./pictures/half_moon_boundary.png)

# 任务二：基于numpy的mnist图像分类

训练过程中准确率与损失函数图像：

![image](./pictures/mnist_np.png)

测试集测试结果：

![image](./pictures/mnist_np_accuracy.png)

# 任务三：基于pytorch的mnist图像分类

分别采用lenet、vgg、resnet-18以及vit测试其在mnist数据集上的准确度，训练过程对比图如下所示：

![image](./pictures/legend.png)

![image](./pictures/mnist_pytorch_accuracy.png)

![image](./pictures/mnist_pytorch_loss.png)

vit结果如下所示：

![image](./pictures/mnist_vit.png)

测试集测试结果：

|   模型    | 准确率 |
| :-------: | :----: |
|   lenet   | 98.5%  |
| resnet-18 | 98.6%  |
|    VGG    | 98.7%  |
|    VIT    | 97.67% |


