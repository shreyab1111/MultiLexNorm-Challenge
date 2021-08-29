# MultiLexNorm- wNUT 2021 Challenge

Lexical Normalization on Twitter data from Multiple Languages

Each file is named in a particular format: <language>-<task>-<model>-<mode>
  For example, en-ln-se2seq-n represents a file involving English dataset (en), Working on Lexical Normalisation (ln), model is Sequence to Sequence using LSTM (seq2seq), and mode is normal (n).
  In contrast, es-ln-seq2seq-a will represent a file involving Spanish dataset (es), Working on Lexical Normalisation (ln), model is Sequence to Sequence using LSTM (seq2seq), and mode is attention (a).

I have tried to implement four Sequence models - with LSTM, Bidirectional LSTM, Attention Models in the Decoder, and Transformer, respectively.
I have used Character level embedding for the modeling.

This is the site link to the challenge - http://noisy-text.github.io/2021/multi-lexnorm.html
