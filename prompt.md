About prompt engineering

我用中文最易懂的方式写


https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/

LLM large language model 
API 调用 LLM 

Angrew prompt engineer for developers 
1th: 

openAI的python库来访问openAI API : 安装这个库: pip install openai
https://openai.xiniushu.com/docs/libraries
英文文档：
https://platform.openai.com/account/billing/overview    

1. 可以复习下python
key放在系统变量，位置注意
相关报错
1. 
 raise self.handle_error_response(
openai.error.RateLimitError: You exceeded your current quota, please check your plan and billing details.
//配额用量查看，https://platform.openai.com/account/usage
//免费问题就升级到付费


2. 再接着看openai的文档
开发人员：使用 API 调用到 LLM，以快速构建软件应用程序

LLM类型：基础LLM 、指令微调LLM
    基础LLM: 基于文本训练数据，训练出预测下一个单词能力的模型，其通常是在互联网和其他来源的大量数据上训练的。

    指令调整的 LLMs 的训练通常是从已经训练好的基本 LLMs 开始，该模型已经在大量文本数据上进行了训练。指令调整的 LLMs 已经被训练成有益、诚实和无害的，



3. openai version: 0.27.6
4. some guide
https://boostpixels.com/guide
effective prompt: 
    Default word the model is trained on is "ftpdnx". 
    Weight in words means how much a word affects the image being generated.
    If the generated image doesn't look like you, try adding "(ftpdnx person)" to your prompt. This helps the AI understand that it should use the photo that the model was trained on.

5. 
OpenAI API 现在支持函数调用了 gpt-4-0613 和 gpt-3.5-turbo-0613 模型，场景：
1创建聊天机器人，通过调用外部工具（例如 ChatGPT 插件）来回答问题
2将自然语言转换为 API 调用或数据库查询
3从文本中提取结构化数据


6. 

??
github.com/mshumer/gpt-prompt-engineer
引入了提示测试、ELO 评级系统、权重和偏差日志记录，在 Prompt 生成过程中，给你足够的数据作为评估。


7. Some references
https://github.com/dair-ai/Prompt-Engineering-Guide
https://github.com/PlexPt/awesome-chatgpt-prompts-zh
https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/
github.com/f/awesome-chatgpt-prompts
https://platform.openai.com/docs/guides/prompt-engineering
https://github.com/antirez/freakwan/blob/main/osx-bte-cli/SerialBTE.m
https://groq.com/
https://www.yuque.com/xinntao/nm1yxs/wvritz5ulgv3qriu
https://huggingface.co/shenzhi-wang/Llama3-8B-Chinese-Chat
https://huggingface.co/datasets/HuggingFaceFW/fineweb

《Learning to Attribute with Attention》B Cohen-Wang, Y Chuang, A Madry 

Generated Knowledge Prompting for Commonsense Reasoning
Automatic Chain of Thought Prompting in Large Language Models
A universal local knowledge base solution based on vector database and GPT3.5



By June 



8. 上下文 
    30000？

9. basic terms 
    Hallucination
    Toxicity

will do
中文造诣提高策略步骤





关于泛化能力
NLP  advanced
xl apparently more faster, better


AI语音生成器 (weekend comment)
lovo.ai 
elevenlabs
murf.ai 



2.19 bla
官方文档看一下，分步解答很好
ReAct 框架 需要例子
RAG for LLMs how to explain
doubao accessment


others: 
扩散模型是如何工作
Dr Shaopin Ma  book 
Mistral
RAG papers Shi-Qi Yan
Llama library
Advanced RAG Applications

marscode about some algorithms 



中文分享知识文档
https://waytoagi.feishu.cn/wiki/QPe5w5g7UisbEkkow8XcDmOpn8e?mark_id=followtopweibo&continueFlag=660e4b571a54d5129818f620289dca7d


Application
可视化的prompt国外网站搜索，like Math, algorithm，thought, abstract conception。 




Bottom: 
“The hottest new programming language is English”
might not be needed in three years, maybe one or two years.









































































