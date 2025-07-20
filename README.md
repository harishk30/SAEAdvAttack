Adversarial Attack Detection on ResNet-18 via Sparse Autoencoder Feature Analysis

Final Project for COS 485 (Neural Networks) 

Abstract:

Adversarial perturbations undermine the reliability of vision-based models that
now steer cars, evaluate medical scans, and power multimodal agents that operate
computers. We introduce a lightweight, interpretable defense system that flags
such perturbations at the feature level, before malicious signals hijack downstream
classification. Our method clamps over-complete sparse autoencoders (SAEs)
after every block of a pretrained ResNet-18, and trains them on clean CIFAR-10
activations. The first SAE’s sparse codes are found to separate clean and adversarial
inputs almost linearly. Exploiting this property, we fit a logistic detector on the
top-k high-activation neurons of the clean representation, and train the detector only
on the FGSM attack. Trained only on FGSM, the detector generalizes zero-shot
to stronger attacks, detecting PGD, DeepFool, and CW at 95%, 86%, and 68%
accuracy. This performance matches and surpasses distance-based baselines for
several of the attacks, showing how interpretable methods can be a cruicial step in
preventing adversaries.

Paper:

https://drive.google.com/file/d/1RGbgRQuLjq6u2siMKmiXUiZq2mqxovX6/view?usp=sharing

