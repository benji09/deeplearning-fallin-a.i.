About prompt engineering

我用中文最易懂的方式写

1 吴恩达的prompt提示工程

2 prompt实践方面

3 

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










































