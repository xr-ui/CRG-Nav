# CRG-Nav: Confidence-Aware Reasoning with Geometric Verification for Zero-Shot Object Navigation
---
 
## Overview
 
CRG-Nav addresses three core limitations of existing zero-shot object navigation methods:
 
- **Unreliable long-range perception** — distant observations are down-weighted via a Gaussian-decay confidence mechanism
- **Hallucination-induced decision bias** — perception (VLM + YOLO-World) is decoupled from decision-making (LLM), preventing perception errors from polluting high-level reasoning
- **Inaccurate stopping decisions** — a dual semantic-geometric verification module uses depth data to estimate 3D target distance before triggering a stop
[overview (1).pdf](https://github.com/user-attachments/files/26627337/overview.1.pdf)
