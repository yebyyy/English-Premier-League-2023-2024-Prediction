# English-Premier-League-2023/2024-Prediction

This project aims to predict the outcomes of English Premier League matches using machine learning techniques. The prediction model is built with a Random Forest classifier and achieves a precision score of 66.15%.

## Datasets

The dataset, `matches_csv`, contains match data scraped from the 2021-2024 English Premier League seasons. It includes various match statistics and outcomes, which serve as the foundation for our predictive model.

## Files

- `Scrape.ipynb`: Jupyter notebook containing the web scraping logic used to collect match data from the 2021-2024 seasons.
- `English_Premier_League_Prediction_Model.ipynb`: Jupyter notebook where the Random Forest classification model is developed, trained, and evaluated.

## Getting Started

To replicate this project, clone this repository and ensure you have the necessary Python packages installed, including `scikit-learn`, `beautifulsoup4`, `pandas`, and `requests`.

```bash
git clone <repository-url>
cd <repository-name>
# Install dependencies
pip install -r requirements.txt
```
## Usage

Run `Scrape.ipynb` to collect the latest match data.
Execute `English_Premier_League_Prediction_Model.ipynb` to train the model and make predictions.

## Contributing

Contributions to improve the prediction accuracy or enhance the data collection process are welcome. Please feel free to fork the repository and submit a pull request with your changes.
