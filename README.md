### Simple word2vec

This document was to train and test word2vec model
the code to train the model is almost exactly this: https://www.tensorflow.org/tutorials/text/word2vec , but changed slightly, for the sake of learning

The differences are:
1) Changed the input dataset.
2) Changed the negative sample number, window size, batchsize, ...
3) changed the design of the model.
4) wrote a similarity function at the end, the results were bad.
5) imported genism and tested the results with genism, results were great.
6) Since results were good, trained GENISM with data, and the result was bad again :). (DATA ISSUE)


## Result:
I am pretty sure the model sucks unless we feed a very rich data.

