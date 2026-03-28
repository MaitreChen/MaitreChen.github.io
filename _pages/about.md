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
    margin-bottom: 5px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px; /* 图片居中 上右下左*/ 
    max-width: 100%; /* 限制图片最大宽度 */
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
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
    gap: 10px; /* 控制图片间距 */
    margin: 20px 0;
  }

  .image-container img {
    max-width: 150px; /* 控制最大宽度 */
    height: auto;
    margin: 0; /* 移除原来的 margin */
  }

  .co-first {
    color: #B02418;
  }

  .spotlight {
    color: #B02418;
  }

  /* 新增：用于包裹图片并作为绝对定位的参考系 */
  .pub-img-wrapper {
    position: relative;
    float: left; /* 替代原来的 img align="left" */
    margin: 0px 15px 10px 0px;
  }
  
  /* 新增：清除图片自带的外边距，防止排版冲突 */
  .pub-img-wrapper img {
    margin: 0; 
  }

  /* 新增：左上角 Badge 的样式 */
  .pub-badge {
    position: absolute;
    top: 0;
    left: 0;
    background-color: #B02418; /* 使用你预设的主题红 */
    color: white;
    padding: 3px 8px;
    font-size: 13px;
    font-weight: bold;
    z-index: 10;
    border-bottom-right-radius: 6px; /* 右下角增加圆角，视觉更柔和 */
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

My research interests lie in **Affective Computing** and **Multimodal Learning**, with a particular focus on multimodal emotion recognition for older adults. Have fun!



# 🔥 News
<div style="max-height: 200px; overflow-y: auto;">
<ul>
  <li><em>2025.08:</em> 🎉 MOFA was accepted by <strong>PRCV 2025</strong>-Shanghai, here we come!</li>
</ul>
<ul>
  <li><em>2026.03:</em> 🎉🎉 MCI-FED was accepted by IEEE Trans. on Affective Computing!</li>
</ul>
</div>



# 📝 Publications 
&dagger;: equal contribution, * : corresponding author

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
  <dd><a>[Project Page]</a></dd>
</dl>

<hr>



# 🎖 Honors and Awards
- *2025.11* National Graduate Scholarship (Master Student)
- *2025.10* First-Class Graduate Scholarship (Master Student)
- *2024.08* Excellent Undergraduate Thesis Award, Jiangsu Province
- *2024.06* Outstanding Undergraduate Graduate

