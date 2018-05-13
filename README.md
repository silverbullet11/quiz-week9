# 第九周作业：

## 1. 数据集准备：
https://www.tinymind.com/silverbullet11/datasets/w9vgg16

包括：
1.1 vgg_16.ckpt: vgg_16的checkpoint文件
1.2 fcn_train.record: 本地生成的训练数据
1.3 fcn_val.record: 本地生成的验证数据

## 2. 训练模型执行结果：
2.1 模型设置： https://www.tinymind.com/silverbullet11/quiz-w9

2.2 执行结果(log)： https://www.tinymind.com/executions/b4j88mru

## 3. 模型输出结果：
https://www.tinymind.com/executions/b4j88mru/output

## 4. 模型代码补全：
N/A

## 5. 心得体会：
对fcn的理解：
- FCN通过反卷积将很小的feature map扩张到较大的空间尺度，从而丰富输出的特征。
- 通过将全连接操作替换成卷积操作，可以避免输入数据大小的影响。
