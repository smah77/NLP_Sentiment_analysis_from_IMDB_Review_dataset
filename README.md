
#Dataset1: imdb_reviews
Description:
Large Movie Review Dataset. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well.

Homepage: http://ai.stanford.edu/~amaas/data/sentiment/

Source code: tfds.text.IMDBReviews

Versions:

1.0.0 (default): New split API (https://tensorflow.org/datasets/splits)
Download size: 80.23 MiB


#Dataset2: imdb_reviews/subwords8k
Config description: Uses tfds.deprecated.text.SubwordTextEncoder with 8k vocab size

Features:


FeaturesDict({
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=2),
    'text': Text(shape=(None,), dtype=tf.int64, encoder=<SubwordTextEncoder vocab_size=8185>),
})

***Used Biderctional LSTM, GRU, Conv1D, Embedding, Global Avg Pooling, Global Max Pooling***