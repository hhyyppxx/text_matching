# text_matching
文本匹配模型

本项目包含目前大部分文本匹配模型，持续更新中

数据集为QA_corpus，训练数据10w条，验证集和测试集均为1w条

其中对应模型文件夹下的`args.py`文件是超参数

训练：
`python train.py`

测试：
`python test.py`

测试集结果对比：

模型|loss|acc|论文地址
--|--|--|--|--
DSSM|0.7613157|0.6864|[DSSM](https://posenhuang.github.io/papers/cikm2013_DSSM_fullversion.pdf)
ESIM|0.55444807|0.736|[ESIM](https://arxiv.org/pdf/1609.06038.pdf)
CONVNET|0.6872447|0.6977|[ConvNet]([http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.723.6492&rep=rep1&type=pdf)



