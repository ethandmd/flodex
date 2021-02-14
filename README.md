# flodex
Analyze two different textual narratives from the Florentine Codex (c. ~1560s) of the fall of Tenochtitlan using NLP (STANZA in particular).
The data is in a .txt file, and it is tokenized and annotated through the Stanza pre-trained english language model. Then, the Stanza document is converted to a python object (a list of dictionaries) from which the class "Section", takes in each converted Stanza document and creates a multi indexed Pandas dataframe.

EDA tasks: Sentence lengths, UPOS usage as %, Word choice, Sentiment Analysis as % 


