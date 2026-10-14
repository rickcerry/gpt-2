# GPT-2 Optimizer Comparison

This project was developed as part of the **DD2424 – Deep Learning in Data Science** course at KTH Royal Institute of Technology.

We implement and train GPT-2 to investigate the performance of three optimization algorithms:

- **AdamW**
- **Muon**
- **NorMuon (Neuron-wise Normalized Muon)**

The optimizers are evaluated on two tasks:
- **Text Generation:** Shakespearean sonnet generation.
- **Sentiment Classification:** Fine-grained sentiment classification using SST-5.

The study compares convergence speed, generalization performance, computational efficiency, and GPU memory usage.

## Results

Across both tasks, AdamW achieved the best validation performance, while Muon-based optimizers demonstrated faster training convergence in sentiment classification.

## Authors

- Riccardo A. Cerrone
- Simon Wigh
- Arif Iqbal

## Course

DD2424 – Deep Learning in Data Science  
KTH Royal Institute of Technology, 2026
