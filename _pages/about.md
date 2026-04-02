---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  dl {
    margin-top: 1px;
    margin-bottom: 5px;
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px;
    max-width: 100%;

    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);

    transition: box-shadow 0.3s ease-in-out;
  }

  hr {
    border: 1px solid #ebebeb;
    margin: 30px 0; 
    clear: both; 
  }


  dl dd {
  color: #; 
  margin-top: 1px; 
  margin-bottom: 1px;
}

  dl dd strong {
  font-weight: bold;
  }


  .publication-title {
    font-weight: bold;
  }

  .image-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin: 20px 0;
  }

  .image-container img {
    max-width: 150px;
    height: auto;
    margin: 0; 
  }

  .co-first {
    color: #B02418;
  }

  .spotlight {
    color: #B02418;
  }


  .pub-img-wrapper {
    position: relative;
    float: left; 
    margin: 0px 15px 10px 0px;
  }
  

  .pub-img-wrapper img {
    margin: 0; 
  }

 
  .pub-badge {
    position: absolute;
    top: 0;
    left: 0;
    background-color: #B02418;
    color: white;
    padding: 3px 8px;
    font-size: 13px;
    font-weight: bold;
    z-index: 10;
    border-bottom-right-radius: 6px; 
  }
  

</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


# Short Bio
My name is Hongbin Chen (陈宏斌), and I am currently a second-year Master's student in Biotechnology and Engineering at the [School of Biomedical Engineering and Informatics, Nanjing Medical University](https://english.njmu.edu.cn/), supervised by Prof. [Jianqing Li](https://bmei.njmu.edu.cn/2018/1120/c19988a262557/page.htm) and Assoc. Prof. [Wentao Xiang](https://scholar.google.com/citations?hl=zh-CN&user=-foPGxYAAAAJ&view_op=list_works&sortby=pubdate). I am also a Ph.D. candidate in Clinical Medical Engineering and affiliated with the Jiangsu Province Engineering Research Center for Smart Wearable and Rehabilitation Devices. 

My research interests lie in **Affective Computing**, with a particular focus on multimodal emotion recognition for older adults. 

Let's collaborate! I promise to reply to your email much faster than my deepest neural networks converge.



# 🔥 News
<div style="max-height: 200px; overflow-y: auto;">
<ul>
  <li><em>2026.04:</em> 🎉🎉 DiVA was accepted by JBHI!</li>
</ul>
<ul>
  <li><em>2026.03:</em> 🎉🎉 ES-DPNet was accepted by IEEE Trans. on Affective Computing!</li>
</ul>
<ul>
  <li><em>2025.08:</em> 🎉🎉 MOFA was accepted by PRCV 2025!</li>
</ul>

</div>



# 📝 Publications 
&dagger;: equal contribution, * : corresponding author


<hr>

<dl>
<dt>
    <div class="pub-img-wrapper">
      <span class="pub-badge">JBHI 2026</span>
      <img width="400" src="../images/paper/DiVA.png" alt="DiVA">
    </div>
  </dt>
  <dd>
    <a href="https://doi.org/10.1109/JBHI.2026.3679693" class="publication-title">Towards Cognitive Impairment Screening in Elderly Communities with Audio-Visual Modal Disentangled Representation Learning
    </a>
  </dd>
  <dd>Rui Feng, <strong>Hongbin Chen</strong>, Yihao Yao, Liuyu Wu, Tao Liang, Wentao Xiang, Jie Li, Chu Kiong Loo, Junxiao Yu*, Wei Wang*, Jianqing Li*</dd>
  <dd>Journal of Biomedical and Health Informatics <strong>(JBHI)</strong>, 2026</dd>
  <dd>
    <a href="https://github.com/FengRui1998/DiVA" target="_blank" style="text-decoration: none; color: #181717; font-weight: bold;">
      <i class="fab fa-github" style="font-size: 1.2em; margin-right: 5px;"></i>[Code & Project]
    </a>
  </dd>
</dl>


<hr>

<dl>
<dt>
    <div class="pub-img-wrapper">
      <span class="pub-badge">TAFFC 2026</span>
      <img width="400" src="../images/paper/ES-DPNet.jpg" alt="ES-DPNet">
    </div>
  </dt>
  <dd>
    <a href="https://doi.org/10.1109/TAFFC.2026.3679686" class="publication-title">Facial Expression Recognition for Chinese Elderly Using Edge and Semantic features Dual Path Network with Two-step Transfer Learning
    </a>
    <!-- <a href="javascript:alert('The publisher is still brewing the coffee! Paper will be online soon. ☕');" class="publication-title" style="cursor: help;">Facial Expression Recognition for Chinese Elderly Using Edge and Semantic features Dual Path Network with Two-step Transfer Learning
    </a> -->
  </dd>
  <dd>Keke Shi<sup>&dagger;</sup>, <strong>Hongbin Chen<sup>&dagger;</sup></strong>, Keshu Cai, Jinhui Wu, Wei Wang, Jie Li, Bin Liu, Liangcheng Qu, Kuiying Yin, Pasquale Molinaro, Giancarlo Fortino, Jianqing Li, Wentao Xiang*</dd>
  <dd>IEEE Trans. on Affective Computing <strong>(TAFFC)</strong>, 2026</dd>
  <dd>
    <a href="https://github.com/Codenewwer/feresdpnet" target="_blank" style="text-decoration: none; color: #181717; font-weight: bold;">
      <i class="fab fa-github" style="font-size: 1.2em; margin-right: 5px;"></i>[Code & Project]
    </a>
  </dd>
</dl>

<hr>

<dl>
<dt>
    <div class="pub-img-wrapper">
      <span class="pub-badge">PRCV 2025</span>
      <img width="400" src="../images/paper/MOFA.jpg" alt="MOFA">
    </div>
  </dt>
  <dd>
    <a href="https://link.springer.com/chapter/10.1007/978-981-95-5567-3_29" class="publication-title">MOFA: Modality-Orthogonalized Fusion Architecture for Multimodal Emotion Recognition
    </a>
  </dd>
  <dd><strong>Hongbin Chen</strong>, Rui Feng, Jie Li, Wei Wang, Jianqin Li*, Wentao Xiang*</dd>
  <dd>Chinese Conference on Pattern Recognition and Computer Vision <strong>(PRCV)</strong>, 2025</dd>
</dl>

<hr>






# 🎖 Honors and Awards
- *2025.11* National Graduate Scholarship (Master Student)
- *2025.10* First-Class Graduate Scholarship (Master Student)
- *2024.08* Excellent Undergraduate Thesis Award, Jiangsu Province
- *2024.06* Outstanding Undergraduate Graduate


# 💬 Professional Services
- Conference Reviewer: PRCV (2026).
