## 分类问题的应用

<div grid="~ cols-2 gap-4">

<div mt-3 text-sm>

- 使用预训练的ResNet-50模型（基于ImageNet数据集的子集）进行图片分类。

![](https://vip2.loli.io/2023/10/30/8VicrSF9yXNvOkG.webp)

<center>Execution order diagram</center>

</div>

<div flex flex-col justify-center items-center mx-12>

<img src="https://vip2.loli.io/2023/10/30/FH2KNvELYRwnZTy.webp" />

<center text-sm mt-2>Use ResNet-50 model to classify images.</center>

</div>

</div>

<!-- 监督学习在分类问题方面的应用有很多，以刚才流程图演示的图片分类为例。

我们采用预训练的ResNet-50模型（基于ImageNet数据集的子集）进行图片分类。

首先给大家简单地介绍一下ImageNet数据集和ResNet-50模型。

ImageNet数据集（韩枫老师在高级人工智能课上提及过）：

它是一个大型的视觉数据库。其中包含了超过1000万个手动标注的图像，涵盖了22000个不同的类别。这个数据集的重要性在于它的规模和多样性，为机器学习模型提供了丰富的训练资料。它的主要创始人和关键贡献者是华人AI女神—李飞飞。

ResNet(Residual Network)-50模型：

这是深度学习领域中广受欢迎的卷积神经网络模型。该模型基于部分ImageNet数据集（包含1000个类别，含有不同种类的动物、植物、交通工具、日常用品等）训练。被广泛应用于图像分类。

PyTorch框架提供了预训练的ResNet-50模型。当我们用它来处理图像时，它会返回与图像内容相匹配的类别ID。然后，我们可以参考相应的类别表来获取该ID对应的类别名称。

右侧代码的执行流程如左图所示。 -->