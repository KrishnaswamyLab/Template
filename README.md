# Template

[![ArXiv](https://img.shields.io/badge/ArXiv-ProjectName-firebrick)](https://arxiv.org/abs/ProjectLink)
[![Conference](https://img.shields.io/badge/-Conference_Year-aeeafc)](https://ConferenceLink)
[![Poster](https://img.shields.io/badge/Poster-0f4d92)](https://PosterLink)
[![HuggingFace Dataset](https://img.shields.io/badge/HuggingFace-Dataset-orange)](https://huggingface.co/datasets/DatasetLink)
[![Twitter](https://img.shields.io/twitter/follow/KrishnaswamyLab.svg?style=social)](https://twitter.com/KrishnaswamyLab)

This is a GitHub repo template for the lab. Feel free to contribute.

## About
A brief eye-catching intro of the project.

Can include a figure here.
`<img src = "assets/architecture.png" width=800>`

<img src = "assets/architecture.png" width=800>

## Citation
```
@article{
Put the google scholar Bibtex here.
}
```

## Usage
### Environment setup
```bash
git clone https://github.com/KrishnaswamyLab/ProjectName.git
cd ProjectName
chmod +x setup.sh && ./setup.sh
source .venv/bin/activate
```

### Preprocessing
```bash
cd src/preprocessing
python preprocess_xxx.py
```

### Training and evaluation
```bash
cd src/
python main_xxx.py
```

### Analyses and visualizations
```bash
cd src/script_analysis/
python analyze_xxx.py

cd src/script_vis/
python visualize_xxx.py
```

## Repository Structure
```
├── assets/                        # Figures to display in this repo
├── comparison/                    # Baseline methods to compare with
├── data/                          # Data files
├── src/                           # Code folder
│   ├── preprocessing/             # Preprocessing code
│   ├── datasets/                  # Data loaders
│   ├── model/                     # Neural networks
│   ├── utils/                     # Utility functions
│   ├── script_analysis/           # Analysis
│   ├── script_vis/                # Visualization
│   └── main_xxx.py                # Main training/eval script
├── results/                       # Training/eval outputs
├── requirements.txt               # Environment dependencies
└── setup.sh                       # Environment setup
```

## Other sections to showcase results etc.
