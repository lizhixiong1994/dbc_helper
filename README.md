## 一款利用命令行单词的小工具
### 可以再工作闲暇时光高效记忆单词
### 运行环境 python 3.6及以上

~~~
利用exls储存数据
单词模块包括：
nj3000（牛津3000单词）
kydc（考研5500单词）
简介：
1：每个单词有两个关键参数nums 以及 hit_nums 还有 权重
2：权重可以理解为抽中的概率，越大则出现的概率越高
3：nums 可以理解为出现频率，该值越大，权重越大
4：hit_nums 可以理解为单词熟练度， 做题每对一次，hit_nums值会越大，做错一次会变小，当熟练度达到最大时，则该单词出现的概率会大幅度减小，当熟练度小于0时，该单词出现的概率会大幅度增加
5：具体权重计算规则可以参考get_weight方法
6：调参参考代码
~~~
