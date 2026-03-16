📘 Week 2: AI/ML Environment Setup & Deep Learning Foundations

Dates: March 15 - March 21, 2026
Status: 🟡 In Progress
Dates: March 8 - March 14, 2026 Status: 🟡 In Progress

🎯 Week 2 Goals

    Set up complete Python data science environment

    Master Object-Oriented Programming (OOP) in Python

    Deep dive into NumPy for neural network math

    Learn data preprocessing with Pandas

    Create advanced visualizations with Matplotlib/Seaborn

    Install and test PyTorch with GPU support (if available)

    Build first neural network from scratch

    Document everything with clear reflections

    📅 Daily Log
Day 8 (March 15) - Environment Setup & OOP Introduction

✅ Environment Setup Completed:

    Updated Python to latest version (3.11+)

    Created isolated virtual environment for ML projects

python -m venv ml_env
source ml_env/bin/activate  # (Mac/Linux)
Installed core ML libraries:
pip install --upgrade pip
pip install numpy pandas matplotlib seaborn jupyter
pip install torch torchvision torchaudio  # PyTorch
pip install scikit-learn  # For ML utilities

Verified installations:
import numpy as np
import pandas as pd
import torch
import sklearn
print(f"NumPy version: {np.__version__}")
print(f"PyTorch version: {torch.__version__}")
print("✅ All libraries installed successfully!")

📚 OOP Foundations Learned:

    Classes and Objects

    __init__ constructor method

    Instance methods vs class methods

    Inheritance and polymorphism

  # My first AI-ready class
class NeuralLayer:
    def __init__(self, input_size, output_size):
        self.input_size = input_size
        self.output_size = output_size
        # We'll add weights and biases tomorrow!
        
    def __str__(self):
        return f"NeuralLayer(input={self.input_size}, output={self.output_size})"

# Test it
layer = NeuralLayer(784, 128)
print(layer)

he environment felt familiar after Week 1, but now it's more purposeful. Every library installed is a tool for the black box journey. OOP is clicking—I can see how neural networks are built from small, reusable pieces.

🔧 Challenges Faced:

    PyTorch installation on old MacBook needed the right version (CPU-only)

    Solved by checking official docs and using compatible build

Day 9 (March 16) - NumPy Deep Dive for Neural Networks

📊 Today's Focus: Linear algebra foundations for deep learning

✅ NumPy Mastery:

    Array creation and manipulation

    Broadcasting rules

    Matrix operations (dot product, transpose, inverse)

    Random number generation for weights

    Reshaping and indexing

💻 Practice Code:
python

import numpy as np

# Simulating a neural network layer
input_data = np.array([[1, 2, 3], [4, 5, 6]])  # Batch of 2 samples
weights = np.random.randn(3, 4)  # 3 inputs → 4 outputs
bias = np.zeros(4)

# Forward pass (matrix multiplication)
output = np.dot(input_data, weights) + bias
print(f"Input shape: {input_data.shape}")
print(f"Weights shape: {weights.shape}")
print(f"Output shape: {output.shape}")
print(f"Sample output:\n{output}")

🧠 Reflection:
NumPy is the language neural networks speak. Understanding broadcasting and matrix multiplication today felt like learning the alphabet before writing sentences. The random weights initialization is exactly how real networks start—completely random, then they learn.

📸 Screenshots Added:
https://../images/day9-numpy-operations.png
Day 10 (March 17) - Coming Soon: Pandas for Data Preparation

Plan: Load real dataset, clean it, prepare for neural network training
Day 11 (March 18) - Coming Soon: Data Visualization Mastery

Plan: Create publication-quality plots with Matplotlib/Seaborn
Day 12 (March 19) - Coming Soon: PyTorch Tensors & Autograd

Plan: Understand computational graphs and automatic differentiation
Day 13 (March 20) - Coming Soon: First Neural Network in PyTorch

Plan: Build, train, and evaluate a simple classifier
Day 14 (March 21) - Coming Soon: First Look Inside - Activation Visualization

Plan: Capture and visualize internal activations (first interpretability step!)
📚 Resources Used This Week

    PyTorch Official Tutorials: https://pytorch.org/tutorials/

    NumPy Quickstart: https://numpy.org/doc/stable/user/quickstart.html

    Python OOP Documentation: https://docs.python.org/3/tutorial/classes.html

    Fast.ai Course (starting soon)

    3Blue1Brown Neural Networks playlist

🧠 Key Learnings So Far
Concept	Status	Application
Virtual Environments	✅ Mastered	Isolated ML projects
OOP in Python	✅ Solid	Building blocks for neural nets
NumPy Broadcasting	✅ Understood	Efficient matrix operations
PyTorch Installation	✅ Done	Ready for deep learning
🔥 Weekly Commitment

    One commit a day. One concept mastered. One step closer to the black box.

📸 Proof of Work

https://../images/day8-env-setup.png
https://../images/day8-oop-layer.png
https://../images/day9-numpy-operations.png
🔜 Next Week Preview

Week 3: Building and Training Neural Networks + First Interpretability Experiments

Last updated: March 16, 2026 | Dhaka → Kuala Lumpur (soon)

This is ready to post, Sam! Just replace the image paths with your actual screenshot filenames. Let me know if you want me to adjust anything. 🚀

