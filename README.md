# Misleading-Covid-vaccination-Tweets
*This repository is linked to this paper - "Misleading the Covid-19 vaccination discourse on Twitter: An exploratory study of infodemic around the pandemic."
The [paper](https://arxiv.org/pdf/2108.10735.pdf) Misleading and Non-Misleading tweets. Label the tweets using XLNet pre-trained model. (1500 tweets manually annotated).
<br>
**The main objectives of this paper -**
1. Labeling process of the collected tweets <br>
2. Descriptive Analysis:<br>
  a) Syntactic Aspect - Distribution and KS test of Nouns, Pronouns, Stop words, etc.<br>
  b) Frame of Mind - Topic Modeling, Sentiments, Emotions, NRC Lexicon, Word Cloud.<br>
  c) Visibility Aspect - Hashtags, Tweet time, Retweets/Reply/Likes count.<br>
3. Predictive Analysis:<br>
  a) Traditional Classifiers - SVM, XGBoost, RF, Logistic Regression<br>
  b) AI Explainability: SHAP for feature importance.
  
  Note: The Misleading COVID19 dataset (https://researchdata.ntu.edu.sg/dataset.xhtml?persistentId=doi:10.21979/N9/QMLIJQ) is released in accordance with Twitter's TOS, which allows sharing of tweet IDs and are intended for non-commercial research (https://twittercommunity.com/t/policy-update-clarification-research-use-cases/87566). Thus, by downloading this dataset, you agree that you will not use it for commercial purposes.

Tools Used: Anaconda Navigator;
Packages used: NLTK, SHAP, NLP tools

If you find this code or paper useful in your research, please consider citing:

Please cite this paper:

    @article{sharma2021misleading,
    title={Misleading the Covid-19 vaccination discourse on Twitter: An exploratory study of infodemic around the pandemic},
    author={Sharma, Shakshi and Sharma, Rajesh and Datta, Anwitaman},
    journal={arXiv preprint arXiv:2108.10735},
    year={2021}
    }
