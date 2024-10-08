---
title: "AI x Cybersecurity Resources"
excerpt_separator: "<!--more-->"
categories:
  - Blog
  - Resources Directory
tags:
  - AI
  - cybersecurity
  - information security
  - hacking
  - prompt injection
  - language models
  - CTF
  - AI alignment
toc: true
toc_sticky: true
---

This page is basically a [directory](https://jackyan.com/blog/2023/09/bring-back-the-human-curated-web-directory/) of links.<!--more--> I have a hodgepodge of useful bookmarks accumulated over time in a yet-to-be-well-organized bookmark directory and I wanted to group up a few of them for specific topics (this page being for links related to some stuff at the intersection of cybersecurity and AI). I figured I might as well post it here for my own reference and so others might get use from it! These links are not necessarily in any particular order, though I’ll try to provide a brief description of each.

---
---

<p>&nbsp;</p>
## Prompt Attack challenge/game:
### [GPT Prompt Attack ⛳](https://gpa.43z.one/)
![Screenshot of website](/assets/images/cyber_ai_images/gptattack.png)
* If you can match or beat my best score of 387 (sum of the character count for my best solutions to all 20 levels is 387), I have a prize for you. And major respect. But You have to show me your solutions for the prize!
* Honorable mention, here is [a similar game from Lakera](https://gandalf.lakera.ai/gandalf)

<p>&nbsp;</p>
## Articles & research papers:
### [Backdooring Instruction-Tuned Large Language Models with Virtual Prompt Injection](https://poison-llm.github.io)
* Discusses Virtual Prompt Injection (VPI), a technique allowing attackers to covertly influence large language models (LLMs) by injecting biased prompts into training data.
* Shows that with minimal poisoned data, attackers can cause significant shifts in model responses, such as increasing negative sentiment in responses about public figures.
* Notes that you can mitigate these risks with rigorous data integrity checks and methods like data filtering.

### [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://llm-attacks.org)
* Discusses automated adversarial attacks on aligned large language models like ChatGPT and Google Bard.
* Specific sequences can be crafted to bypass content filters and induce harmful responses.
    * These attacks, which can be automatically generated and are transferable across different models, raise significant concerns about the long-term safety and robustness of LLMs.

### [The Real-World Impact of AI on Cybersecurity Professionals (ISC2)](https://www.isc2.org/Insights/2024/02/The-Real-World-Impact-of-AI-on-Cybersecurity-Professionals)
* Some interesting survey data.
* How AI is transforming cybersecurity roles.
    * (Benefits efficiency and risks amplifying cyber threats)

### [Capturing the Flag with GPT-4](https://micahflee.com/2023/04/capturing-the-flag-with-gpt-4/)
* A very interesting article about a guy (Michah Lee) who did some CTF hacking challenges at BSides SF 2023 with GPT-4 assitance (to fantastic effect).
* He walks you through his process with screenshots and all.

<p>&nbsp;</p>
