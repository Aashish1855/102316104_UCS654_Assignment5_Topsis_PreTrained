# 102316104_UCS654_Assignment5_Topsis_PreTrained
# TOPSIS Based Selection of Best Conversational Model

## Overview

This project implements the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method to select the best pre-trained conversational model among multiple options. Instead of training models from scratch, which requires high computational resources, I compared existing models using different performance metrics and ranked them mathematically.

## Models Compared

- GPT-2  
- BlenderBot  
- DialoGPT  
- T5-Conversation  

## Criteria Used

The models are evaluated based on:

- BLEU Score (benefit criteria)  
- ROUGE Score (benefit criteria)  
- Coherence Score (benefit criteria)  
- Perplexity (cost criteria)  
- Inference Time (cost criteria)  
- Model Size (cost criteria)  

Higher value is preferred for benefit criterias and lower value is preferred for cost criterias.

## Methodology

First, a decision matrix is created using the above metrics. Then the matrix is normalized and weighted according to importance of each criteria. After that, ideal best and ideal worst solutions are calculated. Finally, TOPSIS score is computed and models are ranked based on closeness to ideal solution.

## Conclusion

This project shows how multi-criteria decision making can be applied in AI model comparison instead of depending only on single metric.
