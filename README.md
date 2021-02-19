# German-To-English-Translator-Using-Transformers-From-Scratch

## Introduction:
This is an English to German translator built using Transformers. The transformer was implemented from scratch using TensorFlow 2 and the instructions of the paper "Attention Is All You Need"


![alt text](https://pbs.twimg.com/media/DCKhefrUMAE9stK.jpg)

## Data:
The data can be found in:  
https://www.statmt.org/europarl/ 

And the non_breaking_prefixes can be found in this repository:  
https://github.com/moses-smt/mosesdecoder/tree/master/scripts/share/nonbreaking_prefixes

## Training:
I did not have a proper GPU so I used google colab (not pro) for the training. I chose a very very smaller model compared to the paper and I trained it only for 2 epochs.
After one hour of training, the model achieved 24% accuracy at the end of the first epoch and 36% on the second, this could easily be further improved with more epochs and a larger model and more parameter tuning which I don't have the proper GPU for but the results are pretty good considering the small model size and epochs.

## Acknowledgements
This translator is inspired from this udemy course: https://www.udemy.com/course/modern-nlp/
