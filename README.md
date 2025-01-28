# PyTorch Examples Repository

This repository showcases general examples and implementations in **PyTorch**, focusing on various machine learning and deep learning tasks. These examples are designed for educational purposes, ensuring no private or proprietary information is included from any consulting engagements. The repository provides practical demonstrations for applying PyTorch to domains such as NLP, Computer Vision, and general-purpose machine learning, with GPU acceleration using A100 GPUs in Google Colab and PyTorch 2.5.1+cu121.

## Overview

This repository includes the following key projects:

1. **Computer Vision with PyTorch**:
   - Example workflows for tasks such as image classification.
   - Code is available in `ComputerVision_PyTorch.ipynb`.

2. **PyTorch Classification**:
   - Covers classification tasks with PyTorch, showcasing workflows and exercises.
   - Files include `PyTorch_Classification.ipynb`, `Copy_of_PyTorch_Classification.ipynb`, and `PyTorch_cvlassification_exercises.ipynb`.

3. **PyTorch Tensors Introduction**:
   - Introduction to PyTorch tensors and their operations.
   - Explore the basics in `PyTorch_Tensor_Intro.ipynb`.

4. **Workflow Examples**:
   - Demonstrates end-to-end workflows for PyTorch projects.
   - Available in `PyTorch_Workflow.ipynb`.

5. **Positional Encodings in PyTorch**:
   - Demonstrates the role of positional encodings in sequence modeling tasks such as Natural Language Processing (NLP) and Time-Series Analysis.
   - Includes sinusoidal positional encoding implementation and visualization.
   - Code is available in `Positional_Encodings.ipynb`.

6. **Educational Purpose**:
   - All examples are generalized and anonymized.
   - No sensitive or private information is included, ensuring full compliance with confidentiality requirements from past projects.

## Requirements

- Python 3.11
- Jupyter Notebook
- PyTorch 2.5.1+cu121
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

4. Select the desired project notebook to explore its implementation.

## GPU Acceleration

- All examples were tested with GPU acceleration using the NVIDIA A100 GPU in Google Colab.
- The configurations ensure optimal performance for machine learning and deep learning tasks.

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
