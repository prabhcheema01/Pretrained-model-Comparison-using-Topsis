# Pretrained-model-Comparison-using-Topsis
## Project Overview

Welcome to the Text Conversational Model Comparison project! This project aims to assist users in selecting the most suitable text conversational model for their needs by comparing various pre-trained models using the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method. By evaluating essential metrics such as perplexity, BLEU, and ROUGE, this project provides insights into the performance and efficiency of different models in generating human-like responses in conversations.
## Key Features:

1. **Comprehensive Metrics Consideration:**
   - Evaluation is based on a comprehensive set of metrics including perplexity, BLEU, and ROUGE, offering a holistic view of model performance in conversational tasks.
2. **Methodology - TOPSIS:**
   - The TOPSIS method is utilized for comparison, considering both similarity to the ideal solution and dissimilarity to the negative ideal solution, ensuring a robust ranking of conversational models.

3. **Models Evaluated:**
   - Models such as DialoGPT, BlenderBot, GPT-3, Meena, LaMDA, and Siri are evaluated, reflecting real-world pre-trained models commonly used in text conversational tasks.

## Project Structure:

- **`data.csv`**: Contains evaluation metrics for each model.
- **`result.csv`**: Provides ranked results in a tabular format for easy analysis.

## Results and Analysis:
1. **Ranked Table:**
- Refer to conversational_table_result.csv for detailed ranked results.

| **Model**   | **Perplexity**    | **BLEU**              | **ROUGE**         |
|-------------|-------------------|-----------------------|-------------------|
| DialoGPT    | 40                | 0.35                  | 0.45              |
| BlenderBot  | 38                | 0.38                  | 0.48              |
| GPT-3       | 35                | 0.40                  | 0.50              |
| Meena       | 42                | 0.36                  | 0.46              |
| LaMDA       | 48                | 0.33                  | 0.42              |
| Siri        | 50                | 0.32                  | 0.40              |




## Analysis:
**Model Performance:**
Meena achieves the highest BLEU and ROUGE scores, indicating superior conversational quality, followed closely by GPT-3 and BlenderBot. DialoGPT and LaMDA show competitive performance in terms of BLEU and ROUGE scores.

**Perplexity:** GPT-3 has the lowest perplexity score, indicating better prediction of the target responses compared to other models. However, perplexity alone may not fully capture the conversational quality of the models.

**Efficiency Consideration:**  Siri has the highest perplexity score but lower BLEU and ROUGE scores compared to other models, indicating potential trade-offs between perplexity and conversational quality. Additionally, computational efficiency and response time are important considerations for real-time conversational applications.
