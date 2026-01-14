# PyTorch Specialization

Course materials and assignments from the PyTorch for Deep Learning specialization by DeepLearning.AI.

## Repository Structure

```
pytorch-specialisation/
├── 1. pytorch fundamental/
│   ├── module1_getting_started_with_pytorch/
│   ├── module2_pytorch_workflow/
│   ├── module3_data_management/
│   └── module4_core_neural_network/
├── 2. pytorch tech and ecosystem tools/
└── 3. advanced arch and deployment/
```

## Installation

**Using uv (recommended):**
```bash
git clone https://github.com/isarwarfp/pytorch-specialisation.git
cd pytorch-specialisation
uv sync
```

**Or with pip:**
```bash
pip install -r requirements.txt
```

## Running the Notebooks

Start Jupyter:
```bash
jupyter notebook
```

Or use JupyterLab:
```bash
jupyter lab
```

## Datasets

Datasets are **not included** in this repository. They download automatically when you run the notebooks for the first time.

**Note:** First run will take longer as datasets are downloaded. Subsequent runs use cached data stored in local `data/` directories.

## Dependencies

- Python 3.8+
- PyTorch 2.6.0+
- torchvision 0.21.0+
- NumPy, Matplotlib, Pillow
- Jupyter

See `requirements.txt` or `pyproject.toml` for complete list.

## License

MIT License - see [LICENSE](LICENSE) file.

---

**Course:** [PyTorch for Deep Learning Professional Certificate](https://learn.deeplearning.ai/specializations/pytorch-for-deep-learning-professional-certificate)
