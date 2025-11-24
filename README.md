# dcgananalysis
Implementation and analysis of DCGAN experiments on MNIST database, including baseline DCGAN, ReLU variants, and systematically exploring hyperparameters.

## Project Overview

The goal of this project is to generate realistic handwritten digit images (0–9) using a DCGAN and to analyze how architectural and training changes affect performance. All experiments use the **MNIST** dataset.

- **Implement the baseline DCGAN** (based on the official TensorFlow DCGAN tutorial) and examine the effect of training for different numbers of epochs (10, 50, 100).
- **Modify the generator activations** to use ReLU (instead of LeakyReLU) for the hidden layers, and compare to the baseline at 50 epochs.
- **Explore multiple hyperparameters** (noise vector dimensionality, batch size, learning rate, momentum terms) and analyze their impact on:
   - Visual quality of generated images.
   - Training stability and speed (time to complete 50 epochs).

---

## Dataset: MNIST

**MNIST** is a benchmark dataset of handwritten digits, consisting of:

- **60,000** training images  
- **10,000** test images  
- Grayscale, **28 × 28** pixels  
- Digit classes: **0–9**

In this project, MNIST serves as the real data distribution that the DCGAN tries to learn to imitate.

---
