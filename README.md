# Negation Resolution

An NLP tool that performs Negation resolution on sentences. It takes as input a sentence and a target-keyword. It returns `True` for affirmed keywords, `False` for negated and `None` for keywords not found.

## Installation

First you need to download and extract [CoreNLP](http://stanfordnlp.github.io/CoreNLP/#download). 

Then, just follow requirements.txt:

```shell
pip install -r requirements.txt
```

##Example

```python
import negation
sentence = "The patient is suicidal"
negation.predict(sentence, 'suicide')
```


