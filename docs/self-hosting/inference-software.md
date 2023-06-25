---
sidebar_position: 5
---

# Inference Software

Inference software serves as your personal assistant in navigating the world of AI and Large Language Models (LLMs). These tools empower you to operate AI models on your local hardware, making modifications as needed and pushing the boundaries of what's possible.

## What is Inference Software?

In essence, inference software is an adjustable conduit between you and AI models. These applications allow you to shape the responses of AI models by offering diverse methods to train and fine-tune the outputs. 

Options abound. Some, like **gpt4all** and **TavernAI**, emphasize user-friendly interfaces, inviting anyone to interact with AI models seamlessly. In contrast, software like **oobabooga** and **koboldcpp** encourage a deeper dive, providing extensions that grant you full control over your AI/LLM.

## Choosing Your Inference Software

Your ideal inference software aligns with your goals. Some options, lean and API-based, offer a lightweight approach to interacting with models. Others invite you to dedicate as much computing power as you're willing to give. The perfect fit doesn't exist universally, but rather depends on your unique needs and preferences. 

If unsure where to begin, consider starting with the tried and true [text-generation-webui](https://github.com/oobabooga/text-generation-webui) by oobabooga. As your comfort with the workflow grows, feel free to explore others and discover which ones resonate the most with you.

## Recommended Options

Here are a few inference software options that have gained traction in the FOSS and FOSAI communities. These are continually gaining more support and compatibility, expanding the possibilities of what we can achieve with AI and LLMs.

1. [**oobabooga**](https://github.com/oobabooga/text-generation-webui): Probably the most popular choice - this interface is inspired by [Automatic1111's stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) interface, aiming to be the [text-generation-webui](https://github.com/oobabooga/text-generation-webui) equivalent of LLMs. This free and open-source web client interfaces with [HuggingFace](https://huggingface.co/) LLMs, which is the world's largest repository of AI models. It allows you to download, chat, and configure text-based models similar to Chat-GPT. However, not all models on HuggingFace perform at the same level as Chat-GPT out of the box. Many require 'fine-tuning' or 'training' to produce consistent, coherent results. 

2. [**Koboldcpp**](https://github.com/LostRuins/koboldcpp): This web-based interface lets you chat with LLMs locally and supports GGML inference. It's part of a platform focused on the role-playing aspect of generative AI and LLMs. 

3. [**TavernAI**](https://github.com/TavernAI/TavernAI): This customized web client is as functional as gpt4all and allows you to connect with Kobold's API or insert your own Chat-GPT API key to talk with OpenAI's GPT-3. 

4. [**SillyTavern**](https://github.com/SillyTavern/SillyTavern): This is another variant of the TavernAI client, offering similar functionalities but is quickly becoming the more popular of the two with its expanded compatiblities and documentation.

5. [**gpt4all**](https://github.com/nomic-ai/gpt4all): This is a user-friendly interface that's compatible with some of the latest open-source LLM models. It supports different model formats, including GGML, which enables GPU + CPU compute. 

6. [**Exllama**](https://github.com/turboderp/exllama): A standalone Python/C++/CUDA implementation of Llama for use with 4-bit GPTQ weights, designed to be fast and memory-efficient on modern GPUs. Please note, this project is still a work in progress and you can only run LlaMA specific models using this platform.

Remember, the best inference software for you depends on your specific needs and technical expertise. Explore each one and find the one that you like the most.

### **Quick Links**

- [How-To-Install-oobabooga](https://www.youtube.com/watch?v=lb_lC4XFedU)
- [How-To-Install-Koboldcpp](https://github.com/LostRuins/koboldcpp)
- [How-To-Install-TavernAI](https://github.com/TavernAI/TavernAI/wiki/How-to-install)
- [How-To-Install-SillyTavern](https://github.com/SillyTavern/SillyTavern)
- [How-To-Install-gpt4all](https://www.youtube.com/watch?v=rOa0wy2TDYE)
- [How-To-Install-Exllama](https://github.com/turboderp/exllama)
