# Pretrained-model-Comparison-using-Topsis
## Project Overview

Welcome to the Text Summarization Model Comparison project! This project aims to assist users in selecting the most suitable text summarization model for their needs by comparing various pre-trained models using the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method. By evaluating essential metrics such as Rouge scores, summary length, and training time, this project provides insights into the performance and efficiency of different models.

## Key Features:

1. **Comprehensive Metrics Consideration:**
   - Evaluation is based on Rouge scores, summary length, and training time, offering a holistic view of model performance and efficiency.
2. **Methodology - TOPSIS:**
   - The TOPSIS method is utilized for comparison, considering both similarity to the ideal solution and dissimilarity to the negative ideal solution, ensuring a robust ranking.

3. **Models Evaluated:**
   - Models such as RoBERTa, ELECTRA, DistilBERT, ALBERT, GPT-2, CTRL, BART, T5, and Pegasus are evaluated, reflecting real-world pre-trained models commonly used in text summarization tasks.

## Project Structure:

- **`data.csv`**: Contains evaluation metrics for each model.
- **`result.csv`**: Provides ranked results in a tabular format for easy analysis.

## Results and Analysis:
1. **Ranked Table:**
- Refer to summarization_table_result.csv for detailed ranked results.

| **Model**   | **Rouge Scores**  | **Length of Summary** | **Training Time** |
|-------------|-------------------|-----------------------|-------------------|
| RoBERTa     | 0.77              | 133                   | 10                |
| ELECTRA     | 0.79              | 137                   | 11                |
| DistilBERT  | 0.72              | 125                   | 7                 |
| ALBERT      | 0.81              | 142                   | 13                |
| GPT-2       | 0.76              | 132                   | 9                 |
| CTRL        | 0.74              | 128                   | 8                 |
| BART        | 0.83              | 148                   | 15                |
| T5          | 0.80              | 135                   | 12                |
| Pegasus     | 0.85              | 155                   | 18                |



## Analysis:
**Model Performance:**
Pegasus achieves the highest Rouge scores, indicating superior summarization quality, followed by BART and ALBERT.

**Efficiency Consideration:** DistilBERT remains the most resource-efficient model with the lowest training time, while T5 and RoBERTa also offer competitive performance with moderate training times.
