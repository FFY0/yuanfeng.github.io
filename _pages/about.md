---
permalink: /
#title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I earned my bachelor’s degree in the School of Software Engineering at [Harbin Institute of Technology (HIT)](https://www.hit.edu.cn/) in 2022. The same year, I was admitted to the School of Computer Science and Technology at [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/) to pursue a master’s degree, and in 2024, I transitioned to the PhD program. Currently, I am a first-year Ph.D. candidate jointly supervised by Prof. [Prof. Xike Xie](http://staff.ustc.edu.cn/~xkxie/), [Prof. S. Kevin Zhou](https://scholar.google.com/citations?user=8eNm2GMAAAAJ&hl=en), and [Prof. MingJun Xiao](http://staff.ustc.edu.cn/~xiaomj/indexEN.html), and I am affiliated with the Data Darkness Lab (DDL) under the ([MIRACLE Center](https://miracle.ustc.edu.cn/main.htm)).

My research journey began with an exploration into understanding and leveraging the memory within neural networks to accomplish intriguing tasks. In addition, I am delving into the KV Cache memory mechanisms of LLMs, with the objective of unraveling their intrinsic workings and making application contributions like optimizing inference efficiency.

**Please don’t hesitate to reach out for any discussion. You can contact me via email at yfung@mail dot ustc dot edu dot cn. I am always open to engaging in intriguing research endeavors! 😊**

------

## Research Interests:

🎯 **Teaching neural networks to memorize data streams & Large-Scale Data Compression!**

1. Meta-sketch: A neural data structure for estimating item frequencies of data streams. **<span style="color:#CD5C5C;"> (CCF-A, AAAI23 Oral) [link](https://ojs.aaai.org/index.php/AAAI/article/view/25846)</span>**
2. Mayfly: a Neural Data Structure for Graph Stream Summarization. **<span style="color:#CD5C5C;"> (Top AI Conf., ICLR24 Spotlight) [link](https://openreview.net/pdf?id=n7Sr8SW4bn)</span>**
3. Learning to Sketch: A Neural Approach to Item Frequency Estimation in Streaming Data. **<span style="color:#CD5C5C;"> (CCF-A, TPAMI24) [link](https://ieeexplore.ieee.org/abstract/document/10499867/)</span>**
4. Lego Sketch: A Scalable Memory-augmented Neural Network for Sketching Data Streams. **<span style="color:#CD5C5C;"> (CCF-A, ICML25) This paper will be available soon.</span>**

🎯 **Understanding KV Cache Memory in LLMs And Compressing them!**

1. Ada-KV: Optimizing kv cache eviction by adaptive budget allocation for efficient llm inference. **(Available on [Arxiv](https://arxiv.org/abs/2407.11550))**
  
    *We introduced the first head-wise adaptive cache compression and open-sourced our code. [**CloudFlare**](https://blog.cloudflare.com/workers-ai/making-workers-ai-faster/) has integrated our Ada-KV algorithm into vLLM, providing crucial support for real-world deployment, and released a [technical report](https://arxiv.org/abs/2410.00161) with detailed evaluation. Additionally, we’ve been invited by **Huawei** and **OPPO** to share our insights with their teams, aiding in practical applications!  We also actively collaborating with the community, hoping to assist future research in this area. Explore our [github repo](https://github.com/FFY0/AdaKV) and feel free to raise issues or contact us via email for any inquiries!*

2. Identify Critical KV Cache in LLM Inference from an Output Perturbation Perspective. **(Available on [Arxiv](https://arxiv.org/abs/2502.03805v1))**
    *We applied perturbation analysis to show that KV cache eviction methods can be improved by integrating information from the value cache and pretrained parameters. Our evaluation in challenging context-only compression settings extends these findings to broader real-world applications, such as prefix context compression and multi-turn dialogues. We believe this work offers a novel theoretical perspective on the importance of KV cache, emphasizing the need to consider a broader range of information, including pretrained parameters in LLMs. If you would like to discuss our work further, please feel free to contact us via email.*

🎯 **RAG in LLMs.**

I am also collaborating with other researchers on LLM RAG, focusing on deployment in practical applications.

1. FRAG: A Flexible Modular Framework for Retrieval-Augmented Generation based on Knowledge Graphs **<span style="color:#CD5C5C;"> (CCF-A, ACL25 Findings) [link](https://arxiv.org/abs/2501.09957)</span>**
2. Path Pooling: Training-Free Structure Enhancement for Efficient Knowledge Graph Retrieval-Augmented Generation. **(Available on [Arxiv](https://arxiv.org/abs/2503.05203))**

🎯 **Broader Research Horizons.**

1. Interpretable Memory in LLMs
2. Multimodal Large Models
3. Test-time Scaling Laws / Reasoning Model

------

## Selected Publications

For full publications, please refer to my  [google scholar](https://scholar.google.com/citations?user=d2ESOiIAAAAJ&hl=en).

1.  <span style="color:#BEBEBE;">**[Arxiv]**</span> **Yuan Feng**, Junlin Lv, Yukun Cao, Xike Xie, and S. Kevin Zhou. "Ada-kv: Optimizing kv cache eviction by adaptive budget allocation for efficient llm inference." arXiv preprint arXiv:2407.11550 (2024) ([paper](https://arxiv.org/abs/2407.11550), [code](https://github.com/FFY0/AdaKV)).

2.  <span style="color:#BEBEBE;">**[Arxiv]**</span> **Yuan Feng**, Junlin Lv, Yukun Cao, Xike Xie, and S. Kevin Zhou. "Identify Critical KV Cache in LLM Inference from an Output Perturbation Perspective." arXiv preprint arXiv:2407.11550 (2024) ([paper](https://arxiv.org/abs/2502.03805v1), [code](https://github.com/FFY0/AdaKV-in-NVIDIA-kvpress/tree/criticalkv)).

3. <span style="color:#5B8C5A;">**[ICASSP25 Poster Paper (CCF-B)]**</span> Junlin Lv, **Yuan Feng**, Xike Xie, Xin Jia, Qirong Peng, and Guiming Xie. "CritiPrefill: A Segment-wise Criticality-based Approach for Prefilling Acceleration in LLMs." ICASSP 2025 - 2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) ([paper](https://ieeexplore.ieee.org/abstract/document/10887916), [code](https://github.com/66RING/CritiPrefill)).

4. <span style="color:#CD5C5C;"> **[ICML25 Poster Paper (CCF-A)]**</span>  **Yuan Feng**, Yukun Cao, Wang Hairu, Xike Xie, and S. Kevin Zhou. "Lego Sketch: A Scalable Memory-augmented Neural Network for Sketching Data Streams. In The 42nd International Conference on Machine Learning, 2025 Poster (This paper will be available soon., [code](https://github.com/FFY0/LegoSketch_ICML))

5. <span style="color:#CD5C5C;"> **[ICLR24 Spotlight Paper (Top AI Conf.)]**</span>  **Yuan Feng**, Yukun Cao, Wang Hairu, Xike Xie, and S. Kevin Zhou. "Mayfly: a Neural Data Structure for Graph Stream Summarization." In The Twelfth International Conference on Learning Representations, 2024 Spotlight.([paper](https://openreview.net/pdf?id=n7Sr8SW4bn), [code](https://openreview.net/attachment?id=n7Sr8SW4bn&name=supplementary_material))

6.  <span style="color:#CD5C5C;"> **[TPAMI24 Regular Paper (CCF-A)]**</span> Yukun Cao, **Yuan Feng<sup>Co-First</sup>**, Hairu Wang, Xike Xie, and S. Kevin Zhou. "Learning to Sketch: A Neural Approach to Item Frequency Estimation in Streaming Data." IEEE Transactions on Pattern Analysis and Machine Intelligence, 2024 ([paper](https://ieeexplore.ieee.org/abstract/document/10499867/), [code](https://github.com/FFY0/MetaSketch_TPAMI)).

7. <span style="color:#CD5C5C;"> **[AAAI23 Oral Paper (CCF-A)]**</span>  Yukun Cao, **Yuan Feng**, and Xike Xie. "Meta-sketch: A neural data structure for estimating item frequencies of data streams." In Proceedings of the AAAI Conference on Artificial Intelligence, 2023 Oral. ([paper](https://ojs.aaai.org/index.php/AAAI/article/view/25846), [code](https://github.com/FFY0/meta-sketch))

------

## Selected Honors

* 2024 **PhD's First Prize Scholarship** in USTC

* 2022/2023 two times **Master’s First Prize Scholarship** in USTC

* 2021 **Outstanding Student Award** in HIT

* 2020/2021 two times **National Scholarship** in HIT

------

## Academic Service

Reviewer

* NeurIPS, 2024&2025
* ICLR, 2024&2025
* ICDE, 2024&2025

## Educations

* 2024.09 - , PhD candidate in Computer Science and Technology, University of Science and Technology of China (USTC).

* 2022.09 - 2024.06, Master in Computer Science and Technology, University of Science and Technology of China (USTC).

* 2018.09 - 2022.06, Bachelor in Software Engineering, Harbin Institute of Technology (HIT).
