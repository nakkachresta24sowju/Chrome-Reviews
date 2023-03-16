# Predict Sentiment Analysis on Chrome Reviews using Machine Learning

For Sentiment Analysis, we’ll use VADER Sentiment Analysis, where VADER means Valence Aware Dictionary and sentiment Reasoner.

VADER is a lexicon and rule-based feeling analysis instrument that is explicitly sensitive to suppositions communicated in web-based media. VADER utilizes a mix of lexical highlights (e.g : words) that are, for the most part, marked by their semantic direction as one or the other positive or negative. Thus, VADER not only tells about the Polarity score yet, in addition, it tells us concerning how positive or negative a conclusion is.

Why do I use VADER?

VADER belongs to a kind of sentiment analysis that depends on lexicons of sentiment-related words. In this methodology, every one of the words in the vocabulary is appraised with respect to whether it is positive or negative, and, how +ve or -ve. Beneath you can see an extract from VADER’s vocabulary, where more positive words have higher positive evaluations and more adverse words have lower negative grades.

In this data we have already used cleansed text of reviews so that I am not including preprocessing and cleansing of text in the code.

The given chrome reviews are also 1 or 2 sentences only that's why I directly jump sentiment analysis part.

If the reviews of was large then its better to proceed with othe NLP techniques 

stemming(method to break down the word into a simpler form)

Lemmatization (which helps in breaking down words from plural to a singular form)

we have to identify Stop Words (Stop words are nothing but the articles used in the English language like “the”, “a”, “at”, “for”, “above”, “on”, “is”, “all”)

Part of Speech Tagging (POS)

Named entity Recognition step (It is the step in which the system identifies which word is a person’s name, location, etc)

Chunking (grouping the individual piece of information into bigger pieces).

Any of the above methods we will use based on requirement.

Steps involved in this sentiment analysis task:

      Perform basic cleansing of data , chencking for duplicates and data analysis.

      Apply VADER sentiment analysis on data.

      Predict Polarity scores and Sentiment type for each review.



