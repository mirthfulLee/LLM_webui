## 说明

本仓库fork自 [Chuanhu Chat](https://github.com/GaiZhenbiao/ChuanhuChatGPT), 删除了一些个人不需要的功能, 再根据个人需求修改了一些UI.

## 目录

| [支持模型](#支持模型) | [使用技巧](#使用技巧) | [安装方式](https://github.com/GaiZhenbiao/ChuanhuChatGPT/wiki/使用教程) | [常见问题](https://github.com/GaiZhenbiao/ChuanhuChatGPT/wiki/常见问题) |
| --- | --- | --- | --- |

## 支持模型

| API 调用模型 | 备注 | 本地部署模型 | 备注 |
| :---: | --- | :---: | --- |
| [ChatGPT(GPT-4)](https://chat.openai.com) | 支持微调 gpt-3.5 | [ChatGLM](https://github.com/THUDM/ChatGLM-6B) ([ChatGLM2](https://github.com/THUDM/ChatGLM2-6B)) |
| [Azure OpenAI](https://azure.microsoft.com/en-us/products/ai-services/openai-service) |  | [LLaMA](https://github.com/facebookresearch/llama) | 支持 Lora 模型
| [Google PaLM](https://developers.generativeai.google/products/palm) | 不支持流式传输 | [StableLM](https://github.com/Stability-AI/StableLM)
| [讯飞星火认知大模型](https://xinghuo.xfyun.cn) |  | [MOSS](https://github.com/OpenLMLab/MOSS)
| [Inspur Yuan 1.0](https://air.inspur.com/home) |  | [通义千问](https://github.com/QwenLM/Qwen/tree/main)
| [MiniMax](https://api.minimax.chat/) |
| [XMChat](https://github.com/MILVLG/xmchat) | 不支持流式传输
| [Midjourney](https://www.midjourney.com/) | 不支持流式传输
| [Claude](https://www.anthropic.com/) |

## 快速上手

克隆仓库到本地后, 在项目文件夹中复制一份 `config_example.json`，并将其重命名为 `config.json`，在其中填入 `API-Key` 等设置。

```shell
pip install -r requirements.txt
python chatbot.py
```

一个浏览器窗口将会自动打开，此时您将可以使用 **川虎Chat** 与ChatGPT或其他模型进行对话。

> **Note**
>
> 具体详尽的安装教程和使用教程请查看[ChuanhuChat的wiki页面](https://github.com/GaiZhenbiao/ChuanhuChatGPT/wiki/使用教程)。
