# <u>Word-Prediction-Ngram</u>
### Next Word Prediction using n-gram Probabilistic Model.
Various jupyter notebooks are there using different Language Models for next word Prediction.
<br>

### Input :
The users Enters a text sentence<br> 
### Output :
Predicts a word which can follow the input sentence
<br>

#### Various Smoothing Techniques have been used in different Language Models along with combination of Interpolation and Backoff in these different Language Models.
### Smoothing Techniques Used:
      1. Add 1 
      2. Good Turing 
      3. Simple Knesser Ney
      4. Interpolated Knesser Ney
      
### How the code works:
1. Cleaning of training corpus ( Removing Punctuations etc)
2. Creation of Language Model:<br>
    i) Formation of n-grams (Unigram, Bigram, Trigram, Quadgram)<br>
    ii) Probability Dictionary Creation with provision of various Smoothing Mechanism


