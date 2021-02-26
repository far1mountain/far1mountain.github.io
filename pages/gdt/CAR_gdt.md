---
title: CAR-T
keywords: 
summary: 
sidebar: gdt
permalink: CAR_gdt.html
folder: gdt
---

## 第一代CAR-T

第一代CAR-T 结构为：胞外区（scFv）···· 铰链区 ···· 跨膜区 ···· 胞内信号传导区（CD3ζ）。

在{% cite rischer_human_2004 %}的研究中，构建了两种CAR-T，胞外区分别来源于针对CD19的单抗（CD19ζ）和针对GD2（神经母细胞瘤）的单抗。

在细胞实验中，CAR-T与常规gdT对比，产生更多的细胞因子，具有更强的肿瘤细胞杀伤能力。

## 第二代CAR-T

第二代CAR-T 结构为：胞外区（scFv）···· 铰链区 ···· 跨膜区 ···· 胞内信号传导区（CD3ζ + 协同刺激区，如CD28或4-1BB）。增加了协同刺激区，借此增加T细胞的增殖，细胞因子分泌，延长细胞的存活时间。

只要存在scFv识别的相关抗原，CAR-T就会发挥作用，如果正常细胞中过表达了相关抗原，也会受到CAR-T的攻击。为了解决这一问题，将双重激活信号分开：

- 信号1（CCR）：胞外（针对肿瘤特异抗原，GD2，CD33，ErbB2）···· 胞内（协同刺激信号，DAP10，CD28）{% cite fisher_engineering_2018 fisher_engineering_2019 %}
- 信号2（TCR）：胞外（gdTCR）···· 胞内（CD3ζ）

CCR是TC biopharm的主要技术。

## 第三代CAR-T

第三代CAR-T的胞内信号传导区包括多个协同结构域，如CD28-41BB或CD28-OX40，临床前结果显示，与第二代CAR相比，第三代CAR效应更强，体内存活更久。

在常规的CAR-T研究{% cite quintarelli_choice_2018%}中，（GD2····CD28····4-1BB····ζ）这种第三代CAR优于CD28-OX40，在以下方面有改善：
- T-cell exhaustion,
- basal T-cell activation, 
- in vivo tumor control 
- T-cell persistence.

随后，他们也将这种CAR应用在gdT细胞中{% cite polito_universal_2019%}，这种改造显著提升了gdT细胞的抗肿瘤能力。

## 第四代CAR-T

第四代CAR-T进一步加入了增强T细胞功能的因素，如细胞因子（IL-2，IL-5,IL-12）及协同刺激配体等。

这类CAR在gdT中的应用需要进一步查询。

## SUPER CAR

SUPER CAR将常规CAR的scFv独立出来，结构为：

scFv····zipA····zipB····胞内结构域

这种设计的好处是，一种改造好的T细胞，可以通过zip链接到不同的scFv上，识别不同的表位。{% cite cho_universal_2018%}

SUPER CAR在gdT中的应用需要进一步查询。

## 其他

替莫唑胺（TMZ）是治疗GB的常用化疗药物，TMZ可以增加肿瘤细胞NKG2D配体的表达，使肿瘤细胞更易于受到gdT细胞的识别和杀伤，但TMZ也会杀伤gdT细胞，因此将抗药基因转染到gdT细胞中，将这种改造的gdT和TMZ联用，增强了gdT的抗瘤活性。{% cite jr_engineered_2013 %}

IN8bio公司利用这种策略，开展了临床试验{% cite md_phase_2020 %}。

**参考文献**
{% bibliography --cited_in_order %}

{% include links.html %}
