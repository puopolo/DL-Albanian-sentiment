Resources: 
- The BiLSTM architectures here are adapted and database sourced from: https://github.com/lule-ahmedi/AlbAna/
- Their research: Kastrati, Z.; Ahmedi, L.; Kurti, A.; Kadriu, F.; Murtezaj, D.; Gashi, F. A Deep Learning Sentiment Analyser for Social Media Comments in Low-Resource Languages. Electronics 2021, 10, 1133. https://doi.org/10.3390/electronics10101133
- The dataset used here is the same as above. I only edited their original "AlbAna" datset by deleting all of the columns except for 'Annotation' and 'Comment' for simplicity. Data also downloaded from https://github.com/lule-ahmedi/AlbAna/
- The mBERT architecture is Multilingual BERT (cased), available here: https://github.com/google-research/bert/blob/eedf5716ce1268e56f0a50264a88cafad334ac61/multilingual.md
- FastText embeddings are available for Albanian as vector (bin) here: https://fasttext.cc/docs/en/crawl-vectors.html
- GloVe embeddings are 6B tokens, 400K vocab, uncased, 300d vectors. Source: https://nlp.stanford.edu/projects/glove/
- These files were created and run in Google Colab, so they will require changing the directories if you run them on your own.
