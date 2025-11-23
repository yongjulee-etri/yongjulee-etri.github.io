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

**Dr. Yong-Ju Lee is the head of the Visual Intelligence Research Department at the Electronics and Telecommunications
Research Institute (ETRI)** in South Korea and adjunct professor in Korea National University of Science and Technology.
He received a Ph.D. in computer engineering from the Chungnam National University(CNU), South Korea. He was a
visiting scholar at the University of Virginia Tech and planning committee/RFP member('19~'23:AI,'24: AI Safety R&D, AGI) of the ministry of science and ICT in
Korea. With a distinguished career in visual intelligence research, Dr. Lee has made significant contributions to the field
and continues to lead innovative projects that advance multimedia technologies, such as generative visual intelligence(KOALA, Ko-LLaVA) and
visual AI agent collaboration(CLARA). His research interests include Artificial General Intelligence(AGI), Generative AI, Edge-based model compression, Human-level
visual perception, Crossmodal/Multimodal learning.

# 🎉 Visual Intelligence Lab  [[Homepage]](https://etri-visualintelligence.github.io/) <br>
 - **(2024)** : We have **19 papers** this year(2 ETRI J., 5 CVPR, 2 AVSS, 1 ICML, 6 ECCV, 3 NeurIPS). <br>
 -- **(2024/12)**: Three papers accepted to NeurIPS 2024 (Kwanyong Park, Youngwan Lee, Ham Jaeseok) <br>
 -- **(2024/09)**: Six papers accepted to ECCV 2024 (Youngwan Lee, Kwanyong Park, Lee Seongwon, Min jinyoung, Ham Jaeseok, Kim Hyungil) <br>
 -- **(2024/08)**: One paper accepted to ICML 2024 (Youngwan Lee) <br>
 -- **(2024/07)**: Two papers accepted to AVSS 2024 (Kim Daehoe, Oh Seongchan)<br>
 -- **(2024/06)**: Five papers accepted to CVPR 2024 (Kwanyong Park, Youngwan Lee, Bae Kangmin, Jo Youngjoo) <br>
 -- **(2024/02)**: Two papers accepted to ETRI J. (Jeong Junyoung, Jeon Sanghun) <br><br>
 - **(2023)** : We have **9 papers** this year(1 AAAI, 1 ICLR, 4 CVPR, 1 ICCV, 1 NeurIPS, 1 ETRI J.). <br>
 -- **(2023/12)**: One paper accepted to NeurIPS 2023 (Youngwan Lee) <br>
 -- **(2023/10)**: One paper accepted to ICCV 2023 (Park Minho), One paper accepted to ETRI J. (Yun Kimin)<br>
 -- **(2023/06)**: Four papers accepted to CVPR 2023 (Kim Jonghee, Ham Jaeseok, Seol Mooah, Bae Kangmin) <br>
 -- **(2023/05)**: One paper accepted to ICLR 2023 (Youngwan Lee)<br>
 -- **(2023/02)**: One paper accepted to AAAI 2023 (Jongryul Lee) <br><br>
 - **(2022)** : We have **6 papers** this year(1 ETRI J., 2 CVPR, 2 ECCV, 1 BMVC). <br>
 -- **(2022/11)**: One paper accepted to BMVC 2022  (Jongryul Lee) <br>
 -- **(2022/10)**: Two papers accepted to ECCV 2022 (Ham Jaeseok, Youngwan Lee)<br>
 -- **(2022/06)**: Two papers accepted to CVPR 2022 (Youngwan Lee, Moon Jinyoung)<br>
 -- **(2022/04)**: One paper accepted to ETRI J. (Chunhee Lee)<br>

  
# 🎖 Projects
-  ## '독자 AI 파운데이션 모델' 프로젝트 선정(NC AI 컨소시엄 참여, '25.08)    [[newspaper]](https://zdnet.co.kr/view/?no=20250804120134)<br>
   ![image description](images//ncai.jpg)
  
-  ## Development of AI Autonomy and Knowledge Enhancement for AI Agent Collaboration <br>
    **Yong-Ju Lee (<span style="color:darkred">Project Investigator, '22~'26</span>)**  [[Homepage]](https://etri-visualintelligence.github.io/clara/)<br>
    ![image description](images//clara-motivation.png)
    -- This research is exploring the underlying technology that allows agents to see, hear, speak, and interact with each other. In particular, we are exploring various services through cooperative learning from a robot perspective. <br>

-  ## Development of Large Korean Language Model Technology for Efficient Pre-training <br>
    **Yong-Ju Lee (<span style="color:darkred">Project Investigator, '22~'25</span>)**  [[Homepage]](https://etri-visualintelligence.github.io/crossmodal/)<br>
    ![image description](images//crossmodal-motivation.png)
   -- The main purpose of this study is to develop an efficient dictionary learning model based on Korean language. In particular, various research attempts are being made to create and understand visual language models. The models we developed are KOALA (Text-to-Image) model and LLaVA (Large Language and Vision Assistant) model. <br>
   
-  ## Development of Model Optimization and Lightweight based on Edge AI Technology <br>
    **Yong-Ju Lee (<span style="color:darkred">Project Investigator, '20</span>)** [[Homepage]](https://etri-visualintelligence.github.io/edge/)<br>
   ![image description](images//edgeai-motivation.png)
   -- The main purpose of this research is to implement a lightweighting process for AI models. In particular, the challenge was carried out through various studies such as model compression and model pruning. <br>

-  ## Development of Big Data Edge Analytics SW Technology for Load Balancing and Activet Timely Response <br>
    **Yong-Ju Lee (<span style="color:darkred">Project Investigator, '18~'20</span>)** [[Homepage]](https://etri-edgeanalytics.github.io/docs/)<br>
      ![image description](images//edge-analytics-motivation.png)
   -- In this research, we studied various underlying deep learning models in a big data analytics environment. In particular, we developed an edge cloud framework. <br>

# 📝 Publications 

-  ## KOALA: Empirical Lessons Toward Memory-Efficient and Fast Diffusion Models for Text-to-Image Synthesis <br>
    Youngwan Lee, Kwanyong Park, Yoorhim Cho, **Yong-Ju Lee**, Sung Ju Hwang<br>
   Conference on Neural Information Processing Systems(<span style="color:darkred">**NeurIPS**</span>) 2024 <br>
   [[paper]](https://arxiv.org/pdf/2312.04005) [[demo]](https://huggingface.co/spaces/etri-vilab/KOALA) [[models]](https://huggingface.co/etri-vilab) <br>

-  ## A Multimodal Chain of Tools for Described Object Detection <br>
    Kwanyong Park, Youngwan Lee, **Yong-Ju Lee**<br>
   Conference on Neural Information Processing Systems Workshop(<span style="color:darkred">**NeurIPS**</span>) 2024 <br>
   [[paper]](https://openreview.net/forum?id=N4i4PfcrK6)<br>
   
-  ## Language-only Efficient Prompt Learning for Zero-shot Composed Image Retrieval <br>
    Seongwon Lee, **Yong-Ju Lee** <br>
   European Conference on Computer Vision Workshop(<span style="color:darkred">**ECCV**</span>) 2024 <br>
   [[paper]](https://green-fomo.github.io/ECCV2024/program.html)<br>


-  ## DiT-Pruner: Pruning Diffusion Transformer Models for Text-to-Image Synthesis Using Human Preference Scores <br>
    Youngwan Lee, **Yong-Ju Lee**, Sung Ju Hwang <br>
   European Conference on Computer Vision Workshop(<span style="color:darkred">**ECCV**</span>) 2024 <br>
   [[paper]](https://green-fomo.github.io/ECCV2024/program.html)<br>


-  ## KOALA: Fast and Memory-Efficient Latent Diffusion Models via Self-Attention Distillation <br>
    Youngwan Lee, Kwanyong Park, Yoorhim Cho, **Yong-Ju Lee**, Sung Ju Hwang <br>
   IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshop(<span style="color:darkred">**CVPR**</span>) 2024 <br>
    [[Project page]](https://huggingface.co/spaces/etri-vilab/KOALA)[[paper]](https://arxiv.org/abs/2312.04005)[[code]](https://github.com/youngwanLEE/sdxl-koala)<br>

-  ## Multimodal AudioVisual Speech Recognition Architecture Using a Three-Feature Multi Fusion Method for Noise-Robust Systems <br>
    Sanghun Jeon, Jieun Lee, Dohyeon Yeo, **Yong-Ju Lee**, SeungJun Kim <br>
   <span style="color:darkred">**ETRI Journal**</span> 2024 <br>
   [[paper]](https://onlinelibrary.wiley.com/doi/10.4218/etrij.2023-0266)<br>

-  ## Block-wise Word Embedding Compression Revisited: Better Weighting and Structuring <br>
    Jong-Ryul Lee, **Yong-Ju Lee**, Yong-Hyuk Moon<br>
   Empirical Methods in Natural Language Processing(<span style="color:darkred">**EMNLP**</span>) 2021<br>
   [[paper]](https://aclanthology.org/2021.findings-emnlp.372/)<br>

-  ## Efficient Approximation of Filters for High-Accuracy Binary Convolutional Neural Networks <br>
    Junyong Park, Yong-Hyuk Moon, **Yong-Ju Lee** <br>
    European Conference on Computer Vision Workshop(<span style="color:darkred">**ECCV**</span>) 2020<br>
   [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-68238-5_6)<br>

-  ## Long Short-Term Memory Recurrent Neural Network for Urban Traffic Prediction: A Case Study of Seoul <br>
   **Yong-Ju Lee**, OkGee Min <br>
   IEEE International Conference on Intelligent Transportation Systems(<span style="color:darkred">**ITSC**</span>) 2018<br>
   [[paper]](https://ieeexplore.ieee.org/document/8569620)<br>
   
-  ## Adaptive delivery and handoff management framework for multimedia session mobility <br>
   **Yong-Ju Lee** <br>
   <span style="color:darkred">**Information Sciences**</span> 2014<br>
   [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0020025514001753)<br>
   
-  ## Video block device for user-friendly delivery in IaaS clouds <br>
   **Yong-Ju Lee** <br>
   <span style="color:darkred">**The Journal of Supercomputing**</span> 2014<br>
   [[paper]](https://link.springer.com/article/10.1007/s11227-013-1032-6)<br>
   
-  ## BitNBD: BitTorrent-based network block device for provisioning virtual machines in IaaS clouds <br>
   **Yong-Ju Lee**,Hag-Young Kim, Cheol-Hoon Lee <br>
   <span style="color:darkred">**IEICE transactions on information and systems**</span> 2011<br>
   [[paper]](https://search.ieice.org/bin/summary.php?id=e94-d_1_60)<br>
   
-  ## Cell approximation method in quorum systems for minimizing access time <br>
   **Yong-Ju Lee**,Hag-Young Kim, Cheol-Hoon Lee <br>
   <span style="color:darkred">**Cluster Computing**</span> 2009<br>
   [[paper]](https://link.springer.com/article/10.1007/s10586-009-0097-8)<br>

# 💬 Invited Talks and Promotions
- **2025.11**, Promotional Video for Safe LLaVA(AI Safety Model)
<iframe width="448" height="252" src="https://www.youtube.com/embed/UR763vV-nu0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br><br>

- **2025.07**, 산업안전보건의 달(공공분야 AI 도입사례 및 AI Safety 연구)
<iframe width="448" height="252" src="https://www.youtube.com/embed/kDdMlhmK1G8?start=3547" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br><br>

- **2025.06**, TJB 대덕의 도전자들 (한국전자통신연구원)
<iframe width="448" height="252" src="https://www.youtube.com/embed/me9yApuqz68" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br><br>

- **2025.04**, Awarded the Prime Minister’s Commendation in celebration of the 2025 Science, Technology, Information and Communication Day(2025년 과학기술정보통신의날 국무총리표창)
<iframe width="448" height="252" src="https://www.youtube.com/embed/OplmKzKVlGk?start=4863" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<!--
![image description](images//PrimeMinisterAward.png)
-->
<br><br>

- **2025.01**, Promotional Video for Collaborative Intelligence of Agents   
<iframe width="448" height="252" src="https://www.youtube.com/embed/n_7n0M_JOec" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br><br>

- **2024.11**, ICT R&D Week 2024
<iframe width="448" height="252" src="https://www.youtube.com/embed/jK4xIr6eWqc?start=8919" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br><br>

<iframe width="448" height="252" src="https://www.youtube.com/embed/7uY3OyzQT6g" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br><br>

- **2024.09**, Agent Collaboration Intelligence(CLARA-ROBOT) in ETRI
<iframe width="448" height="252" src="https://www.youtube.com/embed/4DJ-0Z70E0E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br><br>

- **2024.06**, Genertive Visual Intelligence in ETRI AI Conference 2024
<iframe width="448" height="252" src="https://www.youtube.com/embed/hQmy7vJVNEE?start=13880" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br><br>

- **2024.04** ETRI WebZine 2024/04
<iframe width="448" height="252" src="https://www.youtube.com/embed/VgLvF5pBqbw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br>
<iframe width="100%" height="400" src="https://www.etri.re.kr/webzine/202404/sub02.html" frameborder="0"></iframe>
<br><br>

- **2024.01** ETRI Generative AI promotion 2024/01
<iframe width="448" height="252" src="https://www.youtube.com/embed/oZFSALPGmwk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br>
 ![image description](images//koala-broadcasting.png)
<br>
 ![image description](images//koala-newspaper.png)
<br>


- **2023** Agent Collaboration Project Overview 
<iframe width="448" height="252" src="https://www.youtube.com/embed/kdz_EpIPEt8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" ></iframe>
<br>

- **Contact** Yong-Ju Lee (yongju@etri.re.kr)
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fetri-yongjulee-etri.github.io&amp;count_bg=%2379C83D&amp;title_bg=%23555555&amp;icon=&amp;icon_color=%23E7E7E7&amp;title=hits&amp;edge_flat=false" alt="Hits" /></a>




