# EFG – SU Competition

Welcome to the EFG – SU Competition! This repository contains the code and documentation for my participation in the competition. In this competition, we aim to predict customer churn for retail Egyptian clients trading on the EFG Hermes ONE app, to retain them before actual churn, and explore internal or external factors to reduce churn in the brokerage market for EFG.

## Competition Use Case

Every business wants to optimize for customers remaining loyal to their services. They typically calculate their churn rate and strive to minimize it through enhancing their services, products, and marketing campaigns. EFG provides seamless financial services, one of which is a stock market trading application called EFG Hermes ONE. In this use case, we aim to predict customer churn for retail Egyptian clients trading on the ONE app, to retain them before actual churn, and explore internal or external factors to reduce churn in the brokerage market for EFG. EFG is considered your client, and you are attempting to sell them a final product based on the data available.

## Data Description

The data provided for this competition includes two dummy datasets: `clients_data.csv` and `orders_data.csv`. The `clients_data` file contains clients' information and demographics, while the `orders_data` file comprises the clients' orders on the app. For detailed information about the data features and their descriptions, please refer to the provided documentation.

## Folder Structure

```
data-science-project/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── models/
│
├── notebooks/
│   ├── exploration.ipynb
│   ├── preprocessing.ipynb
│   ├── modeling.ipynb
│   └── evaluation.ipynb
│
├── src/
│   ├── data/
│   │   ├── data_ingestion.py
│   │   └── data_preprocessing.py
│   ├── modeling/
│   │   ├── train_model.py
│   │   └── evaluate_model.py
│   └── utils/
│       └── helpers.py
│
├── config/
│   └── config.yaml
│
├── tests/
│   ├── test_data.py
│   └── test_model.py
│
├── README.md
├── LICENSE
└── requirements.txt
```

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/efg-su-competition.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Explore the notebooks in the `notebooks` directory for data exploration, preprocessing, modeling, and evaluation.

4. Run the scripts in the `src` directory to perform data ingestion, preprocessing, modeling, and evaluation.

## Contact

If you have any questions or concerns, feel free to contact me at [Mohamed Abdelmagid](mailto:mabdelmagid@aucegypt.edu).

Happy coding!