# Learning Gender-Neutral Word Embeddings (EMNLP 2018)
[Jieyu Zhao](http://jyzhao.net), Yichao Zhou, Zeyu Li, [Wei Wang](http://web.cs.ucla.edu/~weiwang/), [Kai-Wei Chang](http://kwchang.net) 

## Abstract
Word embedding models have become a fundamental component in a wide range of Natural Language Processing (NLP) applications. However, embeddings trained on human-generated corpora have been demonstrated to inherit strong gender stereotypes that reflect social constructs. To address this concern, in this paper, we propose a novel training procedure for learning gender-neutral word embeddings. Our approach aims to preserve gender information in certain dimensions of word vectors while compelling other dimensions to be free of gender influence. Based on the proposed method, we generate a Gender-Neutral variant of GloVe (GN-GloVe). Quantitative and qualitative experiments demonstrate that GN-GloVe successfully isolates gender information without sacrificing the functionality of the embedding model.

------
## Updates:
In Table 1 and 3, it should be "Hard-GloVe". And on Page 5, it should be "OntoNotes". 

Our pretrained word embeddings can be found [here](https://drive.google.com/a/g.ucla.edu/file/d/1v82WF43w-lE-vpZd0JC1K8WYZQkTy_ii/view?usp=sharing).

The seed words we use in our paper is under [wordlist](/wordlist).

The SemBias dataset can be found under [SemBias](/SemBias/).

You can run the code same way as original GloVe: https://github.com/stanfordnlp/GloVe 

### License
See the LICENSE file.
