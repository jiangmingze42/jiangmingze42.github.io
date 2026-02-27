---
title: "LightRefine-PCXR: A Lightweight Refinement Framework for Efficient Medical Device Suppression in Pediatric Chest X-Rays"
collection: publications
category: conferences
permalink: /publication/2026-02-13-lightrefine-pcxr
excerpt: "A lightweight refinement framework for suppressing medical devices in pediatric chest X-rays to improve downstream clinical analysis."
date: 2026-02-13
venue: "Medical Imaging with Deep Learning (MIDL) 2026"
paperurl: "https://openreview.net/pdf?id=nixf7QdyXX"
slidesurl: ""
bibtexurl: ""
citation: "Mingze Jiang, Xueyang Li, John Kheir, Alec Girten, and Yiyu Shi. (2026). \"LightRefine-PCXR: A Lightweight Refinement Framework for Efficient Medical Device Suppression in Pediatric Chest X-Rays.\" <i>Medical Imaging with Deep Learning (MIDL)</i>."
---
In pediatric chest radiography, indwelling support devices (e.g., tubes and lines) are ubiq
uitous and often obscure critical thoracic structures, complicating radiologic interpretation
and reducing the reliability of automated analysis methods. Although generative inpainting
has advanced rapidly, reliable deployment in pediatric chest radiographs remains challeng
ing. Subtle anatomical cues must be preserved under substantial domain shift, while full
adaptation of large backbones is often impractical because of limited pediatric data and
constrained clinical compute budgets. To address these limitations, we propose LightRefine
PCXR, a lightweight, backbone-agnostic refinement framework for suppressing medical de
vices in pediatric chest X-rays (PCXRs). LightRefine-PCXR follows a two-stage strategy:
a frozen pretrained inpainting backbone first produces a coarse device-removed estimate,
and a compact anatomy-aware refiner then predicts mask-constrained residual corrections
to restore local structures while preserving all unmasked pixels exactly. This plug-in design
substantially reduces trainable parameters and peak GPU memory compared with end-to
end fine-tuning, yet consistently improves reconstruction fidelity and perceptual quality
across diverse inpainting paradigms, including CNN-, transformer-, and diffusion-based
models. Comprehensive in-domain and cross-dataset experiments demonstrate robust de
vice suppression and strong generalization in low-data pediatric settings, highlighting the
practicality of LightRefine-PCXR for real-world pediatric radiology workflows. Our model
will be publicly available upon acceptance.
