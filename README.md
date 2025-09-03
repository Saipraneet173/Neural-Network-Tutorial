# 🧠 Neural Network Architecture Showdown on MNIST

## Accuracy vs Energy Efficiency: Finding the Sweet Spot

Ever wondered which neural network architecture gives you the best bang for your computational buck? This project dives deep into comparing four different architectures - not just for accuracy, but also for their energy footprint (because let's face it, training models shouldn't cost the earth, literally).

---

## 📋 What's This About?

This tutorial walks through implementing and comparing **MLP**, **CNN**, **RNN**, and **SNN** (yes, Spiking Neural Networks!) on the classic MNIST dataset. But here's the twist - instead of just chasing accuracy numbers, I explore the trade-offs between model performance and training efficiency.

### Why Should You Care?

- 🎯 **Real-world applicable**: In production, you need models that are both accurate AND efficient
- ⚡ **Energy-conscious ML**: With growing concerns about AI's carbon footprint, efficiency matters
- 🧪 **Comprehensive comparison**: Side-by-side analysis of fundamentally different architectures
- 🦾 **Includes SNNs**: Explores bio-inspired computing that most tutorials skip

---

## 🚀 Quick Start

### Prerequisites

```bash
pip install torch torchvision matplotlib numpy snntorch pandas
```

### Running the Tutorial

1. Clone this repository:
```bash
git clone https://github.com/Saipraneet173/Neural-Network-Tutorial.git
cd neural-architecture-comparison
```

2. Open the Jupyter notebook:
```bash
jupyter notebook AI_Coursework.ipynb
```

3. Run all cells sequentially (grab a coffee while the models train! ☕)

---

## 🏗️ Architecture Line-up

### The Contenders

| Model | What Makes It Special | Best For |
|-------|----------------------|----------|
| **MLP** | Simple, fast, no-frills fully connected layers | Quick baseline, simple patterns |
| **CNN** | Spatial feature extraction with convolutions | Image recognition tasks |
| **RNN** | Sequential processing (treats image rows as sequences) | Demonstrating temporal processing |
| **SNN** | Bio-inspired spike-based computation | Energy-efficient inference |

---

## 📊 Key Findings

Without spoiling all the fun (run the notebook yourself!), here's what emerged:

- **CNN** dominates in accuracy (as expected for image tasks)
- **MLP** surprises with its speed-to-accuracy ratio
- **SNN** shows promise for energy-efficient computing
- **RNN** demonstrates that not every architecture fits every problem

### Sample Results Preview

The notebook generates comprehensive comparisons showing:
- Accuracy vs Training Time trade-offs
- Impact of different optimizers (Adam vs SGD)
- Learning rate sensitivity analysis
- Beautiful visualizations that actually tell a story

---

## 🎓 Learning Objectives

By working through this tutorial, you'll understand:

1. **Implementation details** of four fundamentally different neural architectures
2. **PyTorch patterns** for clean, reusable model code
3. **Evaluation beyond accuracy** - why efficiency metrics matter
4. **Hyperparameter impacts** through systematic experimentation
5. **Visualization techniques** for comparing multiple models

---

## 📂 Project Structure

```
.
├── AI_Coursework.ipynb   # Main tutorial notebook
├── README.md             # You're reading this!
├── data/                 # MNIST dataset (auto-downloaded)
└── figures/              # Generated plots and visualizations
```

---

## 💡 Key Insights & Design Decisions

### Why These Four Models?

Each represents a different paradigm in neural computation:
- **MLP**: The foundational building block
- **CNN**: Spatial hierarchy learning
- **RNN**: Temporal/sequential processing
- **SNN**: Next-gen bio-inspired computing

### Training Time as Energy Proxy

While not perfect, training time correlates strongly with computational cost and energy usage. This makes our comparison practical for resource-constrained environments.

### Default Hyperparameters

All models use Adam optimizer (lr=0.001) and batch_size=64 by default to ensure fair comparison. The notebook includes code to experiment with variations.

---

## 🔬 Extending This Work

Some ideas to take this further:

- **Hybrid architectures**: What about CNN-SNN combinations?
- **Other datasets**: How do these patterns hold for CIFAR-10 or custom data?
- **Actual energy measurement**: Use tools like CodeCarbon for real power consumption
- **Deployment comparison**: Which model performs best on edge devices?
- **Quantization effects**: How does model compression affect the accuracy-efficiency trade-off?

---

## 📚 References & Acknowledgments

This project builds on foundational work in deep learning and neuromorphic computing. Key references include:

- LeCun et al. (1998) - Original CNN work on MNIST
- Goodfellow, Bengio & Courville (2016) - Deep Learning fundamentals
- Eshraghian et al. (2021) - SNNTorch framework and SNN training methods

Special thanks to the PyTorch and SNNTorch communities for excellent documentation and tools.

---

## 🤝 Contributing

Found a bug? Have an idea for improvement? Feel free to:

1. Open an issue describing what you'd like to change
2. Fork the repository
3. Create a pull request with your improvements

All contributions welcome - from typo fixes to new model architectures!

---

## 📝 License

This project is open source and available under the MIT License. Use it, modify it, learn from it!

---

## 👤 Author

Created as part of Advanced AI Systems coursework (24COC102) at Loughborough University.

**Connect with me:**
- GitHub: [@Saipraneet173](https://github.com/Saipraneet173)
- LinkedIn: [Saipraneet Darla](https//www.linkedin.com/in/saipraneet-darla-1a0838255)

---

*If you found this helpful, consider giving it a ⭐ on GitHub!*
