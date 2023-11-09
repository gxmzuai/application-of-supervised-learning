1、

大家好，今天我来汇报一下监督学习方法的应用。 

2、

今天我汇报的内容包括6个部分，第一部分，我会带大家回顾一下监督学习的概念；
二至四部分，主要介绍监督学习的两大基本问题分类和回归问题方面的应用。
第五部分，介绍监督学习在目前大火的大语言模型领域的应用。
最后做本次报告的总结。

3、

有关监督学习的要点，简要来说就是用一个带标签的数据集用于模型的训练。在训练过程中，模型学习到一个函数，这个函数用于对输入数据进行预测。一旦函数被学习完成，模型就可以被用于预测未标记的数据。 

4、


监督学习的两大传统问题是分类问题和回归问题，下面我来介绍监督学习在这两大问题方面的应用。

先来简单地介绍一下分类问题。

5、

监督学习的两大传统问题是分类问题和回归问题，下面我来介绍监督学习在这两大问题方面的应用。

先来简单地介绍一下分类问题。

如幻灯片所示，分类问题的核心目标是预测离散值或类别标签。这与之后要讲的回归问题预测连续值的目标形成了鲜明的对比。

为了方便理解，我们使用动物图片分类的例子来揭示分类问题的基本流程：

1、首先，我们有一个带有标签的动物图片数据集。这些图片都带有对应的动物名称标签，例如“狗”、“猫”等。

2、在这一步，我们使用这些带标签的图片来训练一个分类模型。这个模型将学习如何根据图片中的动物特征来识别并预测动物类别。

3、一旦模型训练完成，我们可以使用它来对那些没有标签的动物图片进行预测。模型将尝试根据它在训练过程中所学到的知识来预测图片中动物的类别。

4、最后，我们得到了模型的预测结果，即该图片所属的动物类别。

分类问题是监督学习中的一个核心问题，它涉及到识别和预测数据点的特定类别。

6、