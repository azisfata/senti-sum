# Indonesia Senti-SUM
## Sentiment Analysis on Auto Summarization using Indonesian BERT
Recently, online news has replaced conventional magazines and physical newspapers because of its understandability and ability to deliver information on time. News sites provide a comprehensive overview of important current events, becoming a valuable resource for learning about a country's current social, political, and economic issues. Governments use news channels and sentiment analysis to get an overview of specific topics. However, some previous studies only read part of the news elements to determine sentiment, so the system does not thoroughly read the content to determine the sentiment polarity. This situation leads to errors in sentiment reading, which should be negatively interpreted as positive or vice versa. This research tests automatically generated news text summaries using the IndoBERT fine-tuning model to label the sentiment of news texts. This research shows that the fine-tuned IndoBERT tested using the human-made news summary dataset achieved optimal results, with an F1-score of 75% when compared to the F1-Score of 65% from the auto-generated news summary dataset. This shows that the performance of sentiment analysis prediction using automatic news summarization cannot yet surpass the performance of sentiment analysis prediction using human-made news summaries.
## Requirement
Tested on Kaggle notebook with 1 Tesla P100-16GB GPU and a RAM size of 30 GB using below configuration: 
- Python==3.10.12
- numpy==1.24.3
- pandas==2.0.3
- torch==2.0.0
- tqdm==4.66.1
- torchvision==0.15.1
- transformers==4.36.0
- tensorboardX==2.6.2.2
- nltk==3.2.4
- sklearn-pandas==2.2.0
- matplotlib==3.7.4
- seaborn==0.12.2
- ipywidgets==7.7.1

## Experiment
1. First, download [SentiSUM] dataset
2. Run summarization task on SentiSUM dataset using [IndoBERT Summarization.ipynb] and it will generate [Auto-SentiSUM]
3. Run IndoBERT Fine-Tuning and evaluation Auto-Summarization sentiment using  

## License

MIT

**Free Software, Hell Yeah!**

   [SentiSUM]: <https://github.com/azisfata/senti-sum/blob/main/SentiSUM.xlsx>
   [Auto-SentiSUM]: <https://github.com/azisfata/senti-sum/blob/main/Auto-SentiSUM.xlsx>
   [IndoBERT Summarization.ipynb]: <https://github.com/azisfata/senti-sum/blob/main/IndoBERT%20Summarization.ipynb>
