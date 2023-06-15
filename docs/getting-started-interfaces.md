# How do I get started, what interfaces can I use?

To interact with a model it is recommend that you utilize one of the pre-existing interfaces that have been built by the open-source community.

These interfaces provide several handy features:
- A chat-like interface to interact with your model
- Swapping between prompt types to match the model being used
- Model re-training (currently Ooba only)
- Support for changing model parameters on the fly

There are a few interface options based on your particular needs:

##### text-generation-webui (aka Oobabooga)

![UI Image](https://raw.githubusercontent.com/oobabooga/screenshots/main/galactica.png)

Ooba is one of the most popular user-interfaces for interacting with locally hosted LLMs and a recommended starting point.

- Chat with streaming output
- Download & manage models via UI
- API Support (including drop-in replacement for OpenAI)
- LoRA (Low Rank) Model Training
- Extendable via Plugins

GitHub: https://github.com/oobabooga/text-generation-webui

##### koboldcpp

![UI Image](https://raw.githubusercontent.com/LostRuins/koboldcpp/concedo/media/preview.png)

Interact with llama.cpp, a port of Facebook's LLaMA model in C/C++ 

- Simple, focused UI
- Maintains conversation context
- Windows/Mac/Linux Support
- Only 20MB!

GitHub: https://github.com/LostRuins/koboldcpp

##### Exllama

![UI Image](https://raw.githubusercontent.com/turboderp/exllama/master/doc/_screenshot.jpg)

Exllama is an emerging interface which is focused on being memory efficient for better compatibility with modern GPUs.

- Focused on speed & memory management
- Polished user interface
- Multi-bot mode
- Ongoing updates

GitHub: https://github.com/turboderp/exllama

##### SillyTavern

![UI Image](https://user-images.githubusercontent.com/18619528/228649856-fbdeef05-d727-4d5a-be80-266cbbc6b811.png)

A popular user-interface option for those interested in role-playing and character creation.

- Support for group chats
- Define worlds for enhanced immersion
- Create character agent bots
- Connectable with Oobabooga via API
- Supports additional functionality via Extensions

GitHub: https://github.com/SillyTavern/SillyTavern