## 监督学习在大语言模型中的应用

<div grid="~ cols-2 gap-4">
<div class="mt-3 text-sm">

ChatGPT的模型微调过程利用到了基于人类反馈的强化学习(RLHF)，基于人类反馈的强化学习可看作是结合了监督学习和强化学习的方法。[via](https://en.wikipedia.org/wiki/ChatGPT)

![](https://vip2.loli.io/2023/10/31/qeImJWFw2zU8VaN.webp)

今年9月份，OpenAI新出的GPT-4V，能看，能听，能说。其中的听，使用的是OpenAI自己研发的whisper模型，其中利用到了监督学习。[via](https://openai.com/research/whisper)

![](https://vip2.loli.io/2023/10/31/3tGxm9yKXdabcTD.webp)

</div>


<div text-sm>

- 研究生小组前段时间使用国内清华大学开源的ChatGLM2-6B大语言模型，附加自己的数据集(train.json和dev.json)对基础大模型进行微调时，用到了监督学习。

- 上周OpenAI首届开发者大会后，推出的Create a GPT功能，允许用户用多轮对话的形式创造出特定领域的GPT，这种多轮对话形式的模型微调，技术中也涉及监督学习的身影。

![](https://vip2.loli.io/2023/11/10/n34Z691Dhtesxql.webp)

<center text-sm>Fine-Tuning in LLM.</center>

</div>
</div>

<!-- 

去年11月底发布的ChatGPT，掀起了AI领域的大变革。

ChatGPT的模型微调过程......

在这种方法中，监督学习用于从人类反馈中学习期望的行为。

今年9月份，OpenAI新出的GPT-4V，能看，能听，能说。其中的听，使用的是OpenAI去年推出的whisper模型，其中利用到了监督学习。whisper模型使用从网络上收集到的带标注的68万小时数据进行训练。

上个月，研究生小组使用清华大学开源的ChatGLM这个大语言模型作为基础大模型，使用了包含标签或答案的数据集（train.json和dev.json）对其进行微调，这里面涉及到了监督学习。由于数据量的不足，最后微调的效果不佳。

上周OpenAI开发者大会后......

下图是我微调的一个GPT，用一轮对话即可实现了它身份认知的转变。当然如果追求更加完美的效果，可以附加自己独特的数据集。

通过上述内容，我们可以看到，无论是国内还是国外的研究，在大语言模型的研究中，或多或少存在监督学习的身影。

-->


