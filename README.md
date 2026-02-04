# TOPSIS-Based Selection of Text Generation Models

## Description
This project applies the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** method to rank pre-trained text generation models based on multiple performance and efficiency criteria.

Models evaluated:
- GPT-2
- BART
- T5
- XLNet

## Methodology
- Construct a decision matrix using BLEU score, perplexity, inference time, and model size  
- Normalize the matrix and apply weights  
- Determine ideal best and ideal worst solutions  
- Compute TOPSIS scores and rank models  

## Results
- Each model receives a TOPSIS score in the range [0, 1]  
- Higher score indicates better overall performance  
- A bar chart visualizes the final ranking  

## Tech Stack
- Python  
- NumPy  
- Pandas  
- Matplotlib  

## Run
```bash
pip install numpy pandas matplotlib
python topsis_text_models.py
