# Financial Sentiment Analysis

This is the repo to compare different models to analyse what methods work best for fiancial sentiment analysis of posts on Twitter (Now X)
Detecting sentiments of the market (bearish/bullish/neutral) could help with tasks such as risk monitoring and position planning.
The best model utilises a two-shot method with Finbert and Full Finetuning, giving an Macro F1 of 0.89825.




## Project Setup

### 1. Repository Setup

1. Git clone this repository
2. Create a file named `.env` in the main project folder.
3. Download the required libraries into the env


### 2. Run each Notebook
1. Ensure that you are using GPU 
2. Change the models to run different models (FinBERT or roBERTa) and strategies (LoRA or Full Finetuning)

```Bash
model = "finbert"  # "finbert" or "roberta"
strategy = "LoRA"  # "LoRA" or "FT"
```

3. Change the amount of noise in each model
```Bash
noise_amth = 20000 #20000 for baseline, 70000 for full model
```
   



## Author

- Tan Shu Hui (Amanda)
