# PyTorch Examples Repository

This repository contains various examples and implementations in **PyTorch**, showcasing its versatility for machine learning and deep learning tasks. The repository serves as a resource for learning and applying PyTorch to different domains, including NLP, Computer Vision, and general-purpose machine learning.

## Overview

This repository includes the following key projects:

1. **Positional Encodings in PyTorch**:
   - Demonstrates the role of positional encodings in sequence modeling tasks such as Natural Language Processing (NLP) and Time-Series Analysis.
   - Includes sinusoidal positional encoding implementation and visualization.
   - Code is available in `Positional_Encodings.ipynb`.

2. **Additional PyTorch Examples (Future Additions)**:
   - More examples and tutorials will be added to cover other PyTorch use cases such as image classification, GANs, and reinforcement learning.

## Requirements

- Python 3.8+
- Jupyter Notebook
- PyTorch
- Matplotlib
- NumPy

Install the dependencies using the following command:

```bash
pip install torch matplotlib numpy
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/christophergaughan/PyTorch.git
   ```

2. Navigate to the project directory:
   ```bash
   cd PyTorch
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Select the desired project notebook (e.g., `Positional_Encodings.ipynb`) to explore its implementation.

## Projects

### Positional Encodings

- **Purpose**: Understand and implement positional encodings for transformer models.
- **Highlights**:
  - Sinusoidal positional encoding function implementation.
  - Visual representation of encoding patterns.
  - PyTorch-based integration example for sequence modeling.

### Future Additions

- Image classification models.
- Generative Adversarial Networks (GANs).
- Reinforcement learning tasks.

## References

- [PyTorch Documentation](https://pytorch.org)
- [Attention is All You Need](https://arxiv.org/abs/1706.03762): Transformer model paper introducing positional encodings.

## Author

Christopher Gaughan  
Feel free to connect or reach out for collaboration opportunities!

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Enjoy exploring PyTorch implementations! If you find this project helpful, don't forget to star the repository!

# Also from "Attention Is All You Need" paper:

# Positional Encodings in PyTorch

This repository contains an implementation of **Positional Encodings** in PyTorch, demonstrating their role in sequence modeling tasks such as Natural Language Processing (NLP) and Time-Series Analysis. The code is encapsulated in the Jupyter Notebook `Positional_Encodings.ipynb`.

## Overview

In transformer models, positional encodings are used to inject information about the position of tokens in a sequence, allowing models to capture sequential relationships. This notebook explores:

- **Why positional encodings are necessary** in transformer architectures.
- **Implementation of positional encodings** using PyTorch.
- **Visualization of sinusoidal encodings** to better understand their behavior.

## Features

- Explanation of positional encoding concepts.
- Sinusoidal positional encoding function implementation.
- Visual representation of positional encoding patterns.
- PyTorch-based example to integrate positional encodings into a transformer model.

## Requirements

- Python 3.8+
- Jupyter Notebook
- PyTorch
- Matplotlib
- NumPy

Install the dependencies using the following command:

```bash
pip install torch matplotlib numpy
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/christophergaughan/PyTorch.git
   ```

2. Navigate to the project directory:
   ```bash
   cd PyTorch
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Positional_Encodings.ipynb
   ```

4. Run the notebook cells to explore the implementation and visualizations.

## Key Functions

- **`generate_positional_encodings(d_model, max_len)`**: Generates sinusoidal positional encodings.
- **Integration Example**: Shows how to incorporate positional encodings into transformer-based models.

## Applications

- Enhancing transformer-based architectures for NLP tasks.
- Integrating positional encodings into time-series models.
- Understanding the theoretical foundation of transformers.

## References

- [Attention is All You Need](https://arxiv.org/abs/1706.03762): The seminal paper introducing transformer models and positional encodings.
- PyTorch Documentation: [https://pytorch.org](https://pytorch.org)

## Author

Christopher Gaughan  
Feel free to connect or reach out for collaboration opportunities!

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Enjoy exploring positional encodings! If you find this project helpful, don't forget to star the repository!
