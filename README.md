# GMB_corpus_ner
This is the repository fot the link https://www.kaggle.com/shoumikgoswami/ner-using-random-forest-and-crf, which uses a ensemble model combines (xgboos,crf,random forest,bilist+attn+crf) and a model based on Bert(since my computer does not support trainning a model like bert,my laptop is only a macbook and I have to use the old computer in my family to use cuda , so I do not have the result of the Bert,but the code works fine just the speed is very slow)
How to make dataset:
In this dataset,every sentence is labeld based on the BIO criterion,therefore I have to extract it as sentences rather than only as words.
