---
title: "运动模糊图像PSF估计算法改进研究"
authors:
- 张爱桃
- 李佳
- 周旭
- 梁晶
- 魏昊业
- 张爱净
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2025-12-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*北京生物医学工程, 44*(6)"
publication_short: ""

abstract: 目的 针对运动模糊图像复原中,传统频谱法存在的检测误差大,抗噪性弱及有效检测范围有限等问题,本文提出一种融合高斯拉普拉斯(Laplacian of Gaussian,LoG)滤波与Radon 变换的边缘增强频谱分析法,旨在实现点扩散函数(point spread function,PSF)参数的精准估计.方法 基于脑部MRI 仿真运动模糊模型,分析频谱中明暗条纹的分布特征,采用LoG 滤波提取频谱亮条纹边缘,抑制中心宽条纹与Gibbs 现象导致的干扰,生成保留方向特征的离散边缘点集;利用Radon 变换包容非共线点集的抗噪特性(离散边缘点沿角度θ 投影时,真实边缘贡献相干叠加,噪声点投影随机抵消),显著提升峰信噪比,进而精准定位模糊角度并计算模糊长度;采用配对t 检验,对传统中心亮条纹检测方法与本文方法的PSF参数估计误差进行统计学分析比较.结果 本研究方法的角度估计平均误差0.08°,显著低于传统方法的3.28°,长度估计平均误差0.15 像素,传统方法为0.88 像素,有效角度检测范围由传统方法的±60°扩展到0～180°,且组间误差差异均达极显著水平(P＜0.001).结论 本方法通过LoG 滤波与Radon 变换的协同机制,避免了对中心条纹完整性的依赖,解决了宽条纹导致的检测失效问题,同时有效抑制了噪声和Gibbs 现象导致的干扰,显著提高了运动模糊PSF 参数估计的精度与鲁棒性,为医学影像运动伪影消除提供可靠的技术基础.

# Summary. An optional shortened abstract.
summary: 提出一种运动模糊参数的估计方法.


#tags:
#- Source Themes
#featured: false

#hugoblox:
  #ids:
    #arxiv: 1512.04133v1

links:
  - type: pdf
    url: http://xuebao.hebtu.edu.cn/web/ziran.articleBrief.do?articleId=13528

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
