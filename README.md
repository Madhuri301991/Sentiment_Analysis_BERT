# Sentiment_Analysis_BERT
Sentiment Analysis to classify reviews 
- Use the pretrained multilingual BERT model 'bert-base-multilingual-uncased-sentiment', this model was implemented using the Huggingface Transformers library'.
- tranformers package is used for NLP model --> 
- BERT multilingual BERT model that performs sentiment anlysis --> from HuggingFace
- requests package is going to request review from the YELP site
- pandas --> going to format data that is easy to work with
- numpy --> going to give some additional data transformers processes
- AutoTokenizer --> convert string into sequence of numbers and pass to an NLP model
- AutoModelForSequenceClassification --> give architecture to load NLP model
- BeautifulSoup--> extract data we actually need --> we need reviews
- re--> regex --> extract the specific comments that we want.
