# Deep-Generative-Models-research


[HUFS_Deep-Generativae-Models-research Team_Notion](https://www.notion.so/10b0afd4e0c58027a322f0ae2744d80e)


ADPDiT: A Multimodal Diffusion Transformer 
for Predicting Alzheimer's Disease Progression and Generating Brain Image


Abstract 


ADPDiT (Alzheimer’s Disease Progression Diffusion Trans-
former) is a novel multimodal framework that integrates brain MRI data
with structured textual metadata to predict Alzheimer’s disease (AD)
progression and generate personalized, progression-conditioned AD brain
images. AD is a progressive neurodegenerative disorder with complex
pathology, and conventional single-modality diagnostic approaches such
as brain imaging or cognitive assessments fail to capture its full complex-
ity. To overcome these limitations, ADPDiT employs a diffusion trans-
former with cross-attention modules to effectively fuse patient-specific
anatomical features with auxiliary metadata. The model also leverages
a VAE-based latent space and incorporates Rotary Position Encoding
(RoPE) to enhance the alignment between image and text embeddings,
thereby accelerating convergence and improving accuracy. In this study,
brain MRI data from 1,171 participants in the Alzheimer’s Disease Neu-
roimaging Initiative (ADNI) dataset, comprising 377 cognitively normal
individuals, 540 mild cognitive impairment cases, and 254 AD patients,
were used for training and evaluation. The dataset was rigorously pre-
processed with image alignment, normalization, spatial resolution adjust-
ment, and histogram equalization to ensure high-quality inputs. Addi-
tionally, clinical metadata including cognitive test scores (MMSE, CDR,
etc.) were embedded in the latent space to guide the generative process.
By combining multimodal conditioning with transformer-based diffusion
modeling, ADPDiT offers a comprehensive approach to AD diagnosis and
research, providing insights into disease progression and facilitating the
development of precision medicine tools for neurodegenerative disorders.
This study demonstrates that ADPDiT, through its integration of dif-
fusion processes and multimodal data, is a promising tool for advancing
precision medicine in the diagnosis and management of AD.



Keywords:

Alzheimer’s Disease (AD) · Text-Guided Image Generation
· Brain MRI Generation.

```markdown
# Benchmark Research 
Frequency-Controlled Diffusion Model for Versatile Text-Guided Image-to-Image Translation (AAAI 2024)
Diffusion-based: DiffusionCLIP (CVPR 2022)
Stable Diffusion (CVPR 2022)
Hybrid GAN-VAE: VQGAN-CLIP (ECCV 2022)
U-Net-like: SwinUNETR-V2 (MICCAI 2023)
```
