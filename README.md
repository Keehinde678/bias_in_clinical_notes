# Bias_in_Clinical_Notes

## Project Overview

This repository explores **bias in clinical notes** using Natural Language Processing (NLP) techniques. The project aims to identify, analyze, and visualize potential biases in medical documentation, with a focus on improving fairness, transparency, and accountability in healthcare narratives.

By systematically analyzing clinical notes, this project can:

* Detect subtle language biases in patient records.
* Examine patterns of representation across demographics.
* Provide insights for ethical and equitable healthcare practices.

## Project Structure

```
bias_in_clinical_notes/
│
├── scripts/                 # Jupyter notebooks and scripts for analysis
│   ├── Lexicon analysis.ipynb
│   ├── NLP.ipynb
│   ├── Sentiment Analysis.ipynb
│   ├── Word_bias script.ipynb
│   └── Untitled.ipynb
│
├── outputs/                 # Results of scripts, processed data, visualizations
│   └── processed_notes_with_features.csv
│
├── data/                    # Placeholder for dataset (not included due to size)
│
├── requirements.txt         # Python dependencies
├── .gitignore               # Git ignore rules
└── README.md                # Project documentation
```

## Environment Setup

1. Clone the repository:

```bash
git clone https://github.com/Keehinde678/bias_in_clinical_notes.git
cd bias_in_clinical_notes
```

2. Create a virtual environment and activate it:

```bash
python -m venv env
# Windows
env\Scripts\activate
# macOS/Linux
source env/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Dataset

Due to size and privacy considerations, the original MIMIC-III clinical dataset is **not included**.

* Place your dataset (e.g., `MIMICIII_Cleaned_Merged.csv`) in the `data/` directory.
* Ensure the dataset follows the expected schema used in the scripts.
* Large dataset files should be **excluded from Git** to prevent repository issues. The `.gitignore` already includes the `data/` folder.

## Usage

1. Explore individual notebooks in `scripts/` to replicate analyses:

   * `Lexicon analysis.ipynb` — analyze specific terms and lexicons.
   * `NLP.ipynb` — pre-processing and NLP pipelines.
   * `Sentiment Analysis.ipynb` — sentiment extraction and visualization.
   * `Word_bias script.ipynb` — advanced bias detection.
2. Outputs (e.g., processed datasets, plots) will be saved in the `outputs/` folder.

## Notes

* Ensure sensitive patient data is handled according to HIPAA and ethical guidelines.
* All analyses are intended for research and educational purposes only.

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

---

*Maintainer: Kehinde Soetan*
