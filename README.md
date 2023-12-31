# P5_Sentiment-Analysis

# P5 Natural Language Processing (NLP) Project - 
## Sentiment Analysis

<a name="readme-top"></a>

<div align="center">
  <br/>

  <h3><b>NLP Project: Sentiment Analysis</b></h3>

</div>


## Summary <a name="summary"></a>
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| P5 | Natural Language Processing Project: Sentiment Analysis | https://medium.com/@oparetwumseth/sentiment-analysis-and-gradio-app-on-covid-vaccination-e9b3f495e400 | https://huggingface.co/sotseth/tweets_classifier/blob/main/app.py |

## Project Description <a name="project-description"></a>
This project explores unstructured data (tweets) sentiment Analysis. In this project we fine-tune pre-trained models from HuggingFace on a new dataset to adapt the models in answering if a tweet has a neutral, positive, or negative sentiment. We then use the models to develop a Gradio app and deploy this app on the HuggingFace platform. 

## Objectives of Project <a name="objectives-of-project"></a>
The objective of this project is to develop a machine learning model to assess if a twitter post related to vaccinations is positive, neutral, or negative. This solution could help governments and other public health actors monitor public sentiment towards COVID-19 vaccinations and help improve public health policy, vaccine communication strategies, and vaccination programs accross the world. 

To achieve this objective, the following were undertaken;
1. Fine-tune a two pretrain Hugging Face model.
2. Create a Gradio app based on trained model
3. Upload the Hugging Face model and Deploy Gradio app on the HuggingFace platform
4. Dockerize Gradio app to get it ready to be deployed to any cloud hub

## Data <a name="data"></a>
The datasets where extracted from github, test and train datasets. 

* The dataset is made up of short tweets on the Covid vaccine.  
* There were 5 columns (tweet_id, safe_text, label, agreement, and text_length.
* There were 10,000 rows in the train dataset.

### Variable definition:
* tweet_id: Unique identifier of the tweet
* safe_tweet: Text contained in the tweet. Some sensitive information has been removed like usernames and urls
* label: Sentiment of the tweet (-1 for negative, 0 for neutral, 1 for positive)
* agreement: The tweets were labeled by three people. Agreement indicates the percentage of the three reviewers that agreed on the given label. 


## Installation: <a name="installation:"></a>
* transformers==4.35.0
* gradio==4.2.0
* scikit-learn==1.2.2
* scipy==1.11.3
* torch==2.1.0

## Author <a name="author"></a>
Seth Opare-Twum
- GitHub: [@sethsot](https://github.com/sethsot/sethsot)
- LinkedIn: [Seth Opare-Twum](https://www.linkedin.com/in/%20seth-opare-twum)
