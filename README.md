---
language:
- zh
- en
tags:
- qwen
base_model: Qwen/Qwen-1_8B-Chat
license: mit
---

## Overview

This model is a 4bit quantized version in GGUF format of the original [Qwen/Qwen-1_8B-Chat](https://huggingface.co/Qwen/Qwen-1_8B-Chat) model.

## How to use

Make sure you are using llama.cpp from commit [37c746d](https://github.com/ggerganov/llama.cpp/commit/37c746d687d877bc11803e96b4dc5f378b83c0a0) or later.

```shell
  ./main -m qwen-1_8b-chat.Q4_0.gguf --color -i -cml -n 512 -c 2048 -ngl 27 -p "you are a helpful assistant."
```
# qwen-tune
