# Natural Language Inference

1. We will use an encoder (either a CNN or an RNN) to map each string of
text (hypothesis and premise) to a fixed-dimension vector representation.

2. We will interact the two hidden representations and output a 3-class soft-
max. (To keep things simple, we will simply concatenate the two repre-
sentations, and feed them through a network of 2 fully-connected layers.)

Data: https://nlp.stanford.edu/projects/snli/
