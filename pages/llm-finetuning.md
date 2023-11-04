## 监督学习在多模态大语言模型中的应用

<div grid="~ cols-2 gap-4">
<div class="mt-2 text-sm">

- 模型微调、语音识别等领域

ChatGPT的模型微调过程除了利用到了基于人类反馈的强化学习(RLHF)外，还用到了监督学习。[via](https://en.wikipedia.org/wiki/ChatGPT)

![](https://vip2.loli.io/2023/10/31/qeImJWFw2zU8VaN.webp)

9月份，OpenAI新出的GPT-4V，能看，能听，能说。其中的听，使用的是OpenAI自己研发的whisper模型，其中主要利用了监督学习。[via](https://openai.com/research/whisper)

![](https://vip2.loli.io/2023/10/31/3tGxm9yKXdabcTD.webp)

</div>


<div text-sm>

<h3 mt-4>个人经历</h3>

- 研究生团队前段时间使用国内清华大学开源的ChatGLM2-6B大语言模型，附加自己的数据集(train.json和dev.json)对基础大模型进行微调时，用到了监督学习。

- 前一阵子，个人试用了OpenAI 8月份推出的Fine-Tuning功能，附加自己的数据集(training_data.jsonl和validation_data.jsonl)，微调GPT-3.5，用到了监督学习。

<div class="flex items-center justify-center space-x-4 mt-6">
    <img src="/hf-logo.svg" alt="hf-logo" class="w-16 h-16">
    <logos-openai-icon w-12 h-12 />
</div>

<center text-sm>Fine-Tuning in LLM.</center>

</div>
</div>

<!-- 

1. ...

2. OpenAI的GPT-4V：
GPT-4V是OpenAI最新发布的模型，它的功能不仅仅局限于文本，还拓展到了视觉和听觉领域。特别是在语音识别部分，OpenAI使用了自研的Whisper模型。Whisper模型的核心技术主要利用了监督学习，这再次证明了监督学习在模型训练中的关键作用。

3. ...

4. ...

通过上述内容，我们可以明显看到，无论是国内还是国外的研究，监督学习都在大预言模型中起到了不可或缺的作用。 -->


