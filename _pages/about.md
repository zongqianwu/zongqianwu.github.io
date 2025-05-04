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

My research interest includes <span style="color: #00f;">prompt learning, LLMs, VLMs, and graph representation learning</span>.

If you are interested in me, please contact wkzongqianwu@gmail.com.


# 📖 Educations
- *2024.09 - 2025.09 (**Visiting PhD**):* SUTD <img src="images/SUTD.png" alt="11" style="width: 30px; height: 30px;" />, Guiding Instructor: <a href="https://scholar.google.com/citations?user=KomQOFkAAAAJ"> Prof.Lei Feng</a>.
- *2023.09 - Present (**PhD**):* UESTC <img src="images/UESTC.png" alt="11" style="width: 30px; height: 30px;" />, Guiding Instructor: <a href="https://scholar.google.com/citations?user=-bk1CrcAAAAJ"> Prof.Xiaofeng Zhu</a>, Team Instructors: <a href="https://scholar.google.com/citations?hl=zh-CN&user=krryaDkAAAAJ"> Prof.Heng Tao Shen</a>. 
- *2020.09 - 2023.06 (**Master**):* Guangxi Normal University <img src="images/GXNU.png" alt="11" style="width: 30px; height: 30px;" />, Guiding Instructor: <a href="https://scholar.google.com/citations?user=-bk1CrcAAAAJ"> Prof.Xiaofeng Zhu</a>, Team Instructors: <a href="https://scholar.google.com/citations?hl=zh-CN&user=heE6vKAAAAAJ"> Prof.Shichao Zhang</a>. 
- *2016.09 - 2020.06 (**Bachelor**):* Yulin Normal University <img src="images/YLNU.png" alt="11" style="width: 30px; height: 30px;" />, Applied Statistics. 



# 🔥 News
- *2025.05*: &nbsp;🎉🎉 One paper accepted by ICML 2025!
- *2024.09*: &nbsp;⛄⛄ I will be going to SUTD in Singapore for a visiting PhD program.
- *2024.07*: &nbsp;🎉🎉 One paper accepted by ACM Multimedia 2024!
- *2024.05*: &nbsp;🎉🎉 One paper accepted by KBS!
- *2023.11*: &nbsp;🎉🎉 One paper accepted by AAAI 2024!
- *2023.09*: &nbsp;⛄⛄ I am going to UESTC in Chengdu to pursue a doctoral degree.
- *2023.06*: &nbsp;⛄⛄ Defend my master's dissertation.


# 📝 Publications 

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
- Neural Processing Letters
- The Journal of Supercomputing
- IEEE Transactions on Image Processing
- IEEE Transactions on Knowledge and Data Engineering
- IEEE Transactions on Circuits and Systems for Video Technology

