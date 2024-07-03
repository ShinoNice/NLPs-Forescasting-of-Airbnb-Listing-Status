# Airbnb Property Unlisting Prediction

Welcome to the Airbnb Property Unlisting Prediction project! This project was developed as part of the Text Mining course for the 2023/2024 academic year. Our objective is to use Natural Language Processing (NLP) techniques to predict whether a property listed on Airbnb will be unlisted in the next quarter.

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [How to Run](#how-to-run)

## Project Overview
The goal of this project is to develop an NLP classification model to predict whether an Airbnb property will be unlisted in the next quarter. The dataset includes Airbnb property descriptions, host descriptions, and comments from previous guests. The project involves data preprocessing, model training, and evaluation.

## Data
The data used for this project is provided in the following files:
- `train.xlsx`: Contains Airbnb property and host descriptions for the training set.
- `train_reviews.xlsx`: Contains comments made on each Airbnb property in the training set.
- `test.xlsx`: Contains the structure of the test set, which matches the training set but without the target labels.
- `test_reviews.xlsx`: Contains comments corresponding to the properties in the test set.

## Methodology
1. **Data Preprocessing**: Cleaning and preparing the textual data for analysis.
2. **Feature Engineering**: Extracting relevant features from the text data.
3. **Model Training**: Training NLP models using libraries such as NLTK, Scikit-Learn, Keras, or PyTorch.
4. **Evaluation**: Assessing the model's performance using appropriate metrics.

## Results
The final model's performance and key findings are detailed in the `final_report.pdf` located in the `reports` folder.

## How to Run
To run the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ShinoNice/NLPs-Forescasting-of-Airbnb-Listing-Status
    cd NLPs-Forescasting-of-Airbnb-Listing-Status
    ```

2. Run the main script:
    ```bash
    python scripts/NLP_05.ipynb
    ```

For any questions or further information, feel free to contact me via GitHub.

Happy coding!
