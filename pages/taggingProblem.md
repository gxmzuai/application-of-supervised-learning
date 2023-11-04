## 标注问题（分类问题的推广）的应用

<div grid="~ cols-2 gap-4">

<div mt-3 text-sm>

- 使用预训练的词性标注模型，结合NLTK库和Penn Treebank词性标签，对英文句子进行词性标注。

<a href="https://vip2.loli.io/2023/10/30/ZFGkKmSrawTLfjo.webp" target="_blank"><img src="https://vip2.loli.io/2023/10/30/ZFGkKmSrawTLfjo.webp" /></a>

<center>Execution order diagram</center>

</div>

<div flex flex-col justify-center items-center mx-12>
    <img src="https://vip2.loli.io/2023/10/30/4zmsitcexA3MF59.webp" />
    <center text-sm mt-2>Use NLTK's pre-trained averaged perceptron tagger to perform part-of-speech tagging on an English sentence.</center>
</div>

</div>

<!-- 监督学习在标注方面的应用有很多,以刚才流程图演示的词性标注的为例。

词性标注是自然语言处理中的一个基本任务，它涉及为句子中的每个词分配一个标签，来表示这个词在句子中的语法功能，如名词、动词、形容词等。

在词性标注这个例子中，我们使用的是预训练的词性标注模型（averaged_perceptron_tagger）。这个模型是一个高效且准确的机器学习算法，经常被用于词性标注任务。

为了进行标注，我们选择了NLTK（Natural Language Toolkit）库，这是一个广泛使用的自然语言处理工具包。与此同时，我们使用了Penn(University of Pennsylvania) Treebank词性标签，这是一个标准的词性标签集，广泛应用于自然语言处理任务，由宾夕法尼亚大学的研究生参与创建。

右侧代码的执行流程如左图所示。 -->
