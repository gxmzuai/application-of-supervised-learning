## 分类问题的应用

<div grid="~ cols-2 gap-4">

<div mt-3 text-sm>

- 使用预训练的ResNet-50模型（基于ImageNet数据集的子集训练得到）进行图片分类。

![](https://vip2.loli.io/2023/10/30/8VicrSF9yXNvOkG.webp)

<center>代码执行流程</center>

</div>

<div flex flex-col justify-center items-center mx-12>

![](https://vip2.loli.io/2023/10/30/FH2KNvELYRwnZTy.webp)

<center text-sm mt-2>使用ResNet-50模型来分类图像</center>

</div>

</div>

<!-- 

监督学习在分类问题方面的应用有很多，以刚才流程图演示的图片分类为例。

为了方便演示，这边我们采用的是预训练的ResNet-50模型（基于ImageNet数据集的子集训练得到）来进行图片分类。

ImageNet数据集（韩枫老师在高级人工智能课上提及过）：

它是一个大型的视觉数据库。其中包含了超过1000万个手动标注的图像，涵盖了22000个不同的类别。它为机器学习模型提供了丰富的训练资料。

ResNet(Residual Network)-50模型：

它是一个卷积神经网络模型。该模型基于部分ImageNet数据集（包含1000个类别，涉及不同种类的动物、植物等）训练。被广泛应用于图像分类。

PyTorch框架提供的ResNet-50模型，是一个预先训练好的深度学习模型，能够识别图像中的对象。当我们将一张预处理过的竹叶青蛇的图片输入该模型进行识别时，模型返回了一个类别ID：59。通过查询类别对照表，我们发现这个ID对应的是“vine snake”（藤蛇）。

由于ResNet-50的训练数据集限于1000个类别，所以未能精确识别出竹叶青，但它识别出的藤蛇与竹叶青有着相似的绿色外观，这一结果仍具有参考价值。

 -->