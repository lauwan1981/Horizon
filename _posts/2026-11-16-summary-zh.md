---
layout: default
title: "Horizon Summary: 2026-11-16 (ZH)"
date: 2026-11-16
lang: zh
---

> 从 28 条内容中筛选出 3 条重要资讯。

---

**科技新闻**
1. [1.4MB 纯 HTML 3D 游戏被拆解：约 700KB 实为 Three.js 库](#item-tech-news-1) ⭐️ 6.0/10
2. [Qwen4-Max 发布传闻：2.4T 骨干与百万 token 上下文待证实](#item-tech-news-2) ⭐️ 5.0/10
3. [Claude 辅助的 DOS 语言模型号称仅 435 KB](#item-tech-news-3) ⭐️ 5.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [1.4MB 纯 HTML 3D 游戏被拆解：约 700KB 实为 Three.js 库](https://aihot.news/items/izdx1kuppob6c65ghvmyeal38) ⭐️ 6.0/10

公众号“数字生命卡兹克”拆解了一款近期在社群疯传的 1.4MB 纯 HTML 3D 游戏，指出其中约 700KB 是打包进单文件的 Three.js 库，其余内容全部由代码程序化生成，未使用任何图片、模型或录音。文章同时附上了用于 AI 辅助生成此类游戏的提示词模板。需要注意，这是一篇二手来源的技术分析而非新工具发布，文中细节未经独立验证。

rss · AIHot-Token羊毛 · 11月15日 23:56

**「背景说明」** Three.js 是常用的 WebGL 3D 图形库，官方提供在线编辑器（tool-1-1）。本文所说的“程序化生成”指几何体、纹理等资产由代码在运行时计算生成，而非随文件附带图片、模型或录音，因此单个 HTML 文件也能呈现完整 3D 场景。

**「实际影响」** 对想复现此类单文件 3D demo 的开发者而言，该拆解提示其体积主要来自 Three.js 运行时而非生成内容本身，可借助文中的提示词模板尝试生成，但需自行验证生成代码的质量与浏览器兼容性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://threejs.org/editor/">three . js editor</a></li>

</ul>
</details>

**标签**: `#Three.js`, `#procedural generation`, `#AI-generated code`, `#HTML5 game`, `#prompt engineering`

---

<a id="item-tech-news-2"></a>
### [Qwen4-Max 发布传闻：2.4T 骨干与百万 token 上下文待证实](https://aihot.news/items/nqcfrkilrh7nhnpd03t9q1zfh) ⭐️ 5.0/10

一篇自动生成的 RSS 摘要称，Qwen 团队已发布基于新 Qwen4 架构的 Qwen4-Max，规格包括 2.4T 骨干参数、每 token 激活 71B 参数、328B N-gram Embedding 参数、原生视觉能力和 100 万 token 上下文窗口。该条目没有提供任何基准测试、技术细节或发布日期，只链接到一篇官方博客文章但未附其内容，因此这些规格无法从条目本身得到核验。在官方确认之前，2.4T 参数、71B 激活量和百万级上下文应视为未经证实的传闻，而非已发布或独立测量的能力。

rss · AIHot-Token羊毛 · 11月16日 02:00

**「Qwen4 架构与预览状态」** Qwen4-Max 是阿里 Qwen 系列的新一代旗舰，基于新的 Qwen4 架构：总骨干参数 2.4T、每 token 激活 71B，并额外带有 328B N-gram Embedding 参数，官方博客与阿里云文档均将其定位为面向编码、办公与复杂智能体任务的多模态模型。目前该模型以有限预览形式开放，提供 100 万 token 上下文，但 Token Plan 访问将于 11 月 25 日结束且禁止后端使用，原始 RSS 摘要未提供基准或技术细节，完整能力仍待验证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://qwen.ai/blog?id=qwen4-max">Qwen4-Max: Your New Teammate Has Arrived</a></li>
<li><a href="https://xenospectrum.com/en/qwen4-max-preview-specs-limitations/">Alibaba&#x27;s Qwen4-Max Preview Offers a 1M-Token Context Window ...</a></li>
<li><a href="https://www.alibabacloud.com/help/en/model-studio/qwen4-max-preview">qwen4-max-preview (Latest Model) - Alibaba Cloud</a></li>

</ul>
</details>

**标签**: `#LLM release`, `#Qwen`, `#model architecture`, `#long context`, `#AI agents`

---

<a id="item-tech-news-3"></a>
### [Claude 辅助的 DOS 语言模型号称仅 435 KB](https://news.google.com/rss/articles/CBMijAFBVV95cUxQN3pOT0Ryc2VtbWhRa2thQmFPTjFPc0pIOTd3dUdJMHJjN2NPOExYVEhpNm9JbnpsdFhVZ3ZlamFOWDZOMU0wN1hzUHI0aHFrdER1NTlnUmZFVEhHRU1JS0JzTTBSRTcwSDlmRk90aEF5Q2htb2F5ZVk4WTVLZkREXzZ5RFh0ZTBCc3VYNg?oc=5) ⭐️ 5.0/10

据标题报道，Pasquale Pillitteri 展示了一个据称借助 Claude 构建、可在 DOS 下运行的语言模型，体积仅 435 KB，小到可装入一张软盘。目前可获得的只有标题与元数据，正文、模型架构、训练方式和实测效果均无法核实，因此该规模与可用性仍属单方说法。若属实，它属于复古计算场景下的小模型演示，而非经过独立验证的通用能力突破。

google\_news · Pasquale Pillitteri · 11月15日 18:08

**「背景说明」** 标题中的 Claude 指 Anthropic 的 AI 助手（tool-1-1），作者 Pasquale Pillitteri 是一名软件开发者（tool-1-2）。目前可获取的内容仅有标题与元数据，称其用 Claude 构建了一个 435 KB、可装入一张软盘并在 DOS 下运行的语言模型；常见 3.5 英寸软盘容量约为 1.44 MB，因此 435 KB 确实可以容纳，但文章正文缺失，模型的架构、训练方式与实际效果均无法核实。

**「实际影响」** 目前唯一可核实的数字是标题中的 435 KB；在正文缺失的情况下，读者无法确认其模型架构、推理质量或 DOS 兼容性，因此该消息更适合作为待验证的爱好者项目，而非可直接复用的工程方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.ai/">Claude</a></li>
<li><a href="https://pasqualepillitteri.it/es/tools/image-to-pdf">Image to PDF - Convert Images to PDF Document | Pasquale Pillitteri</a></li>

</ul>
</details>

**标签**: `#language models`, `#DOS`, `#retro computing`, `#AI-assisted development`, `#small models`

---