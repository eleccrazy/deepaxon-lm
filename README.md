# DeepAxon-LM: Axon Segmentation in Light Microscopy Images

**DeepAxon-LM** is a deep learning pipeline for segmenting axons in peripheral nerve tissue captured with **light microscopy (LM)**. The project is focused on clinical and experimental applications in nerve regeneration, with support for training, evaluation, and visualization of axon segmentation models — starting from synthetic data and moving to real-world LM datasets.

---

## Project Goals

- Build a robust U-Net-based segmentation model for binary classification (axon vs. background)
- Start with synthetic data and later apply to real annotated LM datasets
- Provide tools for training, evaluating, and visualizing segmentation results
- Serve as the foundation for a future open-source tool usable in clinical and research settings

---

## Project Structure
```plaintext
deepaxon-lm/
├── notebooks/          # Jupyter notebooks for prototyping
├── data/               # Synthetic and real datasets
├── src/                # Code modules: models, loaders, metrics, utils
├── saved_models/       # Trained model checkpoints
├── outputs/            # Visual overlays, metrics, logs
├── requirements.txt    # Project dependencies
└── README.md           # Project overview (you are here)
```
---

## Features

-  Synthetic dataset generation (axon-like shapes)
-  U-Net model architecture (PyTorch)
-  Dice and IoU metrics
-  Patch-based training pipeline
-  Visual overlay generation for predictions
-  Integration with real LM datasets (once approved)
-  CLI or web app for easy clinical usage

---

## Setup Instructions

```bash
# Clone the repository
git clone https://github.com/eleccrazy/deepaxon-lm.git
cd deepaxon-lm

# Install dependencies (to be defined)
pip install -r requirements.txt
