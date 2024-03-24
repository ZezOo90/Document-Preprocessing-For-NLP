<h1>HTML Text Preprocessing for NLP Tasks<h1>
This Python code is designed to preprocess HTML text for Natural Language Processing (NLP) tasks. The script takes an HTML file from a given URL, extracts the text content, and applies various preprocessing techniques to clean and prepare the text for analysis.

<h2>Features:<h2>
<p>HTML Text Extraction: Utilizes BeautifulSoup to parse HTML content and extract relevant text from p, h1, h2, h3, h4, h5, and h6 tags.<p>
<p>Text Normalization: Removes non-alphabetic characters and converts text to lowercase.<p>
<p>Tokenization: Splits text into individual words or tokens using NLTK's word_tokenize.<p>
<p>Stopword Removal: Filters out common English stopwords using NLTK's stopwords corpus.<p>
<p>Stemming: Reduces words to their root form using NLTK's PorterStemmer.<p>
<p>Lemmatization: Converts words to their base or dictionary form using NLTK's WordNetLemmatizer.<p>
