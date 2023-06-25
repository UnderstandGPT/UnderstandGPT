---
sidebar_position: 4
---

# Hardware Requirements

Depending on the hardware that you have access to will depend on the size of model which you can run. 

Running larger models can be more demanding and require a more powerful system. The larger the model, the more capabilities it will have and the "smarter" it will appear when interacting with it.

Large Language Models can be very large so some members of the open-source community have begun to re-quantize (compress) models from 8 or 16-bit into 4-bit, thus allowing them to better fit on consumer level cards.

The below can be used as a rough guideline of what models you should be able to run on your system:

| Model Size | Required VRAM (4bit) | Required VRAM (8bit) | Recommended GPU (4bit) |
|---|---|---|---|
| 7B   | 6GB   | 10GB | GTX 1660, 2060, AMD 5700 XT, RTX 3050, 3060 |
| 13B  | 10GB  | 20GB | AMD 6900 XT, RTX 2060 12GB, 3060 12GB, 3080, A2000 |
| 30B  | 20GB  | 40GB | RTX 3080 20GB, A4500, A5000, 3090, 4090, 6000, Tesla V100 |
| 65B  | 40GB  | 80GB | A100 40GB, 2x3090, 2x4090, A40, RTX A6000, 8000 |