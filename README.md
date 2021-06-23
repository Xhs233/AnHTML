# AnHTML
欢迎来到popol机器学习

## 您将在这里学习并下载所用的数据集MNIST
注：这些数据集来自
Github上的zalandoresearch，tensorflow

### Demo(fashion流行衣服识别分类)
![image](https://github.com/zalandoresearch/fashion-mnist/blob/master/doc/img/fashion-mnist-sprite.png)
![image](https://github.com/zalandoresearch/fashion-mnist/blob/master/doc/img/embedding.gif)

## 获取数据

[很多的机器学习库](#使用其它机器学习库)已经内置了Fashion-MNIST数据或接口，方便你直接使用。


你可以使用以下链接下载这个数据集。`Fashion-MNIST`的数据集的存储方式和命名与[经典MNIST数据集](http://yann.lecun.com/exdb/mnist/)完全一致。

| 名称  | 描述 | 样本数量 | 文件大小 | 链接 | MD5校验和|
| --- | --- |--- | --- |--- |--- |
| `train-images-idx3-ubyte.gz`  | 训练集的图像  | 60,000|26 MBytes | [下载](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-images-idx3-ubyte.gz)|`8d4fb7e6c68d591d4c3dfef9ec88bf0d`|
| `train-labels-idx1-ubyte.gz`  | 训练集的类别标签  |60,000|29 KBytes | [下载](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/train-labels-idx1-ubyte.gz)|`25c81989df183df01b3e8a0aad5dffbe`|
| `t10k-images-idx3-ubyte.gz`  | 测试集的图像  | 10,000|4.3 MBytes | [下载](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-images-idx3-ubyte.gz)|`bef4ecab320f06d8554ea6380940ec79`|
| `t10k-labels-idx1-ubyte.gz`  | 测试集的类别标签  | 10,000| 5.1 KBytes | [下载](http://fashion-mnist.s3-website.eu-central-1.amazonaws.com/t10k-labels-idx1-ubyte.gz)|`bb300cfdad3c16e7a12a480ee83cd310`|

或者，你可以直接克隆这个代码库。数据集就放在`data/fashion`下。这个代码库还包含了一些用于评测和可视化的脚本。
   
```bash
git clone git@github.com:zalandoresearch/fashion-mnist.git
```

### 类别标注
每个训练和测试样本都按照以下类别进行了标注：

| 标注编号 | 描述 |
| --- | --- |
| 0 | T-shirt/top（T恤）|
| 1 | Trouser（裤子）|
| 2 | Pullover（套衫）|
| 3 | Dress（裙子）|
| 4 | Coat（外套）|
| 5 | Sandal（凉鞋）|
| 6 | Shirt（汗衫）|
| 7 | Sneaker（运动鞋）|
| 8 | Bag（包）|
| 9 | Ankle boot（踝靴）|


### 使用其它的语言

作为机器学习领域里最常使用的数据集，人们用各种语言为MNIST开发了很多载入工具。有一些方法需要先解压数据文件。注意，我们并没有测试过所有的载入方法。

- [C](https://stackoverflow.com/a/10409376)
- [C++](https://github.com/wichtounet/mnist)
- [Java](https://stackoverflow.com/a/8301949)
- [Python](https://pypi.python.org/pypi/python-mnist) and [this](https://pypi.python.org/pypi/mnist)
- [Scala](http://mxnet.io/tutorials/scala/mnist.html)
- [Go](https://github.com/schuyler/neural-go/blob/master/mnist/mnist.go)
- [C#](https://jamesmccaffrey.wordpress.com/2013/11/23/reading-the-mnist-data-set-with-c/)
- [NodeJS](https://github.com/ApelSYN/mnist_dl)和[这里](https://github.com/cazala/mnist)
- [Swift](https://github.com/simonlee2/MNISTKit)
- [R](https://gist.github.com/brendano/39760)和[这里](https://github.com/maddin79/darch)
- [Matlab](http://ufldl.stanford.edu/wiki/index.php/Using_the_MNIST_Dataset)
- [Ruby](https://github.com/gbuesing/mnist-ruby-test/blob/master/train/mnist_loader.rb)
- [Rust](https://github.com/AtheMathmo/vision-rs/blob/master/src/fashion_mnist.rs)
