**Vichaya Tedumrongvanich**

# Part 2: Reddit Data Analysis

Required Libraries and External 

This part of coursework uses Python along with several external libraries that are not part of standard Python installation. To successfully run all scripts and Jupyter notebook, you must install the following packages: 

- requests - for retrieving Reddit data through HTTP requests
- pandas - for data manipulation and cleaning
- numpy - for visualisations
- matplotlib - for visubalisation plot graph
- seaborn - for enhance plot graph visualisation
- nltk - for natural langauge processing (tokenisation, stopwords, VADER sentiment analysis)
- scipy - for statistical test 
-  statsmodel - for building regression models

## **Installation Instruction**

## Step 1. To install all required packages:

**Mac/Linux**

```
%pip install requests pandas numpy matplotlib nltk seaborn statsmodels scipy
```

Or 

**Window (Command Prompy/Powershell)**

```
pip install requests pandas numpy matplotlib nltk seaborn statsmodels scipy
```

## Step 1.5 **Fixing NLTK SSL Certificate Errors 

In case you get errors like:

```
CERTIFICATE_VERIFY_FAILED
Error loading vader_lexicon
Error loading stopwords
```

Run this before downloading NLTK corpora: 

```
import ssl
ssl._create_default_https_context = ssl._create_unverified_context
```

Then Downloand required NLTK corpora:

```
import nltk
nltk.download('vader_lexicon')
nltk.download('stopwords')
nltk.download('punkt')
```

These are for 
- **Sentiment Analysis**
- **Stopword removal**
- **Tokenization**

## Step 2. Required NLTK download 

```
import nltk
nltk.download('vader_lexicon')
nltk.download('stopwords')
nltk.download('punkt')
```

If SSL fails, apply **Step 1.5**

## Step 3. Running the Notebook

This project uses only standard Python libraries and public open source:

- NLTK
- VADER Sentiment Analyzer (Hutto & Gilbert, 2014)
- Request library
- Matplotlib and Seaborn
- Statsmodels 
- Scipy



