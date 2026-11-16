---
layout: default
title: "Horizon Summary: 2026-11-16 (EN)"
date: 2026-11-16
lang: en
---

> From 28 items, 3 important content pieces were selected

---

**Technology News**
1. [Viral 1.4MB single-file Three.js game broken down](#item-tech-news-1) ⭐️ 6.0/10
2. [Qwen4-Max claimed with 2.4T params, 1M context; unverified](#item-tech-news-2) ⭐️ 5.0/10
3. [Reported Claude-Built DOS Language Model Fits in 435 KB on One Floppy](#item-tech-news-3) ⭐️ 5.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Viral 1.4MB single-file Three.js game broken down](https://aihot.news/items/izdx1kuppob6c65ghvmyeal38) ⭐️ 6.0/10

A secondary report from the WeChat account 数字生命卡兹克, aggregated by AIHOT, analyzes a viral single-file HTML 3D game of about 1.4 MB, stating that roughly 700 KB is the bundled Three.js library and the remainder is procedural code with no images, models, or recordings. The article explains the Three.js procedural-generation approach and offers prompt templates for AI-assisted creation. The supplied excerpt is thin and comes from a secondary aggregator, so the size split and the templates are the author&\#x27;s claims rather than independently measured results.

rss · AIHot-Token羊毛 · Nov 15, 23:56

**「Three.js and procedural generation basics」** Three.js is an open-source JavaScript library for rendering 3D graphics in the browser, and its web-based editor demonstrates building scenes without external asset files \(tool-1-1\). Procedural generation means geometry, textures, and audio are computed by code at runtime rather than loaded from files, which is what lets a single HTML file contain an entire game once the library itself is bundled. Prompt collections for single-file HTML Three.js browser games are already circulating for models such as Kimi K3 \(tool-1-2\), the context in which this breakdown appeared.

**「Impact」** For developers, the actionable part is the prompt-template set and the note that most of the 1.4 MB file is Three.js itself, but the excerpt includes neither the templates nor the game URL, so readers must open the linked WeChat article to use them.

<details><summary>References</summary>
<ul>
<li><a href="https://threejs.org/editor/">three . js editor</a></li>
<li><a href="https://www.tripo3d.ai/zh/3d-prompts/models/kimi-k3">Kimi K3 3 D 提 示 词 与案例 | Tripo</a></li>

</ul>
</details>

**Tags**: `#Three.js`, `#procedural generation`, `#AI-generated code`, `#HTML5 game`, `#prompt engineering`

---

<a id="item-tech-news-2"></a>
### [Qwen4-Max claimed with 2.4T params, 1M context; unverified](https://aihot.news/items/nqcfrkilrh7nhnpd03t9q1zfh) ⭐️ 5.0/10

An auto-generated RSS item attributed to “Qwen: Blog Retrieval” claims that the Qwen team released Qwen4-Max, built on a new Qwen4 architecture with a 2.4T-parameter backbone, 71B active parameters per token, 328B N-gram embedding parameters, native vision, and a 1M-token context window. The blurb contains no benchmarks, technical details, release date, or availability information, and only links to a Qwen blog URL, so the claims cannot be confirmed from the item itself. Treat the specifications as an unverified aggregator claim rather than a shipped, independently measured capability.

rss · AIHot-Token羊毛 · Nov 16, 02:00

**「Qwen4-Max architecture and preview status」** According to the Qwen team&\#x27;s official blog, Qwen4-Max is built on a new Qwen4-series architecture with 2.4T backbone parameters, 71B activated per token, and an additional 328B N-gram Embedding parameters. Alibaba Cloud lists it as Qwen4-Max-Preview, a next-generation flagship multimodal model for text, image and video understanding and complex agentic tasks, while third-party coverage of the limited preview notes a 1-million-token context window, Token Plan access ending November 25, and a prohibition on backend use.

**「Impact」** Because the item provides no benchmarks, release date, or API availability, developers and organizations cannot yet assess compatibility or plan integration; the claimed specs should be checked against Qwen’s original blog post before any reliance.

<details><summary>References</summary>
<ul>
<li><a href="https://qwen.ai/blog?id=qwen4-max">Qwen4-Max: Your New Teammate Has Arrived</a></li>
<li><a href="https://xenospectrum.com/en/qwen4-max-preview-specs-limitations/">Alibaba&#x27;s Qwen4-Max Preview Offers a 1M-Token Context Window ...</a></li>
<li><a href="https://www.alibabacloud.com/help/en/model-studio/qwen4-max-preview">qwen4-max-preview (Latest Model) - Alibaba Cloud</a></li>

</ul>
</details>

**Tags**: `#LLM release`, `#Qwen`, `#model architecture`, `#long context`, `#AI agents`

---

<a id="item-tech-news-3"></a>
### [Reported Claude-Built DOS Language Model Fits in 435 KB on One Floppy](https://news.google.com/rss/articles/CBMijAFBVV95cUxQN3pOT0Ryc2VtbWhRa2thQmFPTjFPc0pIOTd3dUdJMHJjN2NPOExYVEhpNm9JbnpsdFhVZ3ZlamFOWDZOMU0wN1hzUHI0aHFrdER1NTlnUmZFVEhHRU1JS0JzTTBSRTcwSDlmRk90aEF5Q2htb2F5ZVk4WTVLZkREXzZ5RFh0ZTBCc3VYNg?oc=5) ⭐️ 5.0/10

Pasquale Pillitteri&\#x27;s item reports a language model built with Claude that runs under DOS and fits in 435 KB, small enough for a single floppy disk. The supplied content contains only the headline and metadata, so the model&\#x27;s architecture, training data, benchmarks, and whether it runs on real DOS hardware remain unverified. On the available evidence it is a retro-computing hobbyist demo rather than a confirmed technical breakthrough, and the 435 KB figure is a headline claim, not an independently measured result.

google\_news · Pasquale Pillitteri · Nov 15, 18:08

**「Background」** Floppy disks were the standard removable storage of the DOS era, with common capacities ranging from a few hundred kilobytes up to about 1.44 MB, which is why a 435 KB model is described as fitting on one. The supplied source contains only the headline and metadata, so the model&\#x27;s architecture and the claimed Claude-assisted build process cannot be verified; the author&\#x27;s own site identifies Pasquale Pillitteri as a software engineer based in Palermo.

<details><summary>References</summary>
<ul>
<li><a href="https://pasqualepillitteri.it/es/tools/image-to-pdf">Image to PDF - Convert Images to PDF Document | Pasquale Pillitteri</a></li>

</ul>
</details>

**Tags**: `#language models`, `#DOS`, `#retro computing`, `#AI-assisted development`, `#small models`

---