---
layout: cost-desiderata-agent-benchmarks
---

## Abstract

With the impressive capabilities of Large Language Models (LLMs), there is an emerging trend of utilizing LLMs to assist people in automatically completing daily tasks, known as "LLM-powered Agents as Assistants." However, a frequently overlooked aspect in the benchmark design and methodological research of LLM-powered Agents is the concept of *cost* incurred by the entire Agent system, which impedes its implementation in practice. In this work, we inspect the three components in an Agent system: the human (user), the machine (LLM-powered agents), and the world (interactive environment), and categorize different types of costs in an Agent system revolving around these roles. Existing benchmarks and techniques of LLM-powered agents lack consideration for one or more types of costs in our categorization.

To further demonstrate the significance of *cost* for LLM-powered agents, we constructed C-WebShop on top of the existing online shopping enviroment for LLM-powered agents, WebShop. The design of C-WebShop integrates the costs from the agent itself, the user to be assisted, and the environment to be interacted with. In C-WebShop, the agent's own monetary and time expenditures are measured and meant to be minimized as well. When assisting in shopping decisions, the agent needs to analyze the user's initial profile, tracking and inferring a series of shopping instructions to make the best choices. In the meantime, the search results in C-WebShop constantly evolve with the historical click actions because of a reranking sorting mechanism. Under the influence of human intentions (cost from the user), self expenditures (cost from the agent), and world changes (cost from the interactive environment), existing LLM-powered agent techniques exhibit suboptimal performance in C-WebShop. This indicates a significant potential for improvement in LLM-powered agent technology under cost-sensitive benchmarking scenarios.

## Why Cost? And Cost Categories

TODO

## C-WebShop

Motivated by the cost desiderata and categories, we integrate several types of cost that agent benchmarks should take care of into the famous [WebShop](https://webshop-pnlp.github.io/) environment and construct C-WebShop.

Try out C-WebShop at the live site [here]()!

TODO

## Performance of Existing Techniques

TODO

## LLM-Powered Agents Go Realistic

TODO

## Authors

This project is co-led by [Zonghan Yang](https://minicheshire.github.io), [An Liu](https://github.com/xxmlala), and [Zijun Liu](https://github.com/BBQGOD). This project is not possible without the following members (in alphabetical order):
- **Graduate students and Postdocs:** Zhicheng Guo, Yile Wang, Zeyuan Yang.
- **Undergraduate students:** Xinrui Chen, Qingyuan Hu, Kaiming Liu, Fangzhou Xiong, Zhenhe Zhang.
- **Additional Acknowledgements:** Chi Chen, Sijie Cheng, Fuwen Luo, Ziyue Wang, Siyu Wang, Xiaolong Wang.

This project is advised by [Peng Li](https://www.lpeng.net/) and [Yang Liu](https://nlp.csai.tsinghua.edu.cn/~ly). 