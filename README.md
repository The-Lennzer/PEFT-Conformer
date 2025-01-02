# PEFT-Conformer

PEFT-Conformer is a fine-tuned Conformer model optimized for medical imaging tasks. It uses Parameter-Efficient Fine-Tuning (PEFT) techniques to achieve high performance across diverse medical datasets.

## Key Features
- **Dual Classifier Head**:
  - **Transformer Head**: Global feature extraction using class tokens.
  - **Convolutional Head**: Localized feature extraction using pooling and fully connected layers.
- **Generalization**: Performs well across multiple medical imaging modalities.
