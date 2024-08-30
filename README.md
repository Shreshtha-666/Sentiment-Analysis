# Sentiment Analysis with TextBlob

## Project Overview
This project performs sentiment analysis on a dataset using the TextBlob library. The primary objective is to classify the sentiments of text data (e.g., tweets) into Positive, Neutral, or Negative categories and visualize the results.

## Dataset
The dataset used in this project is named `test.csv`. It contains a `Category` column, which is analyzed for sentiment.

## Key Steps
1. **Installation of Dependencies**:
    - The project uses `TextBlob` for sentiment analysis, `pandas` for data manipulation, and `matplotlib` for visualization.
    - Required packages can be installed using the following command:
    ```bash
    pip install textblob pandas matplotlib
    ```

2. **Loading the Dataset**:
    - The dataset is loaded from the `test.csv` file using pandas.

3. **Sentiment Analysis**:
    - The `Category` column is analyzed for sentiment using the `TextBlob` library, which classifies the text into Positive, Neutral, or Negative based on the polarity of the text.

4. **Result Calculation**:
    - The results are counted, and the number of Positive, Neutral, and Negative texts are printed.

5. **Visualization**:
    - A bar chart is plotted to visualize the distribution of sentiments across the dataset.

## How to Run the Project
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/Sentiment-Analysis-TextBlob.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Sentiment-Analysis-TextBlob
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the notebook:
    ```bash
    jupyter notebook "code.ipynb"
    ```

## Requirements
- Python 3.x
- TextBlob
- pandas
- Matplotlib

## Results
The sentiment analysis results are displayed in the terminal and visualized using a bar chart. The chart shows the number of Positive, Neutral, and Negative sentiments in the dataset.

## License
This project is licensed under the MIT License.

## Acknowledgments
- The project is inspired by common practices in text sentiment analysis and leverages the TextBlob library for natural language processing.
