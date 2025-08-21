---
permalink: /
#title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I earned my bachelor’s degree at HIT in 2022. In the same year, I joined the School of Computer Science at USTC for my master’s degree and transitioned to the PhD program in 2024. Currently, I am a second-year Ph.D. candidate jointly supervised by Prof. [Prof. Xike Xie](http://staff.ustc.edu.cn/~xkxie/) and [Prof. S. Kevin Zhou](https://scholar.google.com/citations?user=8eNm2GMAAAAJ&hl=en).

My research journey started with exploring neural networks' memory to tackle interesting tasks. Additionally, I am delving into the KV Cache memory mechanisms of LLMs to unravel their workings and contribute to applications like optimizing inference efficiency.

Please don’t hesitate to reach out for any discussion. You can contact me via Email: yfung@mail dot ustc dot edu dot cn or WeChat: movingffy. I am always open to engaging in intriguing research endeavors! 😊

------

## Research Interests:

🎯 **Teaching NNs to memorize data streams & Learnable Large-Scale Data Compression.**

1. Meta-sketch: A neural data structure for estimating item frequencies of data streams. **<span > AAAI23 Oral [link](https://ojs.aaai.org/index.php/AAAI/article/view/25846)</span>**
2. Mayfly: a Neural Data Structure for Graph Stream Summarization. **<span >  ICLR24 Spotlight [link](https://openreview.net/pdf?id=n7Sr8SW4bn)</span>**
3. Learning to Sketch: A Neural Approach to Item Frequency Estimation in Streaming Data. **<span>TPAMI24 [link](https://ieeexplore.ieee.org/abstract/document/10499867/) </span>**
4. Lego Sketch: A Scalable Memory-augmented Neural Network for Sketching Data Streams. **<span >  ICML25 [link](https://openreview.net/forum?id=GPSmbdTZBm) </span>**

🎯 **LLM Efficiency.**

1. Ada-KV: Optimizing kv cache eviction by adaptive budget allocation for efficient llm inference. **[Arxiv](https://arxiv.org/abs/2407.11550)**
  
    *We introduced the first head-wise adaptive cache compression method and open-sourced our code. Through active collaboration with the community, we have helped drive progress in head-wise cache compression, enabling many follow-up works. Explore our [github repo](https://github.com/FFY0/AdaKV)*

2. Identify Critical KV Cache in LLM Inference from an Output Perturbation Perspective. **[Arxiv](https://arxiv.org/abs/2502.03805v1)**

    *We present the first perturbation-based analysis showing that KV cache eviction improves when integrating value-cache information with LLM pretrained parameters. We believe this work offes a novel theoretical perspective on KV cache importance estimation.*

3. SkewRoute: Training-Free LLM Routing for Knowledge Graph Retrieval-Augmented Generation via Score Skewness.  **EMNLP25 findings [link](https://arxiv.org/pdf/2505.23841)**

    *We propose the first LLM routing method for KG-RAG, based on the observation of a strong correlation between query difficulty and the skewness of the RAG retrieval score distribution.*

🎯 **RAG in LLMs.**

I am also collaborating with other researchers on LLM RAG, focusing on deployment in practical applications.

1. FRAG: A Flexible Modular Framework for Retrieval-Augmented Generation based on Knowledge Graphs **<span>  ACL25 findings [link](https://arxiv.org/abs/2501.09957)</span>**
2. Path Pooling: Training-Free Structure Enhancement for Efficient Knowledge Graph Retrieval-Augmented Generation. **[Arxiv](https://arxiv.org/abs/2503.05203)**

🎯 **Broader Research Horizons.**

1. Interpretable Memory in LLMs
2. Multimodal Large Models
3. Test-time Scaling Laws / Reasoning Model

------

## Selected Publications

For full publications, please refer to my  [google scholar](https://scholar.google.com/citations?user=d2ESOiIAAAAJ&hl=en).

1. **Yuan Feng**, Junlin Lv, Yukun Cao, Xike Xie, and S. Kevin Zhou. "Ada-kv: Optimizing kv cache eviction by adaptive budget allocation for efficient llm inference."  (ArXiv [paper](https://arxiv.org/abs/2407.11550), [code](https://github.com/FFY0/AdaKV)).

2. **Yuan Feng**, Junlin Lv, Yukun Cao, Xike Xie, and S. Kevin Zhou. "Identify Critical KV Cache in LLM Inference from an Output Perturbation Perspective." (ArXiv [paper](https://arxiv.org/abs/2502.03805v1), [code](https://github.com/FFY0/AdaKV-in-NVIDIA-kvpress/tree/criticalkv)).

3. Wang Hairu, **Yuan Feng<sup>Co-First</sup>**, Yukun Cao, Xike Xie, and S. Kevin Zhou. "SkewRoute: Training-Free LLM Routing for Knowledge Graph Retrieval-Augmented Generation via Score Skewness" (EMNLP 2025 findings [paper](https://arxiv.org/pdf/2505.23841?), the code will be available soon.)

4. Junlin Lv, **Yuan Feng**, Xike Xie, Xin Jia, Qirong Peng, and Guiming Xie. "CritiPrefill: A Segment-wise Criticality-based Approach for Prefilling Acceleration in LLMs." (ICASSP 2025 [paper](https://ieeexplore.ieee.org/abstract/document/10887916), [code](https://github.com/66RING/CritiPrefill)).

5. **Yuan Feng**, Yukun Cao, Wang Hairu, Xike Xie, and S. Kevin Zhou. "Lego Sketch: A Scalable Memory-augmented Neural Network for Sketching Data Streams. (ICML 2025 Poster [paper](https://openreview.net/forum?id=GPSmbdTZBm), [code](https://github.com/FFY0/LegoSketch_ICML))

6. **Yuan Feng**, Yukun Cao, Wang Hairu, Xike Xie, and S. Kevin Zhou. "Mayfly: a Neural Data Structure for Graph Stream Summarization." (ICLR 2024 Spotlight [paper](https://openreview.net/pdf?id=n7Sr8SW4bn), [code](https://openreview.net/attachment?id=n7Sr8SW4bn&name=supplementary_material))

7. Yukun Cao, **Yuan Feng<sup>Co-First</sup>**, Hairu Wang, Xike Xie, and S. Kevin Zhou. "Learning to Sketch: A Neural Approach to Item Frequency Estimation in Streaming Data." (TPAMI 2024 [paper](https://ieeexplore.ieee.org/abstract/document/10499867/), [code](https://github.com/FFY0/MetaSketch_TPAMI)).

8. Yukun Cao, **Yuan Feng**, and Xike Xie. "Meta-sketch: A neural data structure for estimating item frequencies of data streams." (AAAI 2023 Oral [paper](https://ojs.aaai.org/index.php/AAAI/article/view/25846), [code](https://github.com/FFY0/meta-sketch))

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
