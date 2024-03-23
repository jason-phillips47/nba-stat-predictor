# NBA Stat Predictor

The NBA Stat Predictor is a predictive analytics project developed in Spring 2022 for my CS181Y class at Harvey-Mudd; the project uses machine learning to forecast specific player statistics for hypothetical or upcoming NBA games. Utilizing the `nba_api` to fetch detailed player and game data, this project employs Python's `pandas` for data manipulation and `scikit-learn` for its machine learning pipeline, including the `MLPClassifier` model and `train_test_split` method for training and testing. Data cleaning and formatting are performed using API calls and regular expressions, ensuring high-quality inputs for model training. The entire project is built and documented within a Jupyter Notebook environment, providing an interactive and educational experience for users.

## Features

- **Data Collection**: Uses `nba_api` to retrieve up-to-date player and game statistics from the NBA.
- **Data Processing**: Employs `pandas` for data structuring and preprocessing to prepare the dataset for machine learning.
- **Machine Learning Model**: Utilizes `scikit-learn`'s `MLPClassifier` to predict player performance statistics for a given game scenario.
- **Data Splitting**: Leverages `train_test_split` from `scikit-learn` to divide the data into training and testing sets for model evaluation.
- **Data Formatting**: Applies regular expressions and API responses to format and clean the data accurately.

## Getting Started

To get started with the NBA Stat Predictor, you will need an environment capable of running Jupyter Notebooks and have Python installed.

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/nba-stat-predictor-2022.git
```

2. Navigate to the project directory:

```bash
cd nba-stat-predictor-2022
```

3. Install the required Python packages:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

Navigate to the `NBA Stat Predictor.ipynb` file within the Jupyter Notebook interface to open the project.

## Usage

The project is structured as a Jupyter Notebook, which guides you through the process of data collection, processing, training the model, and making predictions. Follow the instructions and code cells within the notebook to use the NBA Stat Predictor:

1. **Data Collection**: Execute the cells under the data collection section to fetch data using `nba_api`.
2. **Data Processing**: Follow the steps to clean and prepare your data for the machine learning model.
3. **Model Training**: Run the cells that define and train the `MLPClassifier` model.
4. **Prediction**: Make predictions by inputting hypothetical game scenarios and player statistics.

## Contributing

Contributions to the NBA Stat Predictor project are welcome. Feel free to fork the project, make your changes, and submit a pull request for review.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- [nba_api](https://github.com/swar/nba_api) for providing an extensive API to access NBA data.
- [pandas](https://pandas.pydata.org/) for its powerful data manipulation capabilities.
- [scikit-learn](https://scikit-learn.org/stable/) for offering easy-to-use machine learning tools.

---

This README offers a concise overview of the NBA Stat Predictor project, guiding users through setup, usage, and contribution.
