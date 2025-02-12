# Sentiment Analysis

This repository contains a series of Jupyter notebooks for sentiment analysus. The experiments use various data preprocessing and machine learning techniques to predict if a statement is hate speech or not.

## Repository Structure


## Notebooks

- **File:** [Sentiment_Analysis.ipynb](Sentiment_Analysis.ipynb)
- **Description:** Initial data exploration and preprocessing. Loads the training and test datasets and inspects the first few rows. Then proceeds to create an LSTM architecture that will be used to create a model that can predict sentiment from a text based dataset


## Data
- **Training Data:** [hate.csv](hate.csv)


## Setup
1. Clone the repository.
2. Create a virtual environment:
    ```sh
    python -m venv venv
    ```
3. Activate the virtual environment:
    - On Windows:
        ```sh
        .\venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```
4. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
Open the Jupyter notebooks in your preferred environment (e.g., Jupyter Lab, Google Colab) and run the cells to reproduce the experiments.

## License
This project is licensed under the MIT License.