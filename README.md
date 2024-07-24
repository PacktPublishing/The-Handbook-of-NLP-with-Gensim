# The Handbook of NLP with Gensim


<a href=""><img src="https://m.media-amazon.com/images/I/71fSTzz5mbL._SL1500_.jpg" alt="The Handbook of NLP with Gensim" height="256px" align="right"></a>

This is the code repository for [The Handbook of NLP with Gensim](), published by Packt.

**Leverage topic modeling to uncover hidden patterns, themes, and valuable insights within textual data**

## What is this book about?

Navigating the terrain of NLP research and applying it practically can be a formidable task made easy with The Handbook of NLP with Gensim. This book demystifies NLP and equips you with hands-on strategies spanning healthcare, e-commerce, finance, and more to enable you to leverage Gensim in real-world scenarios.

This book covers the following exciting features: 
* Convert text into numerical values such as bag-of-word, TF-IDF, and word embedding
* Use various NLP techniques with Gensim, including Word2Vec, Doc2Vec, LSA, FastText, LDA, and Ensemble LDA
* Build topical modeling pipelines and visualize the results of topic models
* Implement text summarization for legal, clinical, or other documents
* Apply core NLP techniques in healthcare, finance, and e-commerce
* Create efficient chatbots by harnessing Gensim's NLP capabilities

If you feel this book is for you, get your [copy](https://www.amazon.in/Handbook-NLP-Gensim-Leverage-modeling-ebook/dp/B0CKCP1YKC/ref=sr_1_1?keywords=The+Handbook+of+NLP+with+Gensim&sr=8-1) today!

<a href=""><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
nlp = spacy.load("en_core_web_sm")
stopwords = en.Defaults.stop_words
text_tokenized = []
for doc in nlp.pipe(train['Description'], disable = to_be_disabled):
        k = [token.lemma_ for token in doc if not token.is_stop]
        text_tokenized.append(k)
```
**Following is what you need for this book:**
This book is for data scientists and professionals who want to become proficient in topic modeling with Gensim. NLP practitioners can use this book as a code reference, while students or those considering a career transition will find this a valuable resource for advancing in the field of NLP. This book contains real-world applications for biomedical, healthcare, legal, and operations, making it a helpful guide for project managers designing their own topic modeling applications.

With the following software and hardware list you can run all code files present in the book (Chapter 2-14).

### Software and Hardware List
pre-requisites: You will need a version of Angular installed on your computer—the latest version, if possible.
| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  	1-14	   |   	Gensim                                 			  | any OS | 		
|  	1-14	   |   	Python version ≥ 3.7                                 			  | Any OS | 		


### Related products <Other books you may enjoy>
* Python Natural Language Processing Cookbook  [[Packt]](https://www.packtpub.com/product/python-natural-language-processing-cookbook/9781838987312) [[Amazon]](https://www.amazon.in/Python-Natural-Language-Processing-Cookbook/dp/1838987312/ref=sr_1_1_sspa?keywords=Python+Natural+Language+Processing+Cookbook&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)
  
* Hands-On Python Natural Language Processing  [[Packt]](https://www.packtpub.com/product/hands-on-python-natural-language-processing/9781838989590) [[Amazon]](https://www.amazon.in/Hands-Python-Natural-Language-Processing/dp/1838989595/ref=sr_1_5?keywords=Hands-On+Python+Natural+Language+Processing&sr=8-5)

## Errata
* Page 43, The code snippet in the "NLTK for lemmatization" section (end of page) is incorrect and repeated from the previous section.
  _The correct code should be:_
  ```
  from nltk.stem import WordNetLemmatizer
  wnl = WordNetLemmatizer()
  for w in text_tokenized:
  print(wnl.lemmatize(w))
  ```
  
## Get to Know the Author
**Chris Kuo** is a data scientist with more than 20 years of experience. He led various data science solutions including customer analytics, health analytics, fraud detection, and litigation, and is an inventor of a U.S. patent. He has worked at the Hartford Insurance Group (HIG), the American International Group (AIG), Liberty Mutual Insurance, and the BJ’s Wholesale Club. Chris Kuo teaches at Columbia University, has taught at Boston University and other universities. He is the author of The eXplainable A.I. and Modern Time Series Anomaly Detection: With Python & R Code Examples, and Transfer Learning for Image Classification: With Python Examples. He received his undergraduate degree in Nuclear Engineering and Ph.D. in Economics
