# Text Summarization Model Comparison Project

## Overview

Text summarization is a crucial natural language processing task that involves condensing large documents into concise and informative summaries. This project focuses on comparing the performance of various text summarization models to help users choose the most suitable model for their specific needs.

## Key Features:

1. **Metrics Considered:**
   - The comparison is based on essential metrics, including Rouge scores, length of the summary, and training time. Rouge scores assess the quality of the generated summaries, while length and training time provide insights into efficiency and resource requirements.

2. **Methodology - TOPSIS:**
   - The Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method is employed for the comparison. This method considers both the similarity to the ideal solution and the dissimilarity to the negative ideal solution, providing a comprehensive ranking.

3. **Models Evaluated:**
   - Real-world pretrained models, such as BERTSumExt, GPT-3, T5, XLNet, BART, and Pegasus, are included in the comparison. These models are widely used in text summarization tasks.

## Project Structure:

- **`summarization_data.csv`**: CSV file containing evaluation metrics for each model.
- **`summarization_table_result.csv`**: CSV file with ranked results in tabular format.
- **`summarization_bar_chart_data.csv`**: CSV file with data used for creating a bar chart.
- **`summarization_bar_chart.png`**: Bar chart visualizing the model comparison.

## How to Run:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/text-summarization-comparison.git
   cd text-summarization-comparison
