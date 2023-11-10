## 回归问题的应用

<div grid="~ cols-2 gap-4">

<div mt-3 text-sm>

- 使用LinearRegression模型，基于NumPy库进行数据准备和模型训练，用于预测股票的明天收盘价。

<a href="https://vip2.loli.io/2023/10/30/9km7UarzN1sFTBX.webp" target="_blank"><img src="https://vip2.loli.io/2023/10/30/9km7UarzN1sFTBX.webp" /></a>

<center>代码执行流程</center>

</div>

<div m-6 text-center>

![](https://vip2.loli.io/2023/10/30/hNLgCFaGrlfDVAt.webp)

<center text-sm mt-2>使用线性回归模型预测明天股票的收盘价</center>

</div>

</div>


<!--  

监督学习在回归问题方面的应用有很多，以刚才流程图演示的股票明天收盘价预测为例。

我们选择了一个简单的线性回归（LinearRegression）模型来进行这项任务。线性回归是最基本的回归算法之一，它旨在找到输入特征和目标输出之间的线性关系。

我们的目标是预测明天的股票收盘价。为了实现这一目标，我们将使用股票的历史数据，特别是过去的今明两天收盘价，作为我们的输入特征。

训练完线性回归模型后，提供今天该股票的收盘价，以预测明天股票的收盘价。

请注意，股票价格预测是一个复杂的问题，受到许多因素的影响。这边为了方便演示监督学习在回归问题方面的应用，简化了输入特征。

-->