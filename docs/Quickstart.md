# Quickstart — Local ANN Toolkit

This guide helps you get started with the Local ANN Toolkit for offline training and visualization.

Prerequisites
- Python 3.8+
- pip

1) Clone the repository
```bash
git clone <your-repo-url>
cd <repo-directory>
```

2) Create and activate virtual environment
```bash
python -m venv .venv
source .venv/bin/activate    # Linux/macOS
.venv\Scripts\activate       # Windows
```

3) Install dependencies
```bash
pip install -r requirements.txt
```

4) Run the XOR example
```bash
python examples/xor_example.py
```

5) Inspect visualizations
- Generated plots are saved to the `output/` directory by default. Open them with an image viewer or Jupyter.

Notes
- The toolkit is designed for educational use. For larger datasets, consider batching and memory limits.
- If you want, I can add a small Jupyter notebook `notebooks/mnist_tutorial.ipynb` demonstrating end-to-end training and visualization.
