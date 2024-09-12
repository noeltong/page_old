---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Electronic Engineering, Shanghai Jiao Tong University, Minhang, Shanghai, China, 2024 - 2028 (expected)
* M.S. in Electronic Engineering, ShanghaiTech University, Pudong, Shanghai, China, 2021 - 2024
* B.S. in Communication Engineering, Jiangnan University, Wuxi, Jiangsu, China, 2012

Work experience
======
* Central Research Institute, United Imaging Healthcare Co., LTD, Shanghai, Oct. 2023 -- July 2024
    * During my internship at Central Research Institute of United Imaging, my work mainly focused on the quantitative analysis algorithms of parametric imaging of dynamic positron emission tomography (dPET) imaging with patient data from uEXPLORER, a total body PET/CT scanner, under the supervision of Prof.~Yun Zhou. My work mainly contains
        * Dual-tracer time-activity curve separation with machine learning algorithms.
        * Accelerating irreversible 2-tissue compartment model with CUDA and PyTorch.
        * Development of automatic PET/CT parametric imaging and time-activity curve calculation (including regions of interest of brain and tissues of total body) pipeline with CT segmentation.
    * Supervisor: Prof. Yun Zhou (email: `yun.zhou@united-imaging.com`)
  
Skills
======
* Research Interests
    * Solving inverse problems in medical imaging (particularly in photoacoustic imaging) with generative models,
    * Self-supervised representation learning and other pre-training methods,
    * Computer vision in biomedical applications.
* Platform: Linux > Windows.
* Programming Languages: Python, MATLAB, \LaTeX{}.
* DL framework: PyTorch > JAX.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
