---
title:  "Generative AI for Equity Research Reports"
mathjax: true
layout: post
categories: GPT
---
<img src="{{ site.baseurl }}/img/teaching_img/2022_03.JPG" width="600" height="2000" class="center" style="margin:10px 15px"/>

[Slides](https://www.dropbox.com/scl/fo/dlyfdfu62z1wtqgdvy3ow/AF8Lsio1RALfsBsT7mb6cEA?rlkey=471l3ruhd9p0zjgmv7bvnt3z8&dl=0)
[Notes](https://www.dropbox.com/scl/fi/s0qm4f1td2bsofh4xh2m7/Group9_Option1.pptx?rlkey=zmna8tvzg7ul46x5pygh8623l&dl=0)
[Code and Data](https://www.dropbox.com/scl/fo/dlyfdfu62z1wtqgdvy3ow/AF8Lsio1RALfsBsT7mb6cEA?rlkey=471l3ruhd9p0zjgmv7bvnt3z8&dl=0)


* This is a sample material from and for ISOM 3350 FinTech and Cryptoventure course use. Please reach out for a proper citing and circulating of the work when needed.

Whitepapers are critical in providing a detailed business description and STO specifics to potential investors, yet many companies struggle to produce effective documents. To address this, we propose leveraging ChatGPT, a generative AI tool, to fine-tune a GPT model that enhances the quality of STO whitepapers.

## Project Goals:

**Structural and Persuasive Whitepapers:** We aim to create whitepapers that are not only structurally comprehensive but also maintain the correct tone and sentiment—concise, confident, and optimistic. Our analysis of existing documents reveals issues with tone, with some being too informal or negatively focused on challenges. Our enhanced ChatGPT model will ensure whitepapers are appropriately persuasive and positive.

**Clarifying Technical Details:** Many STO whitepapers contain technical jargon that is not reader-friendly, particularly for non-experts. This can deter potential investors. Our model will focus on explaining complex technical details in an accessible manner, increasing the overall appeal and effectiveness of the whitepapers.

**Effective Marketing and Promotion:** Whitepapers serve crucial marketing and promotional roles, sparking investor interest in STOs. However, the significant time and effort required to produce detailed whitepapers can be a barrier. Our trained AI model aims to alleviate this by generating comprehensive, well-written documents efficiently, enabling companies to better utilize their resources for marketing and promotional activities.

By addressing these gaps, we hope to significantly improve the utility and effectiveness of STO whitepapers, making them more appealing to potential investors and supporting companies in their fundraising efforts.

### Model Evaluation

Our project entails fine-tuning two distinct models using varied datasets for STO whitepapers. Model 1 was refined solely with 7 Company STO whitepapers, while Model 2 included a diverse set, with 7 Company STO whitepapers, 4 Investment Vehicle STO whitepapers, and 4 Company ICO whitepapers.

We evaluated these models using a test set consisting of a Scientificcoin STO Whitepaper. We assessed GPT-3 Davinci alongside our two tailored models using six carefully crafted prompts designed to encapsulate five crucial sections: the introduction, market analysis, company overview, token overview, and STO details.

The parameter settings were calibrated to mirror the test set completions in terms of content length. We applied a frequency and presence penalty of 0.5 to encourage diverse outputs. The temperature was set to 0.3 for the introduction to foster precision, and 0.5 for the remaining sections to balance creativity and relevance. The performance is listed in the table below. Note: F, P and T stand for frequency penalty, presence penalty and temperature respectively.

Finally we compare readiblity, word complixity and sentiment of white paper our model generated with human generated ones.


<img src="{{ site.baseurl }}/img/teaching_img/2023_05_02.JPG" width="600" height="2000" class="center" style="margin:10px 15px"/>
