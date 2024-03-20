# thai-char-embedding
We have implemented Word2vec Continuous Bag of Words (CBOW), Skipgram, and Glove models on a Thai corpus to obtain Thai character embeddings

## Data
The model has been trained on the Version 1 dataset, which includes the following files:

- lexicon_th.txt
- female_names_th.txt
- male_names_th.txt
- surnames_th.txt

## Metric
We are using perplexity as the metric to evaluate the Word2Vec models on the trained corpus.

## TODO :
If you would like to contribute to this project, we would greatly appreciate it. Here are some of the tasks that are still pending:

- Architecture
    - ✅CBOW
    - ✅Skipgram
    - ✅Glove (Need someone to valid the code)

- Quickstart
    - Create notebook to demonstrate how to easily use the embedding vectors from cbow, skipgram, and glove

- Metric
    - ❌ Upload perplexity of the model
    - ❌ Analogy evaluation (ราชินี - ราชา + พ่อบ้าน = แม่บ้าน). Please note that character analogy is not as straightforward as word analogy, as characters may not have inherent meanings.

- ❌ Hyperparameter tuning (embedding_size, window_size, ..) 


- Testing
    - ❌ Benchmarking for related tasks performance such as Thai tokenization, language model 

Feel free to get involved in any of these tasks to help improve the project.

## TSNE 
- CBOW
    (emb_size = 32)
    ![cbow32_8](https://github.com/SaranAI/thaichar2vec/blob/main/assets/images/tsne_cbow_8_32.png?raw=true)

- SkipGram
    (emb_size = 32)
    ![skipgram32_8](https://github.com/SaranAI/thaichar2vec/blob/main/assets/images/tsne_skipgram_8_32.png?raw=true)

- GloVe
    (emb_size = 32)
    ![glove32_8](https://github.com/SaranAI/thaichar2vec/blob/main/assets/images/tsne_glove_8_32.png?raw=true)