---
title: "Language Model Resources"
excerpt_separator: "<!--more-->"
categories:
  - Blog
  - Resources Directory
tags:
  - language models
  - LLMs
  - LMs
  - ChatGPT
  - Artificial Intelligence
  - AI
  - machine learning
  - ML
  - deep learning
  - RLHF
  - neural network
  - computer science
  - programming
  - nonprofit
  - open source
  - AI alignment
  - transformers
  - research
  - vectors
  - vector databases
---

This page is basically a [directory](https://jackyan.com/blog/2023/09/bring-back-the-human-curated-web-directory/) of links.<!--more--> I have a hodgepodge of useful bookmarks accumulated over time in a yet-to-be-well-organized bookmark directory and I wanted to group up a few of them for specific topics (this page being for links related to language model stuff). I figured I might as well post it here for my own reference and so others might get use from it! These links are not necessarily in any particular order, but I will try to provide a brief description each.

I might add a table of contents for these link dump pages at a later date because some of them are pretty long... but for now if anyone is reading this, command/crtl+f will have to suffice.

<p>&nbsp;</p>
# Intro to Language Models (LMs):
(Two fantastic and comprehensive articles:)

## [What We Know About LLMs (Primer)](https://willthompson.name/what-we-know-about-llms-primer#block-85b3ec4df96e4c878c1a6db6357269a2)
* Table of contents:
![primer table of contents](/assets/images/lm_resources/lm_primer.png)

## [Getting Started with Large Language Models: Key Things to Know](https://flyte.org/blog/getting-started-with-large-language-models-key-things-to-know)
* Table of contents:  
![primer table of contents](/assets/images/lm_resources/lm_keythings.png)

<p>&nbsp;</p>
# Models, So Many Models:
## [The Rise and Rise of A.I. Large Language Models](https://informationisbeautiful.net/visualizations/the-rise-of-generative-ai-large-language-models-llms-like-chatgpt/)
Screenshot of the chart, though you should really ^go check it out^:
![rise of llms chart](/assets/images/lm_resources/rise_of_llms.png)
* Very cool chart visualizing data representing the explosion of various language models over the last 4 years or so.
* An article below the chart outlines a very interesting data story of the models developing over time.

## [LMSYS Chatbot Arena Leaderboard](https://huggingface.co/spaces/lmsys/chatbot-arena-leaderboard)
* This is a crowdsourced open platform for LLM evals, and rankings based on performance.

## [LLM Explorer](https://llm.extractum.io/)
* Really nicely organized lists, rankings, and categorizations of LLMs.

## [AI / ML / LLM / Transformer Models Timeline and List](https://ai.v-gar.de/ml/transformer/timeline/)
* "This is a collection of important papers in the area of Large Language Models and Transformer Models. It focuses on recent development, especially from mid-2022 onwards"
* Really cool graph/timeline!
![rise of llms chart](/assets/images/lm_resources/rise_of_llms.png)

<p>&nbsp;</p>
# LMs Impact on Programming Paradigms:
## [Software 2.0](https://karpathy.medium.com/software-2-0-a64152b37c35)
Software 1.0 vs 2.0 program space diagram:
![1.0 vs 2.0 program space diagram](/assets/images/lm_resources/soft2.png)
* This sensational article written by Andrej Karpathy in 2017 gets its own entire section on this blog post because of how transformative/important the concepts in it are. Some won't understand all of it, but all will understand some of it. Worth a read. My summary won't do it justice, but here:
* The article argues that neural networks signify a transformative shift from traditional "Software 1.0" to "Software 2.0."
    * Software 1.0 :  Programmers write explicit instructions in code.
    * Software 2.0 :  relies on neural networks where behavior is defined by training on datasets rather than direct programming.
* This shift simplifies certain tasks, such as visual recognition and speech synthesis, by using neural networks to optimize and learn from large datasets instead of manually coding complex rules.
* Software 2.0 allows for more efficient and adaptable systems but comes with challenges like interpretability and vulnerability to biases. The article envisions that as Software 2.0 continues to evolve, it will impact various fields and require new development tools and practices tailored to its paradigm.  

* Final shoutout to Andrej for this fantastic 1 hour video [Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g)

<p>&nbsp;</p>
# Deeper into the LM Landscape
## [State of AI Report 2023](https://nathanbenaich.substack.com/p/welcome-to-the-state-of-ai-report)
* Nathan Beniach's annual "State of AI" report is a comprehensive analysis of the current landscape in artificial intelligence.
* Covers key advancements, industry trends, and emerging technologies in AI.
* Insights on AI research, market dynamics, policy implications, and major players in the field.
* Note: If you want to try to somehow keep up with the crazy pace of the LM/AI space, Nathan also puts out a [monthly report](https://nathanbenaich.substack.com/) on his substack.
    * Similarly, to keep track of the "bleeding edge", you might want to check out [bleeding edge](https://bleedingedge.ai/) for "a feed of noteworthy developments in AI".

## [AI Canon](https://a16z.com/ai-canon/)
* This article provides a curated collection of resources for understanding modern AI.
* Includes foundational papers, blog posts, courses, and guides, focusing on the transformative impact of technologies like transformers and latent diffusion models.
* Starts with overview of these technologies, progresses through technical learning resources and practical guides for building with large language models (LLMs), and concludes with landmark research, notably the 2017 paper "[Attention is All You Need](https://arxiv.org/pdf/1706.03762)" that introduced transformer models.

## [# (Almost) Everything I know about LLMs](https://barryz-architecture-of-agentic-llm.notion.site/Almost-Everything-I-know-about-LLMs-d117ca25d4624199be07e9b0ab356a77#5a7b1625019f42ae9bac58207b4f6200)
* This article provides a comprehensive overview of Large Language Models (LLMs), focusing on their components, data flow, and evaluation methods.
* Emphasizes the importance of prompting techniques and the role of user feedback in improving model performance.
* Highlights various tools and techniques for fine-tuning and augmenting LLMs, aiming to offer a foundational understanding for those interested in the field.

## [Large language model Wikipedia page](https://en.wikipedia.org/wiki/Large_language_model)
* Very informative and consistently updated. It seems to be updated almost daily!

<p>&nbsp;</p>
# Research Papers
## [“Attention is All You Need” Summary](https://medium.com/@dminhk/attention-is-all-you-need-summary-6f0437e63a91)
* A summary of the landmark 2017 paper "[Attention Is All You Need](https://arxiv.org/pdf/1706.03762)"

## [Reflexion: Language Agents with Verbal Reinforcement Learning](https://ar5iv.labs.arxiv.org/html/2303.11366)
* Very interesting paper (published February 2024) on a new reinforcement learning method (potentially much more efficient than the human labor intensive RLHF (reinforcement learning from human feedback) standard method).
* From the abstract:
>"We propose Reflexion, a novel framework to reinforce language agents not by updating weights, but instead through linguistic feedback. Concretely, Reflexion agents verbally reflect on task feedback signals, then maintain their own reflective text in an episodic memory buffer to induce better decision-making in subsequent trials. Reflexion is flexible enough to incorporate various types (scalar values or free-form language) and sources (external or internally simulated) of feedback signals, and obtains significant improvements over a baseline agent across diverse tasks (sequential decision-making, coding, language reasoning). For example, Reflexion achieves a 91% pass@1 accuracy on the HumanEval coding benchmark, surpassing the previous state-of-the-art GPT-4 that achieves 80%."

<p>&nbsp;</p>
# Deeper Technical Understanding:
## [What Is ChatGPT Doing... and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)
* This article provides a high-level overview of how transformer based large language models generate human-like text by predicting the next word based on probabilities derived from vast amounts of text data.
* Explains the importance of randomness in producing creative and varied outputs and touches on the underlying neural network architecture and training process.
* Explains concepts like probability-based text generation, neural networks, and training processes in a way that is accessible to readers with a basic understanding of AI and machine learning.

## [Transformers from Scratch](https://e2eml.school/transformers.html)
* Transformer architecture is the basis for the largest and most capable language models as of August, 2024.
* A transformer is a deep learning architecture developed by researchers at Google and based on the multi-head attention mechanism, proposed in a 2017 paper "[Attention Is All You Need](https://medium.com/@dminhk/attention-is-all-you-need-summary-6f0437e63a91)"
* *WARNING*: This is a deep dive on transformers. Like the title implies, this dive is truly deep!

## [Scaling ChatGPT: Five Real-World Engineering Challenges](https://newsletter.pragmaticengineer.com/p/scaling-chatgpt)
* The (scaling) challenges discussed within:
    1. KV Cache & GPU RAM
    2. Optimizing batch size
    3. Finding the right metrics to measure
    4. Finding GPUs wherever they are
    5. Inability to autoscale

## [Vector Databases A Technical Primer](https://tge-data-web.nyc3.digitaloceanspaces.com/docs/Vector%20Databases%20-%20A%20Technical%20Primer.pdf)
* This is a pdf slide presentation for a Technical Primer on Vector Databases.
* As of August, 2024 the state of the art LLM tools largely are integrated with RAG (retrieval-augmented generation) systems. In this system, queries and documents are stored as vectors, and these vectors are stored in vector databases.

<p>&nbsp;</p>
# Other Random LM Resources:
## [bleeding edge](https://bleedingedge.ai/)
* "a feed of noteworthy developments in AI"
* This site has very cool/clean interactive timeline for said developments.

## [LAION (Large-scale Artificial Intelligence Open Network)](https://laion.ai/)
* LAION is a nonprofit, open source organization providing datasets, tools and models for machine learning research.
* Provides large, useful datasets!

## [EleutherAI](https://www.eleuther.ai/)
* EleutherAI is a nonprofit, open source AI research lab that focuses on interpretability and alignment of large models.
* Provides models, codebases, datasets, and lots of research done in the open!

## [LLM failure archive (ChatGPT and beyond)](https://github.com/giuven95/chatgpt-failures)
* An interesting and useful GitHub.
* From the README:
>A repo containing failure cases for ChatGPT and similar models, with the purpose of further study. I think it could be useful for:
    * comparison with other models
    * creation of synthetic data for testing and/or training

<p>&nbsp;</p>
