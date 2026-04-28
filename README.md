# Wasserstein GANs as Minimax Optimal Distribution Estimators

**Collaborators:** [Imade Bouftini](https://github.com/ibouftini) - Taha Boukaidi Laghzaoui - Hocine Aknouche • **Supervision:** [Claire Brecheteau](mailto:claire.brecheteau@univ-nantes.fr)

**Institution:** [École Centrale de Nantes](https://www.ec-nantes.fr/)

---

## Overview

This project studies the theoretical foundations of Wasserstein Generative Adversarial Networks (WGANs) through the lens of statistical estimation theory. The central question is whether WGANs achieve optimal convergence rates when used to estimate probability distributions.

The work is grounded in the paper *"Wasserstein Generative Adversarial Networks are Minimax Optimal Distribution Estimators"* (Stépanovitch, Aamari, Levrard, 2023). It shows that WGANs, under appropriate architectural and regularity conditions, match the minimax lower bounds for distribution estimation in Wasserstein distance. This is not just a performance result. It provides a principled justification for the WGAN objective from a statistical learning perspective.

The project covers two phases. The first builds a rigorous theoretical analysis of the convergence results and their proofs. The second implements and empirically validates those predictions.

## Documentation

- **[Full Report](final_report.pdf)** - Complete theoretical analysis and empirical validation

## Main References

- Stépanovitch, Aamari, Levrard (2023). *Wasserstein Generative Adversarial Networks are Minimax Optimal Distribution Estimators*
- Arjovsky, Chintala, Bottou (2017). *Wasserstein GAN*
- Villani (2009). *Optimal Transport: Old and New*
