---
sidebar_position: 3
---

# Open Models

## Exploring the World of AI and Language Models

Entering the world of Artificial Intelligence (AI) and Large Language Models (LLMs) is like embarking on an exciting new journey. LLMs are AI models trained on large amounts of text data and are capable of understanding and generating human-like text. 

Several open-source versions of these models have gained popularity in the communities devoted to freely sharing software and AI technology, known as the Free Open-Source Software (FOSS) and Free Open-Source AI (FOSAI) communities. 

Before you choose which software to use, it's important to understand how well different models work with different systems. Let's look at some popular options you might consider, particularly if you're thinking about using AI or LLM technology in your business or service.

## Free Open-Source AI (FOSAI)

### Making AI Accessible to Everyone

FOSAI, like FOSS, is all about making AI technology available to everyone. The aim is to democratize technology so that each user can own and control the technology they use. 

Imagine running AI or LLMs on your personal computer or server. You could control everything - from how the models learn from data (known as training parameters) to which data sets they learn from and how they use information. It sounds empowering, right? That's the essence of FOSAI. The idea is to reduce our reliance on large tech companies and put more control in your hands as a consumer and everyday user. 

However, there are some challenges. For example, licensing can be a hurdle for startups that want to build their businesses on these models. Fortunately, this is becoming less of a problem as new models are developed, which create opportunities for startups to innovate without facing restrictions from larger tech competitors.

The FOSS and FOSAI communities are quickly becoming leaders in AI and LLM research and development. To learn more about this, we recommend reading "[We Have No Moat](https://www.semianalysis.com/p/google-we-have-no-moat-and-neither)", a leaked Google article that highlights the power of the open-source community in relation to LLMs.

Remember, as with any new technology, your experiences with FOSAI software applications and platforms may vary. For a handpicked list of open LLMs, check out [eugeneyan](https://github.com/eugeneyan/open-llms)'s GitHub page and consider supporting this valuable resource by giving it a star.

These models are all licensed for commercial use (e.g., Apache 2.0, MIT, OpenRAIL-M). [Contributions Welcome!](https://github.com/eugeneyan/open-llms)

### What Do the Licenses Mean?

- [Apache 2.0](https://en.wikipedia.org/wiki/Apache_License): Allows users to use the software for any purpose, to distribute it, to modify it, and to distribute modified versions of the software under the terms of the license, without concern for royalties.
- [MIT](https://en.wikipedia.org/wiki/MIT_License): Similar to Apache 2.0 but shorter and simpler. Also, in contrast to Apache 2.0, does not require stating any significant changes to the original code.
- [CC BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/): Allows (i) copying and redistributing the material and (ii) remixing, transforming, and building upon the material
for any purpose, even commercially. But if you do the latter, you **must distribute your contributions under the same license as the original.** (Thus, may not be viable for internal teams.)
- [OpenRAIL-M v1](https://www.bigcode-project.org/docs/pages/model-license/): Allows royalty-free access and flexible downstream use and sharing of the model and modifications of it, and comes with a set of use restrictions (see [Attachment A](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement))
- [BSD-3-Clause](https://en.wikipedia.org/wiki/BSD_licenses): This version allows unlimited redistribution for any purpose as long as its copyright notices and the license's disclaimers of warranty are maintained. 

**Disclaimer:** The information provided in this repo does not, and is not intended to, constitute legal advice. Maintainers of this repo and wiki are not responsible for the actions of third parties who use the models. Please consult an attorney before using models for commercial purposes.

For those looking for a quick rundown for how some of these perform in stylistic senses, see [KoboldAI](https://github.com/KoboldAI/KoboldAI-Client)'s GitHub page where they detail how some (not all) of these perform. 

| Language Model | Release Date | Checkpoints | Paper/Blog | Params (B) | Context Length | License | Try it                                                                                                                |
| --- | --- | --- | --- | --- | --- | --- |-----------------------------------------------------------------------------------------------------------------------|
| T5           | 2019/10 |[T5 & Flan-T5](https://github.com/google-research/t5x/blob/main/docs/models.md#flan-t5-checkpoints), [Flan-T5-xxl (HF)](https://huggingface.co/google/flan-t5-xxl)      | [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://github.com/google-research/text-to-text-transfer-transformer#released-model-checkpoints) | 0.06 - 11       | [512](https://discuss.huggingface.co/t/does-t5-truncate-input-longer-than-512-internally/3602) | Apache 2.0         | [T5-Large](https://github.com/slai-labs/get-beam/tree/main/examples/t5)                                               |
| UL2          | 2022/10 | [UL2 & Flan-UL2](https://github.com/google-research/google-research/tree/master/ul2#checkpoints), [Flan-UL2 (HF)](https://huggingface.co/google/flan-ul2)          | [UL2 20B: An Open Source Unified Language Learner](https://ai.googleblog.com/2022/10/ul2-20b-open-source-unified-language.html)                                                       | 20             | [512, 2048](https://huggingface.co/google/flan-ul2#tldr) | Apache 2.0         |                                                                                                                       |
| Cerebras-GPT | 2023/03 | [Cerebras-GPT](https://huggingface.co/cerebras)                                           | [Cerebras-GPT: A Family of Open, Compute-efficient, Large Language Models](https://www.cerebras.net/blog/cerebras-gpt-a-family-of-open-compute-efficient-large-language-models/) ([Paper](https://arxiv.org/abs/2304.03208)) | 0.111 - 13      | [2048](https://huggingface.co/cerebras/Cerebras-GPT-13B#model-details) | Apache 2.0         | [Cerebras-GPT-1.3B](https://github.com/slai-labs/get-beam/tree/main/examples/cerebras-gpt)                            |
| Open Assistant (Pythia family) | 2023/03 | [OA-Pythia-12B-SFT-8](https://huggingface.co/OpenAssistant/pythia-12b-sft-v8-7k-steps), [OA-Pythia-12B-SFT-4](https://huggingface.co/OpenAssistant/oasst-sft-4-pythia-12b-epoch-3.5), [OA-Pythia-12B-SFT-1](https://huggingface.co/OpenAssistant/oasst-sft-1-pythia-12b) | [Democratizing Large Language Model Alignment](https://arxiv.org/abs/2304.07327) | 12     | 2048  | Apache 2.0                | [Pythia-2.8B](https://github.com/slai-labs/get-beam/tree/main/examples/pythia)                                        |
| Pythia       | 2023/04 | [pythia 70M - 12B](https://github.com/EleutherAI/pythia)                                   | [Pythia: A Suite for Analyzing Large Language Models Across Training and Scaling](https://arxiv.org/abs/2304.01373)                                                                    | 0.07 - 12       | [2048](https://arxiv.org/pdf/2304.01373.pdf) | Apache 2.0         |                                                                                                                       |
| Dolly        | 2023/04 | [dolly-v2-12b](https://huggingface.co/databricks/dolly-v2-12b)                            | [Free Dolly: Introducing the World's First Truly Open Instruction-Tuned LLM](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm)             | 3, 7, 12     | [2048](https://github.com/databrickslabs/dolly#dolly) | MIT                |                                                                                                                       |
| DLite | 2023/05 | [dlite-v2-1_5b](https://huggingface.co/aisquared/dlite-v2-1_5b) | [Announcing DLite V2: Lightweight, Open LLMs That Can Run Anywhere](https://medium.com/ai-squared/announcing-dlite-v2-lightweight-open-llms-that-can-run-anywhere-a852e5978c6e) | 0.124 - 1.5 | 1024 | Apache 2.0         | [DLite-v2-1.5B](https://github.com/slai-labs/get-beam/tree/main/examples/dlite-v2)                                    |
| RWKV         | 2021/08| [RWKV, ChatRWKV](https://github.com/BlinkDL/RWKV-LM#rwkv-parallelizable-rnn-with-transformer-level-llm-performance-pronounced-as-rwakuv-from-4-major-params-r-w-k-v) | [The RWKV Language Model (and my LM tricks)](https://github.com/BlinkDL/RWKV-LM)                                           | 0.1 - 14      | [infinity (RNN)](https://github.com/BlinkDL/RWKV-LM#rwkv-parallelizable-rnn-with-transformer-level-llm-performance-pronounced-as-rwakuv-from-4-major-params-r-w-k-v) | Apache 2.0         |                                                                                                                       |
| GPT-J-6B | 2023/06 | [GPT-J-6B](https://github.com/kingoflolz/mesh-transformer-jax/#gpt-j-6b), [GPT4All-J](https://github.com/nomic-ai/gpt4all#raw-model) | [GPT-J-6B: 6B JAX-Based Transformer](https://arankomatsuzaki.wordpress.com/2021/06/04/gpt-j/) | 6 | [2048](https://github.com/kingoflolz/mesh-transformer-jax/#gpt-j-6b) | Apache 2.0 |                                                                                                                       |
| GPT-NeoX-20B | 2022/04 | [GPT-NEOX-20B](https://huggingface.co/EleutherAI/gpt-neox-20b) | [GPT-NeoX-20B: An Open-Source Autoregressive Language Model](https://arxiv.org/abs/2204.06745) | 20 | [2048](https://huggingface.co/EleutherAI/gpt-neox-20b) | Apache 2.0 |                                                                                                                       |
| Bloom | 2022/11 | [Bloom](https://huggingface.co/bigscience/bloom) | [BLOOM: A 176B-Parameter Open-Access Multilingual Language Model](https://arxiv.org/abs/2211.05100) | 176 | [2048](https://huggingface.co/bigscience/bloom) |  [OpenRAIL-M v1](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |                                                                                                                       |
| StableLM-Alpha | 2023/04 | [StableLM-Alpha](https://github.com/Stability-AI/StableLM#stablelm-alpha) | [Stability AI Launches the First of its StableLM Suite of Language Models](https://stability.ai/blog/stability-ai-launches-the-first-of-its-stablelm-suite-of-language-models) | 3 - 65 | [4096](https://github.com/Stability-AI/StableLM#stablelm-alpha) | CC BY-SA-4.0 |                                                                                                                       |
| FastChat-T5 | 2023/04 | [fastchat-t5-3b-v1.0](https://huggingface.co/lmsys/fastchat-t5-3b-v1.0) | [We are excited to release FastChat-T5: our compact and commercial-friendly chatbot!](https://twitter.com/lmsysorg/status/1652037026705985537?s=20) | 3 | 512 | Apache 2.0 |                                                                                                                       |
| h2oGPT | 2023/05 | [h2oGPT](https://github.com/h2oai/h2ogpt) | [Building the World’s Best Open-Source Large Language Model: H2O.ai’s Journey](https://h2o.ai/blog/building-the-worlds-best-open-source-large-language-model-h2o-ais-journey/) | 12 - 20 | [256 - 2048](https://huggingface.co/h2oai) | Apache 2.0 |                                                                                                                       |
| MPT-7B | 2023/05 | [MPT-7B](https://huggingface.co/mosaicml/mpt-7b), [MPT-7B-Instruct](https://huggingface.co/mosaicml/mpt-7b-instruct) | [Introducing MPT-7B: A New Standard for Open-Source, Commercially Usable LLMs](https://www.mosaicml.com/blog/mpt-7b) | 7 | [84k (ALiBi)](https://huggingface.co/mosaicml/mpt-7b#how-is-this-model-different) | Apache 2.0, CC BY-SA-3.0 |                                                                                                                       |
| RedPajama-INCITE | 2023/05 | [RedPajama-INCITE](https://huggingface.co/togethercomputer) | [Releasing 3B and 7B RedPajama-INCITE family of models including base, instruction-tuned & chat models](https://www.together.xyz/blog/redpajama-models-v1) | 3 - 7 | [2048](https://huggingface.co/togethercomputer/RedPajama-INCITE-Instruct-7B-v0.1/blob/157bf3174feebb67f37e131ea68f84dee007c687/config.json#L13) | Apache 2.0 | [RedPajama-INCITE-Instruct-3B-v1](https://github.com/slai-labs/get-beam/tree/main/examples/redpajama-incite-instruct) |
| OpenLLaMA | 2023/05 | [open_llama_7b_700bt_preview](https://huggingface.co/openlm-research/open_llama_7b_700bt_preview), [open_llama_3b_600bt_preview](https://huggingface.co/openlm-research/open_llama_3b_600bt_preview) | [OpenLLaMA: An Open Reproduction of LLaMA](https://github.com/openlm-research/open_llama) | 3, 7 | [2048](https://huggingface.co/h2oai) | Apache 2.0 | [OpenLLaMA-7B-Preview_200bt](https://github.com/slai-labs/get-beam/tree/main/examples/openllama)                      |
| Falcon | 2023/05 | [Falcon-40B](https://huggingface.co/tiiuae/falcon-40b), [Falcon-7B](https://huggingface.co/tiiuae/falcon-7b) | Paper coming soon | 7, 40 | 2048 | Apache 2.0 |    

## Open LLMs for code  

| Language Model | Release Date | Checkpoints | Paper/Blog | Params (B) | Context Length                                                                         | Licence | Try it                                                                                    |
| --- | --- | --- | --- | --- |----------------------------------------------------------------------------------------| --- |-------------------------------------------------------------------------------------------|
| SantaCoder | 2023/01 | [santacoder](https://huggingface.co/bigcode/santacoder) |[SantaCoder: don't reach for the stars!](https://arxiv.org/abs/2301.03988) | 1.1 | [2048](https://huggingface.co/bigcode/santacoder/blob/main/README.md#model-summary)                | [OpenRAIL-M v1](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) | [SantaCoder](https://github.com/slai-labs/get-beam/tree/main/examples/santacoder)         |
| StarCoder | 2023/05 | [starcoder](https://huggingface.co/bigcode/starcoder) | [StarCoder: A State-of-the-Art LLM for Code](https://huggingface.co/blog/starcoder), [StarCoder: May the source be with you!](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view) | 15 | [8192](https://huggingface.co/bigcode/starcoder#model-summary)                         | [OpenRAIL-M v1](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |                                                                                           |
| StarChat Alpha | 2023/05 | [starchat-alpha](https://huggingface.co/HuggingFaceH4/starchat-alpha) | [Creating a Coding Assistant with StarCoder](https://huggingface.co/blog/starchat-alpha) | 16 | [8192](https://huggingface.co/bigcode/starcoder#model-summary)  | [OpenRAIL-M v1](https://huggingface.co/spaces/bigcode/bigcode-model-license-agreement) |                                                                                           |
| Replit Code | 2023/05 | [replit-code-v1-3b](https://huggingface.co/replit/replit-code-v1-3b) | [Training a SOTA Code LLM in 1 week and Quantifying the Vibes — with Reza Shabani of Replit](https://www.latent.space/p/reza-shabani#details) | 2.7 | [infinity? (ALiBi)](https://huggingface.co/replit/replit-code-v1-3b#model-description) | CC BY-SA-4.0 | [Replit-Code-v1-3B](https://github.com/slai-labs/get-beam/tree/main/examples/replit-code) |
| CodeGen2 | 2023/04 | [codegen2 1B-16B](https://github.com/salesforce/CodeGen2) | [CodeGen2: Lessons for Training LLMs on Programming and Natural Languages](https://arxiv.org/abs/2305.02309) | 1 - 16 | [2048](https://arxiv.org/abs/2305.02309)                                               | Apache 2.0 |                                                                                           |
| CodeT5+ | 2023/05 | [CodeT5+](https://github.com/salesforce/CodeT5/tree/main/CodeT5+)     | [CodeT5+: Open Code Large Language Models for Code Understanding and Generation](https://arxiv.org/abs/2305.07922) | 0.22 - 16 | [512](https://arxiv.org/abs/2305.07922)                                                                                | BSD-3-Clause                                                                           | [Codet5+-6B](https://github.com/slai-labs/get-beam/tree/main/examples/codeT5%2B)          |

 ## Open LLM datasets for pre-training

| Name | Release Date | Paper/Blog | Dataset | Tokens (T) | License |
| --- | --- | --- | --- | --- | ---- | 
| starcoderdata | 2023/05 | [StarCoder: A State-of-the-Art LLM for Code](https://huggingface.co/blog/starcoder) | [starcoderdata](https://huggingface.co/datasets/bigcode/starcoderdata) |  0.25 | Apache 2.0 |
| RedPajama | 2023/04 | [RedPajama, a project to create leading open-source models, starts by reproducing LLaMA training dataset of over 1.2 trillion tokens](https://www.together.xyz/blog/redpajama) | [RedPajama-Data](https://github.com/togethercomputer/RedPajama-Data) | 1.2 | Apache 2.0 |

## Open LLM datasets for instruction-tuning

| Name | Release Date |  Paper/Blog | Dataset | Samples (K) | License |
| --- | --- | --- | --- | --- | ---- | 
| MPT-7B-Instruct | 2023/05 | [Introducing MPT-7B: A New Standard for Open-Source, Commercially Usable LLMs](https://www.mosaicml.com/blog/mpt-7b) | [dolly_hhrlhf](https://huggingface.co/datasets/mosaicml/dolly_hhrlhf) | 59 | CC BY-SA-3.0 |
| databricks-dolly-15k | 2023/04 | [Free Dolly: Introducing the World's First Truly Open Instruction-Tuned LLM](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm) |  [databricks-dolly-15k](https://huggingface.co/datasets/databricks/databricks-dolly-15k) | 15 |  CC BY-SA-3.0 |
| OIG (Open Instruction Generalist)   | 2023/03 | [THE OIG DATASET](https://laion.ai/blog/oig-dataset/) | [OIG](https://huggingface.co/datasets/laion/OIG) | 44,000 | Apache 2.0 |

## Open LLM datasets for alignment-tuning

| Name | Release Date |  Paper/Blog | Dataset | Samples (K) | License |
| --- | --- | --- | --- | --- | ---- |
| OpenAssistant Conversations Dataset | 2023/04 | [OpenAssistant Conversations - Democratizing Large Language Model Alignment](https://drive.google.com/file/d/10iR5hKwFqAKhL3umx8muOWSRm7hs5FqX/view) | [oasst1](https://huggingface.co/datasets/OpenAssistant/oasst1) | 161 | Apache 2.0 |

## Evals on open LLMs

- [Leaderboard by lmsys.org](https://chat.lmsys.org/?leaderboard)
- [Evals by MosaicML](https://twitter.com/jefrankle/status/1654631746506301441)
- [Holistic Evaluation of Language Models (HELM)](https://crfm.stanford.edu/helm/latest/?groups=1)
- [LLM-Leaderboard](https://github.com/LudwigStumpp/llm-leaderboard)
- [TextSynth Server Benchmarks](https://bellard.org/ts_server/)
- [Open LLM Leaderboard by Hugging Face](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)