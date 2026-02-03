# Self-Attentive Deep Fusion Framework with Transformer-Based Semantics for Emergency Head CT Reporting

This repository hosts the source code of our self-attentive deep fusion framework designed for automatic radiology reporting in emergency head CT imaging. Building upon our previous work (https://github.com/S3l11/HeadCTRadRepo), this reengineered system improves contextual understanding. 

For more details, please *refer to our related publication*:

> **Tomassini, S., Zeggada, A., Quattrocchi, C. C., Melgani, F., & Giorgini, P.** (2025). *Self-Attentive Deep Fusion Framework with Transformer-Based Semantics for Emergency Head CT Reporting*. **IEEE International Conference on Metrology for eXtended Reality, Artificial Intelligence and Neural Engineering (MetroXRAINE)**. DOI: 10.1109/MetroXRAINE66377.2025.11340501.

---

# Abstract

Head Computed Tomography (CT) scans are commonly used in emergency departments to identify neurological conditions. However, manual radiology reporting is time-consuming and subject to cognitive biases, especially under time constraints. This work presents a self-attentive deep fusion framework for automatic radiology reporting tailored to emergency head CT imaging. Building on our previously developed system, the proposed model incorporates clinically validated preprocessing for head CTs, a multimodal neural network refined through fine-grained regularization, and intra-sequence self-attention to enhance context modeling. Eight uniformly resampled slices per scan are used as input, and each report section is generated as an independent caption and semantically ranked using a Transformer-based evaluator based on perplexity. The best predictions are concatenated to form ordered reports. The model was trained and evaluated on a dataset of real-world emergency head CTs using ROUGE-L and METEOR as quantitative metrics. The proposed system achieved improvements of +6% in ROUGE-L and +3% in METEOR compared to the reference architecture, and +4% and +2% compared to the same model without self-attention. These results confirm the contribution of self-attention for improving contextual coherence and report quality. The framework remains lightweight and scalable, making it suitable for time-sensitive environments. Future work will explore condition-specific modeling and vision-language model integration.

# Data & Code

- **Data**: Raw data are *private* due to patient confidentiality and cannot be shared.  
- **Code**: Full code is *available* upon request.

For more information, please *contact the corresponding author*.  

# Requirements
- **Python**: 3.9+  
- **TensorFlow**: 2.15+  
- **Memory**: 24+ GB RAM / 40+ GB VRAM

# Terms of use
If you use this code (or part of it) in your research, please *cite the original paper*.  
