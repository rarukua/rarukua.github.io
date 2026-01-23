---
layout: project
title: COMIMS-miRNA
description: Transformer-based miRNA–mRNA interaction prediction using CLASH-seq
category: work
importance: 1
thumbnail: assets/img/projects/comims/overview.png
---
## Overview

COMIMS-miRNA is a transformer-based framework for predicting miRNA–mRNA interactions across the full transcript, integrating CLASH-seq validated chimeric reads.

![Overview](assets/img/projects/comims/overview.png)

---

## Model Architecture

The model uses dual T5-style encoders with contrastive learning and EMA distillation to capture non-canonical interactions.

![Model](assets/img/projects/comims/model.png)

---

## Results

COMIMS outperforms existing tools across multiple benchmarks and transcript regions.

![Results](assets/img/projects/comims/results.png)

---

## Key Contributions

- Transcript-wide miRNA target prediction (CDS, UTR3)
- CLASH-seq–driven supervision
- Attention heatmap interpretability
