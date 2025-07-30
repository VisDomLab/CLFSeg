# CLFSeg: A Fuzzy-Logic based Solution for Boundary Clarity and Uncertainty Reduction in Medical Image Segmentation

📢 **Accepted at 36th British Machine Vision Conference (BMVC) 2025**


## 🧠 Overview

**CLFSeg** is an encoder-decoder-based deep learning framework designed to improve medical image segmentation, especially in boundary-ambiguous and uncertain anatomical regions. Our key contribution is the **Fuzzy-Convolutional (FC) Module**, which leverages convolutional layers and fuzzy logic to enhance robustness, clarity, and efficiency in medical segmentation tasks.

The model achieves **SOTA performance** across polyp and cardiac segmentation tasks using:
- Fuzzy reasoning in convolution
- ConvGLU for enhanced gating
- Dice + BCE hybrid loss to address class imbalance

---


## 📄 Paper

Coming soon...  
Check our [Project Page](https://visdomlab.github.io/CLFSeg/) for updates.

---

## 🗃️ Datasets & Weights

We trained and evaluated CLFSeg on four publicly available datasets:

| Dataset | Download Link | Trained Weights |
|--------|----------------|------------------|
| CVC-ColonDB | *Coming Soon* | *Coming Soon* |
| CVC-ClinicDB | *Coming Soon* | *Coming Soon* |
| ETIS-LaribPolyp | *Coming Soon* | *Coming Soon* |
| ACDC | *Coming Soon* | *Coming Soon* |

---

## 📊 Architecture Overview

### Main Encoder-Decoder Design

![CLFSeg Architecture](CLFSeg_Refine.png)

### FC Module Internals

![FC Module](FC_Module.png)

---
