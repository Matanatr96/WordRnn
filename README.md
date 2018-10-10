# word-rnn-tensorflow
Multi-layer Recurrent Neural Networks (LSTM, RNN) for word-level language models in Python using TensorFlow.

Full credit goes to sherjilozair; this is mostly reused code from https://github.com/sherjilozair/char-rnn-tensorflow

# Requirements
- [Tensorflow 1.1.0rc0](http://www.tensorflow.org)

# Basic Usage
To train with default parameters on the tinyshakespeare corpus, run:
```bash
python train.py
```

To test on trained model, run:
```bash
python sample.py --pick 2 --width 4
```

Refer to sample.py for all editable parameters

# Updating trained model
```bash
python train.py --init_from /save
```