# TensorFlow Word2Vec

A TensorFlow skip-gram Word2Vec example using negative sampling and the text8 Wikipedia corpus.

## Run

Use Python 3.10 with the pinned dependencies:

```bash
python -m pip install -r requirements.txt
python word2vec.py
```

The script downloads text8 on first run and trains for 3,000,000 steps, so it requires internet access and may take a long time.

## Attribution

The notebook credits Aymeric Damien and the [TensorFlow-Examples project](https://github.com/aymericdamien/TensorFlow-Examples/). The example follows the skip-gram and negative-sampling approach described by Mikolov et al., [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781).