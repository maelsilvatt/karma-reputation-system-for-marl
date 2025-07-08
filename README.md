# The Hyperbolic Karma Model for MARL

The **Hyperbolic Karma Model** is a novel reputation system designed to simulate and analyze the evolution of social behavior in multi-agent environments. Inspired by hyperbolic geometry and fiber bundle theory, the model captures moral nuance, contextual variability, and vulnerability dynamics that are often overlooked by traditional scalar reputation systems.

This model is a central contribution of the project and is detailed in the upcoming paper:

> **"Hyperbolic Modeling of Reputation: Karma as a Poincaré Disk Fiber Bundle"**  
> [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15838990.svg)](https://doi.org/10.5281/zenodo.15838990)

📄 Preprint available at: [https://zenodo.org/records/15838990](https://zenodo.org/records/15838990)

---

## 🧠 Key Concepts

### ▪️ State Space: Poincaré Disk

Each agent's karma is represented as a complex number `z` in the **Poincaré disk**:

- `|z|` (magnitude): Indicates the **strength** or **intensity** of reputation.
- `arg(z)` (angle): Represents the agent's **moral orientation**.

This formulation allows for a continuous and geometrically meaningful representation of character traits and reputational states.

---

### ▪️ Hyperbolic Metric

Reputation distances are computed using the **hyperbolic metric**:

- Allows the model to express **moral vulnerability**, where agents with high reputations are more sensitive to small transgressions.
- Captures non-linear dynamics in trust and social decay.

Mathematically, this enables sharp distinctions in moral perception with small behavioral differences—something Euclidean metrics fail to reflect.

---

### ▪️ Fiber Bundle Structure

To capture **contextual incommensurability** (e.g., *professional* vs. *personal* reputation), the model extends the karma space into a **fiber bundle**:

- The base space (Poincaré disk) encodes general moral orientation.
- Each point has a corresponding **fiber** encoding **context-specific** reputation traits.

This allows for an agent to be, for example, professionally admired while morally distrusted in a personal context—without conflating the two.

---

### ▪️ Stochastic Dynamics

The evolution of an agent’s karma is governed by a **stochastic differential equation (SDE)**:

- Simulates **moral recovery**, **reputational collapse**, and **contextual realignment** over time.
- Includes both deterministic drift and random fluctuations.

This approach enables realistic modeling of **moral trajectories** under uncertainty and social feedback.

---

## ✅ Experimental Validation

The Hyperbolic Karma Model has been validated through computational simulations in Jupyter Notebooks:

- Demonstrates **high sensitivity** of consolidated reputations to small moral changes.
- Reveals **geodesic symmetry** between moral extremes (e.g., saints vs. villains).
- Shows how **context-specific fibers** evolve independently under distinct pressures.
- Simulates **complex, emergent dynamics** over time.

---

## 🛠 Technologies Used

- **Mathematical Modeling**: Complex Analysis, Differential Geometry
- **Simulation**: Python, NumPy
- **Visualization**: Matplotlib
- **Documentation**: LaTeX (for the formal paper)

---

## 📄 License

This model is part of the *BuriedBrains* project and is released under the MIT License. See the [LICENSE.md](LICENSE.md) file for more information.

## How to Cite

If you use this work or the **Hyperbolic Karma Model** in your research, please cite the following paper:

```
Silva, I. S. da. (2025). Hyperbolic Modeling of Reputation: Karma as a Poincaré Disk Fiber Bundle. Zenodo. https://doi.org/10.5281/zenodo.15838990
```

### BibTeX

```bibtex
@misc{silva2025hyperbolic,
  author       = {Silva, Ismael S. da},
  title        = {Hyperbolic Modeling of Reputation: Karma as a Poincaré Disk Fiber Bundle},
  publisher    = {Zenodo},
  year         = {2025},
  doi          = {10.5281/zenodo.15838990},
  url          = {https://doi.org/10.5281/zenodo.15838990}
}
```

---

## 👤 Author

**Ismael S. Silva**  
Undergraduate Researcher  
Federal University of Ceará (UFC)  
📧 ismaelsoares.pro@alu.ufc.br
