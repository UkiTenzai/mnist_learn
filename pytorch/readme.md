## 学习pytorch框架的文件
一共有4个文件夹，`data`，`model`，`mydigit`和`src`。
`src`存放3个代码文件，分别是用class构造网络结构，用Sequential构造网络结构，加载已保存的模型预测自己写的数字。其中模型对应的是Sequential构造的。
自己写的数字存放在`mydigit`中，模型存放在`model`中。
`data`下存放着mnist的原数据，为减小体积，在上传GitHub时已经删除里面的数据，如果想获取原来的mnist数据，请在代码文件中将`download=False`改成`download=True`即可。

