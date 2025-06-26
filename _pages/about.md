---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Computer Science PhD candidate at University of Electronic Science and Technology of China (UESTC). I obtained my master's degree in Software Engineering at Guangxi Normal University (GXNU) in 2023 under the supervision of <a href="https://scholar.google.com/citations?user=-bk1CrcAAAAJ"> Prof.Xiaofeng Zhu</a>. Before that, received my bachelor's degree in Applied Statistics at Yulin Normal University in 2020.

My research interest includes prompt learning, LLMs, VLMs, and graph representation learning.

*During my master's studies, I focused on efficient learning on graph data, particularly in few-shot scenarios (IJCAI 2022 and AAAI 2024). In the first year of my PhD, I became interested in new paradigms addressing the limitations of traditional few-shot learning, such as prompt learning (ACM-MM 2024 and one paper under review), which adapts powerful pretrained models like CLIP by tuning the input. However, with the rapid advancement of generative capabilities in large models, many conventional few-shot methods have become less effective. As a result, I have shifted my focus to exploring and leveraging the generative power of large models (ICML 2025 and one paper under review). Looking ahead, starting in 2026, I plan to apply these capabilities to AI in healthcare, aiming not merely to improve benchmarks in NLP and CV, but to address real-world clinical challenges by leveraging existing methods. If you are interested in me, please contact **wkzongqianwu@gmail.com**.*

<span style="color: #00f;"> *(CN: 在我的硕士阶段，我主要研究图数据上的高效学习，尤其关注小样本学习场景（相关成果发表于 IJCAI 2022 和 AAAI 2024）。在博士一年级期间，我开始关注一些突破传统小样本学习局限的新范式，例如提示学习（相关成果发表于 ACM-MM 2024，另有一篇论文在审），该方法通过调节输入来适配像 CLIP 这样强大的预训练模型。然而，随着近年来大模型生成能力的快速发展，许多传统的小样本学习方法变得不再适用。因此，我将研究重心转向了对大模型生成能力的深入探索与利用（相关成果发表于 ICML 2025，另有一篇论文在审）。展望未来，从2026年开始，我计划将这些生成能力应用于AI医疗领域。不仅仅追求像 NLP 和 CV 领域中的性能提升，而是更多致力于通过已有方法解决实际的临床问题和医疗挑战。)* </span>



# 📖 Educations
- *2024.10 - 2025.10 (**Visiting PhD**):* SUTD <img src="images/SUTD.png" alt="11" style="width: 30px; height: 30px;" />, Guiding Instructor: <a href="https://scholar.google.com/citations?user=KomQOFkAAAAJ"> Prof.Lei Feng</a>.
- *2023.09 - Present (**PhD**):* UESTC <img src="images/UESTC.png" alt="11" style="width: 30px; height: 30px;" />, Guiding Instructor: <a href="https://scholar.google.com/citations?user=-bk1CrcAAAAJ"> Prof.Xiaofeng Zhu</a>, Team Instructors: <a href="https://scholar.google.com/citations?hl=zh-CN&user=krryaDkAAAAJ"> Prof.Heng Tao Shen</a>. 
- *2020.09 - 2023.06 (**Master**):* Guangxi Normal University <img src="images/GXNU.png" alt="11" style="width: 30px; height: 30px;" />, Guiding Instructor: <a href="https://scholar.google.com/citations?user=-bk1CrcAAAAJ"> Prof.Xiaofeng Zhu</a>, Team Instructors: <a href="https://scholar.google.com/citations?hl=zh-CN&user=heE6vKAAAAAJ"> Prof.Shichao Zhang</a>. 
- *2016.09 - 2020.06 (**Bachelor**):* Yulin Normal University <img src="images/YLNU.png" alt="11" style="width: 30px; height: 30px;" />, Applied Statistics. 



# 🔥 News
- *2025.06*: &nbsp;🎉🎉 One paper accepted by IPM!
- *2025.05*: &nbsp;🎉🎉 One paper accepted by ICML 2025!
- *2024.10*: &nbsp;⛄⛄ I will be going to SUTD in Singapore for a visiting PhD program.
- *2024.07*: &nbsp;🎉🎉 One paper accepted by ACM Multimedia 2024!
- *2024.05*: &nbsp;🎉🎉 One paper accepted by KBS!
- *2023.11*: &nbsp;🎉🎉 One paper accepted by AAAI 2024!
- *2023.09*: &nbsp;⛄⛄ I am going to UESTC in Chengdu to pursue a doctoral degree.
- *2023.06*: &nbsp;⛄⛄ Defend my master's dissertation.


# 📝 Publications (partial)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/st-cot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rethinking Chain-of-Thought from the Perspective of Self-Training](https://arxiv.org/pdf/2412.10827)  

🍉&nbsp; [**Code**](https://github.com/zongqianwu/ST-COT)

**Zongqian Wu**, Baoduo Xu, Ruochen Cui, Mengmeng Zhan, Xiaofeng Zhu, Lei Feng

- Chain-of-thought (CoT) reasoning has emerged as an effective approach for activating latent capabilities in LLMs. We observe that CoT shares significant similarities with self-training in terms of their learning processes. Motivated by these parallels, this paper explores the underlying relationship between CoT and self-training, demonstrating how insights from self-training can enhance CoT performance.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Multimedia 2024</div><img src='images/AMMPL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adaptive Multi-Modality Prompt Learning](https://arxiv.org/pdf/2312.00823.pdf) 

**Zongqian Wu**, Yujing Liu, Mengmeng Zhan, Ping Hu, Xiaofeng Zhu

- This paper introduces multi-modality prompt learning to address limitations in current methods, enhancing generalization by considering the impact of meaningless patches in images and simultaneously addressing in-sample and out-of-sample generalization.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/KD-FSNC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Self-training based Few-shot Node Classification by Knowledge Distillation](https://ojs.aaai.org/index.php/AAAI/article/view/29530)

**Zongqian Wu**, Yujie Mo, Peng Zhou, Shangbo Yuan, Xiaofeng Zhu

- This paper introduces a novel self-training FSNC method that addresses the limitations of existing approaches, leveraging representation and pseudo-label distillation techniques to enhance the utilization of base set information and mitigate the impact of low-quality pseudo-label.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2022</div><img src='images/IA-FSNC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Information Augmentation for Few-shot Node Classifcation](https://www.ijcai.org/proceedings/2022/0500.pdf) 

**Zongqian Wu**, Peng Zhou, Guoqiu Wen, Yingying Wan, Junbo Ma, Debo Cheng, Xiaofeng Zhu

- This paper proposes a new data augmentation method for few-shot node classification on graph data, mitigating issues with time costs and structural exploration. It involves efficient parameter initialization and fine-tuning with support and shot augmentation.
</div>
</div>



# 🎖 Honors and Awards
- *2024.07:* China Scholarship Council (CSC) Scholarship.
- *2023.06:* Outstanding graduate of Guangxi Normal University. 
- *2022.09:* National scholarship.
- *2022.09:* Academic star scholarship (10 students in the school each year).
  


# 🌝 Reviewer
- ICML 2025
- ICLR 2025
- NeurIPS 2024, 2025
- AAAI 2024, 2025
- IJCAI 2024, 2025
- AISTATS 2025
- ECAI 2025
- ACM Multimedia 2023, 2024
- Neurocomputing
- Neural Networks
- Pattern Recognition
- Neural Processing Letters
- The Journal of Supercomputing
- IEEE Transactions on Image Processing
- IEEE Transactions on Knowledge and Data Engineering
- IEEE Transactions on Circuits and Systems for Video Technology

