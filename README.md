This is a BERT based named entity recognition model used for recognizing mountains 

The sentences were scraped using the reverso context site via the mountain names, this makes sure the sentences have varying style and do not follow the same formula 

Training set has 3 sentences for each known mountain out there. The mountain names are used for annotation used as a target variable
The dataset has to be tokenized 2 times in my case(for annotation and for BERT), I'm sure there is more efficient ways to do that

Model paramaters are pretty basic, just with a custom collating function because the sentences have varying lengtjs

Model has 97% accuracy, precision, recall and f1 scores and seems to be working just fine as this is not a hard task in general
