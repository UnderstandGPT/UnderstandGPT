# Contribution Guidelines
All content contributed should first be reviewed by GPT4 to ensure it meets our content guidelines and its easy to understand for everyone. When submitting a pull request, the response from GPT4 must be included in the PR for it to be approved for reviewal. You must be able to get it to score 8/10 or higher for jargon, and a 7 for all other critera for the content to be reviewed.


## GPT4 PROMPT:

```
Read the provided text and provide constructive criticism on the content to make sure it follows our writing prompt. Do not rewrite the content, only provide feedback. Provide a score from 1 to 10 for each category to show how well the writing adheres to the writing guidelines.

WRITING PROMPT:
No Jargon: The language is kept simple to understand so anyone will be able to read and comprehend it.

Expository: The main objective of this writing style is to explain, describe, and provide readers with a clear understanding of the subject.

Educational: The text is written with the intent of educating the reader about a complex topic, breaking down technical details into easily understandable information. It uses clear and concise language, avoids jargon where possible, and gives explanations where necessary.

Structured: The content is well-organized, with each paragraph dedicated to a different aspect of LLMs, making it easier for readers to follow and understand.

TEXT:
(Your text here)
```

## Reviewing GPT4's feedback and Updating.
It will provide feedback about any issues it has with our provided guidelines. Make any adjustments to the content to meet its requirements until it gives a favorable answer. Particularly make sure the score for jargon is as at an 8 or higher.

## Example:
```
What are Large Language Models (LLMs)?

Large Language Models are machine learning models trained to understand and generate human-like text. They are a type of transformer-based model that is designed to predict the next word in a sentence, given the preceding context, also known as autoregressive models. Notable examples include GPT-3, GPT-4, and similar transformer models.
```
### GPT Review Comments
```
No Jargon: 6/10
The text does a good job of maintaining simplicity to some extent. However, there are several instances where jargon is used without providing enough context or explanation, such as 'transformer-based model', 'autoregressive models', and the reference to 'GPT-3, GPT-4'. For a non-technical reader, these terms could be confusing. More explanation or definition of these terms would help with comprehensibility.

Expository: 7/10
The text gives a brief overview of Large Language Models (LLMs), including a basic definition and the idea behind them. It could, however, delve deeper into the subject to provide readers with a more comprehensive understanding. The role and significance of LLMs, as well as their functioning, could be expanded upon.

Educational: 7/10
The text does provide some educational value as it introduces the reader to LLMs and their basic functionality. However, it falls short in fully educating the reader due to the lack of explanation for the technical terms used. Clear definitions or analogies could improve this score.

Structured: 9/10
The content is well-structured. It introduces the concept of LLMs, then discusses what they do and gives examples. To further improve the structure, the writer could include sub-sections that provide more detail on the various aspects of LLMs. This would help guide the reader through the complex topic.
```
### Updated Text
```
## What's a LLM?

Large Language Models (LLMs) are a type of program taught to understand text and respond back as a human would. They learn by being fed large amounts of text and they try to predict what the answer will be based on the provided information. The model's ability to understand and respond correctly is largely dependent on what information was used to teach it and how big the model is.

Generally, the larger models, the easier it is for it to learn new concepts, but requires a more powerful computer to run which can be a limitation when running on a desktop computer.  There are many different use cases for having a technology that can understand text and provide a response.

## Use Cases
With LLMs being a newer technology, new ideas are tested every day to learn what's possible. There are many possibilities of what it can do that are largely unexplored. Listed below are a few examples of what it could be used for as of today.

**Writing Code**

Give the LLM a short text description of what you want to be done and in what programing language and it will write it for you. Currently, there are limits on how much information it can read and write at once, so while it can handle writing small functions very well, it struggles when it comes to piecing multiple parts of code together.

**Summarizing Text**

One of the skills LLM's can do best. Provide it some text, and ask it to rewrite it in a particular style or format and it will give you an answer. These docs were written using ChatGPT as an editor to make sure the content is clear!

**Question Answering**

LLM's have a broad amount of general knowledge and can provide clear and concise answers about lots of topics. For many questions require domain-specific knowledge or recent information, because they only know information based on what they were taught.

## Running a LLM Locally
While using services like ChatGPT can be convenient and give good answers, there are privacy concerns. For many use cases, you do not want to be giving a company your private information such as medical records, or a company's intellectual property. If you are running the model locally, that means you are able to maintain control of your data without sharing it with anyone else.
```
### Updated Review Comments
```
No Jargon: 8/10 - The text does a good job of explaining technical terms related to LLMs, such as describing how they learn and respond. However, there are a couple instances where more clarification could be beneficial. For example, the phrase "running the model locally" could be confusing to non-technical readers.

Expository: 9/10 - The text does well in explaining what a Large Language Model is, the potential use cases and the concept of running a LLM locally. The content flows well and builds upon previous points.

Educational: 9/10 - The text effectively educates the reader about the subject. It explains the nature of LLMs, their limitations, uses, and potential concerns like privacy. It does this in a structured way that's easy to follow, using clear language throughout.

Structured: 8/10 - The text is organized into different sections for ease of understanding. However, the paragraph on the size of LLMs could be separated into two paragraphs, one discussing the benefits of larger models and another discussing the limitations, for even clearer organization.

General Feedback: There is room for improvement with some terms being better explained to ensure full understanding for all readers. Additionally, a clearer structure in some areas would benefit the reader's comprehension of the content. Overall, however, the piece does a good job of meeting the goals of the writing prompt.
``