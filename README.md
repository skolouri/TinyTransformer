# Tiny Transformer

This repository contains a minimal yet functional implementation of a Transformer architecture featuring both an **encoder** and a **decoder**. The design prioritizes clarity and simplicity, making it an ideal resource for educational purposes and experimentation in both **vision** and **natural language processing (NLP)** applications.

## Overview

- **Minimalist Design**: Focuses on core components of a Transformer without unnecessary complexity.
- **Encoder-Decoder Architecture**: Implements both encoder and decoder stacks as in the original Transformer model.
- **Applications**: Demonstrates use cases in computer vision and NLP tasks.
- **Educational Focus**: Great starting point for students, researchers, and practitioners who want to understand Transformers from scratch.

## Contents

- `TinyTransformer.ipynb`: Main Jupyter notebook containing code and explanations.
- Example tasks and experiments for vision and NLP.

## Getting Started

### Requirements

- Python 3.8+
- `torch`
- `numpy`
- `matplotlib` (for visualizations)
- `tqdm` (optional, for progress bars)

You can install the dependencies with:

```bash
pip install torch numpy matplotlib tqdm
```

### How to Run

Simply open the notebook:

```bash
jupyter notebook TinyTransformer.ipynb
```

Follow the cells sequentially to build, train, and evaluate a minimal Transformer.

## Key Features

- Positional encoding
- Multi-head self-attention
- Encoder/decoder blocks
- Cross-attention between encoder and decoder
- Training examples for vision and text

## Motivation

Transformers are powerful but often introduced with overwhelming complexity. This project aims to **demystify** the Transformer architecture by building it piece by piece, showing how each component fits into the overall system.

## License

This project is released under the [MIT License](LICENSE).
