## 项目介绍
小组成员基于数据集tnews_public，分别采用了fasttext，textrcnn，dpcnn，bert等多种模型来实现文本分类，并与所给的textcnn模型进行对比。
我所负责的是dpcnn部分，其他模型详见小组其他成员的代码。

## 环境
python 3.7 
sklearn 0.21.2 
tensorboardX 2.0 
torch 1.1.0
torchvision 0.3.0  

## 训练并测试：
python run.py --model DPCNN

## 参数
模型都在models目录下，超参定义和模型定义在同一文件中。  

## 参考文献
[1]Deep pyramid convolutional neural networks for text categorization. JOHNSON R,ZHANG T. Proceedings of the55th Annual Meeting of the Association for Computational Linguistics.2017
[2]基于语义的中文文本预处理研究[D]. 张宁.西安电子科技大学 2011
[3]一种文本分类方法和装置[P]. 宋时雨. 中国专利:CN107609160B, 2020-02-21
[4]文本分类中支持向量机研究[J]. 何焱.  河南科技. 2019(29)
[5]全卷积神经网络的字符级文本分类方法[J]. 张曼,夏战国,刘兵,周勇.  计算机工程与应用. 2020(05)
[6]基于字词混合向量的CNN-LSTM短文本分类[J]. 张默涵.  信息技术与信息化. 2019(01)
[7]基于聚类改进的KNN文本分类算法[J]. 周庆平,谭长庚,王宏君,湛淼湘.  计算机应用研究. 2016(11)
