# Performance evaluation of pre-trained Assamese word embedding for Assamese

## Requirements

* It requires python 3.6+
* Install [Flair](https://github.com/flairNLP/flair) preferably  in in favorite virtual environment, 


## How to run

Download the pre-trained model from the link- [NER](https://drive.google.com/file/d/1sqBxuujk9yOPcXkQTvONgQlP93qt0EJD/view?usp=sharing)
Download the pre-trained model from the link- [POS](https://drive.google.com/file/d/1MC7mVOguotsPEnpLiL20ag97O7siMqvU/view?usp=sharing)

```
from flair.models import SequenceTagger
from flair.data import  Sentence, Token

# Load the tagger

model = SequenceTagger.load('AsNER.pt')
`````
