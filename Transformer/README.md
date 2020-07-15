## Transformer (Attention Is All You Need)


### 数据集：
#### SougouNews (http://www.sogou.com/labs/resource/cs.php) 中选出10个类别的新闻，每个类别5000个样本，组成总量为50000的数据集：
    it、women、business、sports、yule、learning、travel、auto、health、house


### 数据形式：
#### label \t content


### 文件解释
* main.py —— 主文件
* model.py —— 模型结构
* config.py —— 配置参数
* Data_Generate_SogouNews.py —— SougouNews新闻数据集处理脚本
* /data —— 数据存放文件夹
* /save_model —— 模型存储文件夹


### 模型结构
![avatar](./Transformer.png)
* Transformer的输入是Word Embedding + Position Embedding。
* Transformer中抛弃了传统的CNN和RNN，整个网络结构完全是由Attention机制组成
* 和大多数seq2seq模型一样，transformer的结构也是由encoder和decoder组成


### 参考资料
* Attention Is All You Need (https://arxiv.org/abs/1706.03762)
* https://www.cnblogs.com/jiangxinyang/p/10210813.html

