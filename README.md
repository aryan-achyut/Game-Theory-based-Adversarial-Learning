# Game-Theoretic Adversarial Training for Robust Statistical Models

This repository explores **game-theoretic adversarial training** to build statistical models that are robust to adversarial attacks. The core idea is to frame the training process as a **zero-sum game** between a defender (the model) and an attacker (the adversarial component introducing perturbations).

The project uses **scikit-learn** datasets to simulate adversarial attacks and evaluate the model's robustness across various perturbation levels. The model adapts through iterative training, similar to **Generative Adversarial Networks (GANs)**, where the adversary injects noise to maximize prediction errors, and the model adapts to minimize them.
