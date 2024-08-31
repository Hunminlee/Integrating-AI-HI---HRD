# Integrating Cross-Human Intelligence and Artificial Intelligence: Through Case Study in Organizational Management

This repository contains the code and datasets associated with the paper "Integrating Cross-Human Intelligence and Artificial Intelligence: Through Case Study in Organizational Management." 

AI is revolutionizing HRD, traditionally managed by professionals. The integration of AI-powered tools in both industry and academia marks a significant shift. While AI enhances efficiency in tasks like training and development, its black-box nature poses challenges, particularly in transparency and trust. Our work addresses the gap between human expertise and AI in HRD by analyzing and interpreting advanced models on HRD tasks. Our findings highlight the importance of aligning AI decisions with expert knowledge, improving the transparency and reliability of AI in HRD.

## Repository Structure

- `DNN_result/`: Contains the datasets used for training and testing the models.
- `models/`: Includes the trained models and the scripts for training.
- `notebooks/`: Jupyter notebooks for exploratory data analysis, feature extraction, and model evaluation.
- `src/`: Source code for data preprocessing, model training, and evaluation.
- `results/`: Output files, including model performance metrics and visualizations.

## Installation

To replicate the results of the paper, clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/Integrating-AI-HI---HRD.git
cd Competency-HRD-Features-AI
pip install -r requirements.txt
```

## To train the model using the provided dataset, run the following command:
python src/train_model.py --config configs/train_config.yaml

## Evaluating the Model
After training, you can evaluate the model on the test dataset:
python src/evaluate_model.py --model models/trained_model.pth --test_data data/test_dataset.csv

## Reproducing Results
To reproduce the results discussed in Section 4.2 of the paper, execute the corresponding Jupyter notebook:
jupyter notebook notebooks/evaluate_results.ipynb

## Results
The results of the model's performance, including accuracy, precision, recall, and F1-score, are available in the results/ directory. Comparative analysis and detailed discussions can be found in the paper.

This paper is currently under review in Human Resource Development International (HRDI)

License
This project is licensed under the MIT License - see the LICENSE file for details.
