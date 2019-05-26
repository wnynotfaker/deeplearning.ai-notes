<h1 align="center">C2W1 深度学习的实践</h1>

## 测验
___
> 1、如果你有10,000,000个例子，你会如何划分训练/开发/测试集？？
- [ ] 训练集占33%，验证集占33%，测试集占33%.
- [ ] 训练集占60%，验证集占20%，测试集占20%.
- [x] 训练集占98%，验证集占1%，测试集占1%.
___
> 2、开发和测试集应该：
- [x] 来自同一分布
- [ ] 来自不同分布
- [ ] 每对数据(x,y)彼此相同
- [ ] 有相同数量的实例
___
> 3、如果你的神经网络模型似乎有很高的方差，下列哪个尝试是可能解决问题的？
- [x] 添加正则化
- [ ] 获取更多的测试数据
- [ ] 增加每个隐藏层中的神经元个数
- [ ] 加深神经网络
- [x] 获取更多的训练数据
___
> 4、你在一家超市的自动结帐亭工作，正在为苹果，香蕉和橘子制作分类器。 假设您的分类器在训练集上有0.5％的错误，以及验证集上有7％的错误。 以下哪项尝试是有希望改善你的分类器的分类效果的？
- [x] 增大正则化参数lambda
- [ ] 减小正则化参数lambda
- [x] 获取更多的训练数据
- [ ] 用一个更大的神经网络
___
> 5、什么是权重衰减？
- [x] 一种正则化技术（如L2正则化），使得每次迭代时，权重都缩小。
- [ ] 训练过程中逐渐降低学习率的过程。
- [ ] 权重的逐渐损坏，如果神经网络是在有噪声的数据上训练的。
- [ ] 通过对权重值施加一个上限来避免梯度消失的一种技术。
___
> 6、当你增加正则化超参数lambda时会发生什么？
- [x] 权重会变得更小（接近0）
- [ ] 权重会变得更大（远离0）
- [ ] 加倍lambda会粗略地导致权重加倍
- [ ] 梯度下降在每次迭代中采取更大的步距（与lambda成比例）
___
> 7、利用Inverted-dropout技术，在测试的时候：
- [ ] 使用dropout（随机失活神经元），不保留训练过程计算中使用过的1/keep-prob因子。
- [ ] 使用dropout（随机失活神经元），保留训练过程计算中使用过的1/keep-prob因子。
- [ ] 不使用dropout（不随机失活神经元），保留训练过程计算中使用过的1/keep-prob因子。
- [x] 不使用dropout（不随机失活神经元），不保留训练过程计算中使用过的1/keep-prob因子。
___

> 8、将参数keep_prob从（比如说）0.5增加到0.6可能会导致以下情况
- [ ] 增强正则化效应。
- [x] 减弱正则化效应。
- [ ] 使神经网络以较大的训练集误差结束    
- [x] 使神经网络以较小的训练集误差结束
___
> 9、以下哪些技术可用于减少方差（减少过拟合）：
- [ ] Xavier初始化
- [x] 数据增强
- [ ] 梯度检查
- [ ] 梯度爆炸
- [x] L2 正则化
- [ ] 梯度消失
- [x] Dropout
___
> 10、为什么我们要归一化输入x？
- [ ] 使参数初始化更快
- [x] 使成本函数更快地进行优化
- [ ] 有助于减少方差，归一化是正则化(regularization)的另一个词
- [ ] 使数据更容易可视化
___