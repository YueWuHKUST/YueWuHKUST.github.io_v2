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
<span id="jump1"></span>
<span class='anchor' id='about-me'></span>

I am a final-year Ph.D. student at the Computer Science and Engineering department of Hong Kong University of Science and Technology (HKUST) supervised by <a href="https://cqf.io/"> Prof. Qifeng Chen </a>. Prior to this, I got my Bachelor's degree from Department of Computer Science at <a href="https://en.whu.edu.cn/"> Wuhan University </a> in 2018.

I'm interested in computational photography, image/video synthesis, 3D generative models and neural rendering.

# 🔥 News
- *2023.06*: &nbsp;🎉🎉🎉🎉 I passed my PhD thesis defense!
- *2023.05*: &nbsp;🎉🎉 I finished my Internship in Microsoft Research Asia.
- *2023.05*: &nbsp;🎉🎉 Two papers are accepted by ICRA2023.
- *2022.05*: &nbsp;🎉🎉 AniFaceGAN is accepted by NeurIPS as a spotlight paper. 


# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022(Spotlight)</div>
<img src='images/anifacegan.png' alt="sym" width = "500" height = "300">
</div></div>
<div class='paper-box-text' markdown="1">

[AniFaceGAN: Animatable 3D-Aware Face Image Generation for Video Avatars](https://arxiv.org/abs/2210.06465)

**Yue Wu**, Yu Deng, Jiaolong Yang, Fangyun Wei, Qifeng Chen, Xin Tong
 
[**PDF**](href="https://arxiv.org/abs/2210.06465) [**Project**](https://yuewuhkust.github.io/AniFaceGAN/) **Code**:(Contact wu.kathrina@gmail.com for the inference code and pretrained models!)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2023</div>
<img src='images/waterdrop.png' alt="sym" width = "500" height = "300"></div></div>
<div class='paper-box-text' markdown="1">

[Video Waterdrop Removal via Spatio-Temporal Fusion in Driving Scenes](https://arxiv.org/abs/2210.06465)

Qiang Wen, **Yue Wu**, Qifeng Chen

[**PDF**](href="https://arxiv.org/abs/2302.05916) [**Code**](https://github.com/csqiangwen/Video_Waterdrop_Removal_in_Driving_Scenes) [**极市平台**](https://mp.weixin.qq.com/s/Smu-E0yhxzS7_c0ahSCAdQ)

We propose a video waterdrop method achieving the best performance in complex real-world driving scenes .
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2023</div><img src='images/long_term.jpg' alt="sym" width = "500" height = "300"></div></div>
<div class='paper-box-text' markdown="1">

[Improving Video Super-Resolution with Long-Term Self-Exemplars](https://arxiv.org/abs/2106.12778)

Guotao Meng\*, **Yue Wu**\*, Qifeng Chen
 
[**PDF**](https://arxiv.org/abs/2106.12778)

We propose Video SR method by utilizing self-exemplars in long-term frames.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/all.gif' alt="sym" width = "500" height = "300"></div></div>
<div class='paper-box-text' markdown="1">

[Optimizing Video Prediction via Video Frame Interpolation](https://arxiv.org/abs/2206.13454)

**Yue Wu**, Qiang Wen, Qifeng Chen
 
[**PDF**](https://arxiv.org/abs/2206.13454) [**Project**](https://yuewuhkust.github.io/OVP_VFI/) [**Code**](https://github.com/YueWuHKUST/CVPR2022-Optimizing-Video-Prediction-via-Video-Frame-Interpolation/) [**BibText**](images/OVP_VFI.txt)

We propose an optimization framework for video prediction without external training.

</div>
</div>
  
  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/novel.png' alt="sym" width = "500" height = "300"></div></div>
<div class='paper-box-text' markdown="1">

[Embedding Novel Views in a Single JPEG Image](https://arxiv.org/abs/2108.13003)

**Yue Wu**\*, Guotao Meng*, Qifeng Chen
 
[**PDF**](https://cqf.io/papers/Embedding_Novel_Views_ICCV2021.pdf) [**Project**](https://yuewuhkust.github.io/iccv-2021-embedding/) 
[**arXiv**](https://arxiv.org/abs/2108.13003)
[**BibTeX**](images/embedding.txt)

An interesting method to embedding novel views into a single image.

</div>
</div>
  
  

  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2020</div><img src='images/video_pred.png' alt="sym" width = "500" height = "300"></div></div>
<div class='paper-box-text' markdown="1">

[Future Video Synthesis with Object Motion Prediction](https://arxiv.org/abs/2004.00542)

**Yue Wu**, Rongrong Gao, Jaesik Park, Qifeng Chen
 
[**PDF**](https://cqf.io/papers/Future_Video_Synthesis_With_Object_Motion_Prediction_CVPR2020.pdf) 
[**arXiv**](https://arxiv.org/abs/2004.00542)
[**Code and Result**](https://github.com/YueWuHKUST/FutureVideoSynthesis) [**BibTeX**](./images/cvpr2020_videopred.txt)

An dedicated framework to decompose the scene and utilize spatial transformer to mimic the movement of rigid scenes.

</div>
</div>
  
  
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV Workshop 2017</div><img src='images/pose.png' alt="sym" width = "500" height = "300"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Multi-Person Pose Tracking: Bottom-up and Top-down Methods](hhttps://arxiv.org/abs/2210.06465)

Sheng Jin, Xujie Ma, Zhipeng Han, **Yue Wu**, Wei Yang, Wentao Liu, Chen Qian, Wanli Ouyang
 
[**PDF**](https://jin-s13.github.io/papers/BUTD.pdf)


Ranked 2nd Places in ICCV Posetrack Challenge

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV Workshop 2017</div><img src='images/icme.png' alt="sym" width = "500" height = "300"></div></div>
<div class='paper-box-text' markdown="1">

[Saliency map generation based on saccade target theory](https://ieeexplore.ieee.org/document/8019456)

**Yue Wu**, Zhenzhong Chen
 
[**PDF**](https://ieeexplore.ieee.org/document/8019456)


</div>
</div>

  
  
## 🧱 Preprints
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/colorization.png' alt="sym" width = "500" height = "300"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Photorealistic Colorization by Imagination](https://arxiv.org/abs/2108.09195)

Chenyang Lei*, **Yue Wu**\*, Qifeng Chen
 
[**PDF**](https://arxiv.org/abs/2108.09195) 


We propose a method to achieve outsanding colorization result by utilizing an imagination module.


</div>
</div>

# 💻 Work Experience
- *2022.1 - 2023.5*, [Microsoft Research Asia](https://www.msra.cn/), Intern. 
- *2017.7 - 2017.12*, [Sense Time](https://www.sensetime.com/cn), Intern.




# 🎖 Honors and Awards
- *2023* HKUST RedBird Academic Excellence Award
- *2018* Postgraduate Scholarship, HKUST.
- *2017* CCF Outstanding College Student Award
- *2017* Best Head Movement Prediction Student Prize ICME Grand Challenge Salient360!
- *2017* Meritorious Winner Interdisciplinary Contest In Modeling.
- *2015* National scholarship, Wuhan University. 
- *2014-2018* First-Class scholarship, Wuhan University


<!-- # 💬 Invited Talks
- *2021* Combining Deep Neural Networks for Efficient Image Restoration and Editing. [Link](https://www.cvmart.net/community/detail/5581) -->

# ✏ Academic Reviewer
* Conference
ECCV 2022, CVPR 2022, ICRA 2023, CVPR 2023.
* Journal
JMLR
<!-- * Outstanding reviewer
NeurIPS, 2022 -->

# 🏫 Teaching Assistant
- *2019* COMP5411: Computer Graphics
- *2020* COMP2711H: Honors Discrete Mathematical Tools for Computer Science
- *2021* COMP3511: Operating System, 2021
- *2022* COMP5214: Advanced Deep Learning Architectures, 2022

<br/>
<br/>
<a href="https://info.flagcounter.com/UQVZ"><img src="https://s11.flagcounter.com/count2/UQVZ/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_10/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0"></a>