# textcat_dataset_IMDB
Movie Review Dataset  for binary sentiment classification in spacy format (and JSON).<br>
train dataset - 2000 examples<br>
dev dataset - 500 examples<br>
Use https://github.com/d5555/TagEditor to view examples. <br>
link to original dataset :<br>
http://ai.stanford.edu/~amaas/data/sentiment/

example:<br>
```
[{
'text': 'It really is a shame that films like this never snag Best Picture nominations, because this one is simply a winner. This is by far the most consistently hilarious comedy I have ever seen. Its screenplay and design are impeccable, not to mention the incredible cast. I can quote this movie for hours on end. Watch it.',
'words': ['It', 'really', 'is', 'a', 'shame', 'that', 'films', 'like', 'this', 'never', 'snag', 'Best', 'Picture', 'nominations', ',', 'because', 'this', 'one', 'is', 'simply', 'a', 'winner', '.', 'This', 'is', 'by', 'far', 'the', 'most', 'consistently', 'hilarious', 'comedy', 'I', 'have', 'ever', 'seen', '.', 'Its', 'screenplay', 'and', 'design', 'are', 'impeccable', ',', 'not', 'to', 'mention', 'the', 'incredible', 'cast', '.', 'I', 'can', 'quote', 'this', 'movie', 'for', 'hours', 'on', 'end', '.', 'Watch', 'it', '.'],
'spaces': [' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', '', ' ', ' ', ' ', ' ', ' ', ' ', ' ', '', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', '', ' ', ' ', ' ', ' ', ' ', ' ', '', ' ', ' ', ' ', ' ', ' ', ' ', '', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', ' ', '', ' ', ' ', '', ''],
'sent_starts': [True, False, False, False, False, False, False, False, False, False, False, False, False, False, False, False, False, False, False, False, False, False, False, True, False, False, False, False, False, False, False, False, False, False, False, False, False, True, False, False, False, False, False, False, False, False, False, False, False, False, False, True, False, False, False, False, False, False, False, False, False, True, False, False],
'cats': {'POSITIVE': True, 'NEGATIVE': False}
},
...
```
