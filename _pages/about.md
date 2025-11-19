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



My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

## 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/confild.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generative Latent Diffusion Model for Inverse Modeling and Uncertainty Analysis in Geological Carbon Sequestration](https://arxiv.org/abs/2508.16640)

**Zhao Feng**, Xin-Yang Liu, Meet Hemant Parikh, Junyi Guo, Pan Du, Bicheng Yan\*, Jian-Xun Wang\*

**Code**: [![GitHub](https://img.shields.io/badge/GitHub-CoNFiLD--geo-blue?logo=github)](https://github.com/fengzhao1239/CoNFiLD-geo)
- CoNFiLD-geo combines conditional neural field encoding with Bayesian conditional latent-space diffusion models, enabling *zero-shot* conditional generation of geomodels and reservoir responses across complex geometries and grid structures.
- The model is pretrained unconditionally in a self-supervised manner, followed by a Bayesian posterior sampling process, allowing for data assimilation for unseen/unobserved states without task-specific retraining. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/surgin.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SURGIN: SURrogate-guided Generative INversion for subsurface multiphase flow with quantified uncertainty](https://arxiv.org/abs/2509.13189)

**Zhao Feng**, Bicheng Yan, Luanxiao Zhao, Xianda Shen, Renyu Zhao, Wenhao Wang, Fengshou Zhang\*

**Code**: [![GitHub](https://img.shields.io/badge/GitHub-SURGIN-blue?logo=github)](https://github.com/fengzhao1239)
- SURGIN integrates a U-Net enhanced Fourier Neural Operator (U-FNO) surrogate with a score-based generative model (SGM), framing the conditional generation as a surrogate prediction-guidance process in a Bayesian perspective.
- An unconditional SGM is first pretrained in a self-supervised manner to capture the geological prior, after which posterior sampling is performed by leveraging a differentiable U-FNO surrogate to enable efficient forward evaluations conditioned on *unseen* observations.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Advances in Water Resources</div><img src='images/cnn_trans.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A hybrid CNN-transformer surrogate model for the multi-objective robust optimization of geological carbon sequestration](https://www.sciencedirect.com/science/article/pii/S0309170825000119)

**Zhao Feng**, Bicheng Yan, Xianda Shen, Fengshou Zhang\*, Zeeshan Tariq, Weiquan Ouyang, Zhilei Han

**Code**: [![GitHub](https://img.shields.io/badge/GitHub-CNN--Transformer-blue?logo=github)](https://github.com/fengzhao1239/CNN-Transformer)
- A hybrid CNN-Transformer surrogate model is developed to simulate time-varying CO<sub>2</sub> injection into 3D heterogeneous geological fields.
- Multi-objective robust optimization is implemented by integrating CNN-Transformer with Non-dominated Sorting-based genetic algorithm II.
</div>
</div>


- [CoSwinNet: a conditional Swin Transformer multimodal surrogate model for subsurface multiphase flow](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=u_cUQswAAAAJ&citation_for_view=u_cUQswAAAAJ:hqOjcs7Dif8C). **Zhao Feng**, Zeeshan Tariq\*, Zhong Zhang, Peilin Zhao, Renyu Zhao, Wenhao Wang, Xinwo Huang, Bicheng Yan, Xianda Shen\*, Fengshou Zhang.

- [CO<sub>2</sub> sequestration and mineralization in basalts: Insights from a deep learning-based surrogate model](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=u_cUQswAAAAJ&citation_for_view=u_cUQswAAAAJ:hqOjcs7Dif8C). Weiquan Ouyang, **Zhao Feng**, Fengshou Zhang\*, Zhao Xia, Xianda Shen. ***Engineering Geology***.




## 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Gas Science and Engineering</div><img src='images/gse_paper.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An encoder-decoder ConvLSTM surrogate model for simulating geological CO<sub>2</sub> sequestration with dynamic well controls](https://www.sciencedirect.com/science/article/pii/S2949908924001109)

**Zhao Feng**, Zeeshan Tariq, Xianda Shen\*, Bicheng Yan\*, Xuhai Tang, Fengshou Zhang

**Code**: [![GitHub](https://img.shields.io/badge/GitHub-ED--ConvLSTM-blue?logo=github)](https://github.com/fengzhao1239/ED-ConvLSTM)
- An Encoder-Decoder Convolutional LSTM (ED-ConvLSTM) is developed for simulating CO<sub>2</sub> flow under dynamic injection rates.
- The proposed network has excellent capability in extrapolating to *unseen* time steps and to different geological settings.
</div>
</div>

- [TransUNet: Accelerating Multiphase Flow Prediction in Geological Carbon Storage Systems](https://onepetro.org/SPEADIP/proceedings/24ADIP/24ADIP/D021S065R002/585839). Zeeshan Tariq, **Zhao Feng**, Hussein Hoteit, Moataz Abualsaud, Xupeng He, Muhammad AlMajid, Shuyu Sun, Bicheng Yan. ***Abu Dhabi International Petroleum Exhibition and Conference***.


## 2023

- [A Data-Driven Model for the Prediction of Stimulated Reservoir Volume (SRV) Evolution During Hydraulic Fracturing](https://onepetro.org/isrmcongress/proceedings/CONGRESS23/CONGRESS23/ISRM-15CONGRESS-2023-361/540138). **Zhao Feng**, Fengshou Zhang, Xianda Shen, Bichen Yan, Zhaowei Chen. ***ISRM Congress***.








# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.