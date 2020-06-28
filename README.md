# William He 项目作品集

### Project 1: [基于成人背景特征进行年薪预测（数据挖掘项目）](https://github.com/hexiantao138/Tree-models-to-do-classification-for-adult-dataset)
* 数据集可以在此链接下载: [http://archive.ics.uci.edu/ml/datasets/Adult](http://archive.ics.uci.edu/ml/datasets/Adult)
* 项目描述：根据任意一个成人其背景包括：年龄，有无婚嫁，教育程度，职业，肤色，性别，工作时间，国籍等来预测年薪<=50k或>50k
* 数据挖掘二分类项目
* 工具：Python, Pandas, Matplotlib, Numpy, Seaborn, Scikit-learn 
* 模型选择：决策树，随机森林，逻辑回归
### Project 2: [猫狗图像自动识别（Kaggle竞赛项目）](https://github.com/hexiantao138/Dogs-vs-Cats-Kaggle)
* 数据集链接：[https://www.kaggle.com/c/dogs-vs-cats](https://www.kaggle.com/c/dogs-vs-cats)
* 项目描述：任意一张猫狗图像实现自动分类，正确率达90%
* 图像识别二分类项目
* 工具：Python, OpenCV
* 模型：卷积神经网络（CNN）
* 最终效果：
![](/project2.png)
### Project 3: [基于推特内容预测有无种族/性别歧视](https://github.com/hexiantao138/Text-classification-for-twitter)
* 训练集：[https://github.com/hexiantao138/Text-classification-for-twitter/blob/master/train.csv](https://github.com/hexiantao138/Text-classification-for-twitter/blob/master/train.csv)
* 测试集：[https://github.com/hexiantao138/Text-classification-for-twitter/blob/master/test.csv](https://github.com/hexiantao138/Text-classification-for-twitter/blob/master/test.csv)
* 项目描述：根据任意一段推特文字（英语）内容，可以自动判断其内容含义有无性别/种族歧视。
* 自然语言处理的二分类项目。
* 工具：nltk，Python
* 模型：朴素贝叶斯，逻辑回归，支持向量机。
* 类别分类为0/1，0代表无性别/种族歧视，1代表有性别/种族歧视。
* 后续：可以构建神经网络模型，效果更佳。
### Project 4: [基于黑白人体轮廓图像与特征点的互相自动识别](https://github.com/hexiantao138/Machine-learning-models-for-image-generation-and-key-points-detection)
* 数据集链接：[https://github.com/hexiantao138/Machine-learning-models-for-image-generation-and-key-points-detection](https://github.com/hexiantao138/Machine-learning-models-for-image-generation-and-key-points-detection)
* 项目描述：此项目可分为两大类：1.根据人体轮廓图自动识别特征点：肩点，腰点，臀点，足点，胯点。2.根据人体特征点自动画出人体轮廓。
* 图像数据识别与处理项目
* 工具：Python，scikit-learn, OpenCV, Matplotlib, Numpy, Pandas。
* 模型：决策树，逻辑回归，线性回归，卷积神经网络（CNN）。
* 注意：项目的预测效果高度依赖于数据集的无异常值，高质量程度。
* 最终效果：
![](/project3.png)
 
### Project 5: [一段连续视频中的指定物体追踪](https://github.com/hexiantao138/Lucas-Kanada-object-detection) 
* 计算机视觉项目
* 原数据链接：[https://github.com/hexiantao138/Lucas-Kanada-object-detection/blob/master/CarSequence.zip](https://github.com/hexiantao138/Lucas-Kanada-object-detection/blob/master/CarSequence.zip)
* 模板如下：
![](/car_template.jpg)
* 项目概述：将一段连续视频拆分为图片，识别每一张图片的模板照片，并以红框框起，最后输出为视频
* 工具：OpenCV, Python, （需要遍历文件夹中图片）
* 效果如下：
![](/Carsequencegif.gif)
