# Large Multimodal Models as General In-Context Classifiers

> **CVPR Findings 2026**

**[Marco Garosi](https://www.marcogarosi.it/) · [Matteo Farina](https://farinamatteo.github.io/) · [Alessandro Conti](https://alessandroconti.me/) · [Massimiliano Mancini](https://mancinimassimiliano.github.io/) · [Elisa Ricci](https://eliricci.eu/)**

*University of Trento · Fondazione Bruno Kessler*

---

[![Project Page](https://img.shields.io/badge/Project%20Page-circle--lmm.github.io-blue?style=flat-square)](https://circle-lmm.github.io/)
[![Paper](https://img.shields.io/badge/arXiv-2602.23229-b31b1b?style=flat-square)](https://arxiv.org/abs/2602.23229)
[![Code](https://img.shields.io/badge/Code-GitHub-green?style=flat-square)](https://github.com/marco-garosi/CIRCLE)
[![License](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/)

---

## About This Repository

> **This is the repository for the [project website](https://circle-lmm.github.io/) only.**
> The paper code is available at **[github.com/marco-garosi/CIRCLE](https://github.com/marco-garosi/CIRCLE)**.

---

## Abstract

Which multimodal model should we use for classification? Previous studies suggest that the answer lies in CLIP-like contrastive Vision-Language Models (VLMs), due to their remarkable zero-shot performance. In contrast, Large Multimodal Models (LMMs) are considered more suitable for complex tasks.

In this work, we argue that this view *overlooks* a key capability of LMMs: **in-context learning**. We benchmark state-of-the-art LMMs on diverse datasets for closed-world classification and find that, although their zero-shot performance is lower than CLIP's, LMMs with a few in-context examples can **match or even surpass** contrastive VLMs with cache-based adapters.

We extend this analysis to the open-world setting and propose **CIRCLE** — a simple, *training-free* method that assigns pseudo-labels to in-context examples and iteratively refines them. CIRCLE establishes a robust baseline for open-world classification, surpassing VLM counterparts and highlighting the potential of LMMs as unified, flexible classifiers.

---

## BibTeX

```bibtex
@inproceedings{garosi2026circle,
  title={Large Multimodal Models as General In-Context Classifiers},
  author={Garosi, Marco and Farina, Matteo and Conti, Alessandro and Mancini, Massimiliano and Ricci, Elisa},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Findings},
  year={2026}
}
```

---

## Website

This site is built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template) and licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
