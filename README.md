# natural-language-processing-with-disaster-tweets
Kaggle Competition, Public score: 0.83328, top 88%
implementing different NLP techniques including Bert, Naiive Bayes to classify disaster tweets.

# implementation
## data preproceesing
the data folder structure is as follows:
```bash
./
├─ data/
│  ├─ train.csv
│  ├─ test.csv
│  ├─ df_trian.xlsx
│  ├─ df_test.xlsx
│  ├─ sample_submission.csv
│  └─ clean_mapping.csv
│
├─ .gitignore
├─ README.md
```

The `train.csv` and `test.csv` files contain the text data for the training and testing datasets, respectively.
The `df_train.xlsx` and `df_test.xlsx` files contain the preprocessed data for the training and testing datasets, respectively. The `sample_submission.csv` file contains the format for the submission file. 
The `clean_mapping.csv` file contains the mapping of the original labels to the new labels.

---
[kaggle](https://www.kaggle.com/competitions/nlp-getting-started)
# Competition Description
Welcome to one of our "Getting Started" competitions 👋
This particular challenge is perfect for data scientists looking to get started with Natural Language Processing. The competition dataset is not too big, and even if you don’t have much personal computing power, you can do all of the work in our free, no-setup, Jupyter Notebooks environment called Kaggle Notebooks.

If you want to talk with other users about this competition, come join our Discord! We've got channels for competitions, job postings and career discussions, resources, and socializing with your fellow data scientists. Follow the link here: https://discord.gg/kaggle

Competition Description
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:
> The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

In this competition, you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified. If this is your first time working on an NLP problem, we've created a quick tutorial to get you up and running.

Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.
