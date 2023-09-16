# NLP_Toolbox
The NLP projects which I programmed and shared them open source.

1.NER
A token classification to predict each token to  ( O : None, Loc : location, Per : person, Org : organization) label.
The model accepts Persian and English and performed 95% f1-score. You can check the model on [huggingface page](https://huggingface.co/AliFartout/Roberta-fa-en-ner)

2.Summarization
A summarization model (mT5) is trained on XLsum dataset for Persian and English. The model trained for about 16 hours and gave the below result:

ROUGE-1 ->  29.83
ROUGE-2 ->  17.4
ROUGE-L ->  21.95

***Note that model will perform better with training in more steps/epochs
