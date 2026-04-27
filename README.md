# AKRM: An Inference-Time Control Framework for Hallucination Reduction in Large Language Models

AKRM is a lightweight inference-time control framework designed to reduce hallucination in large language models without retraining or modifying model parameters.

## Core Idea

Hallucination is treated as a decoding-time instability regime rather than only a confidence failure.

AKRM estimates an epistemic reliability score μ during generation and computes:

```math
K(\mu)=4\mu(1-\mu)# AKRM-Hallucination-Control
An inference-time control framework for hallucination reduction in large language models.
The instability score reaches its maximum at μ = 0.5, corresponding to maximal conflict among competing continuations.

Main Components
Reliability estimation
Instability detection
Refusal gating
Recursive state smoothing
Proper Exit Trigger / controlled abstention
Paper

Preprint: [ADD ZENODO LINK]
DOI: [ADD DOI]

Status

This repository currently contains the paper materials and will be expanded with an AKRM-lite implementation.

Citation
@misc{akin2026akrm,
  author = {Akin, Enes},
  title = {AKRM: An Inference-Time Control Framework for Hallucination Reduction in Large Language Models},
  year = {2026},
  publisher = {Zenodo},
  doi = {ADD DOI},
  url = {ADD ZENODO LINK}
}
License

MIT License


Altta **Commit changes** de.

## 4. PDF ve görsel yükle

Repo ana sayfasına dön.  
**Add file → Upload files** seç. GitHub resmi dokümanında da dosya yüklemek için repo ana sayfasında “Add file” menüsünden “Upload files” seçileceği yazıyor. :contentReference[oaicite:1]{index=1}

Şunları yükle:

Add paper PDF and infographic

```text
AKRM_preprint.pdf
akrm_infographic.png
