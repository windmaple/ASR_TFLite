# ASR_TFLite

This repository provides an Automatic Speech Recognition (ASR) models in TensorFlow Lite (TFLite) for TensorFlow 2.x. These models primarily come from two repositories - [asr](https://www.huylenguyen.com/asr) and [TensorFlowASR](https://github.com/TensorSpeech/TensorFlowASR). We provide end-to-end Jupyter Notebooks that show the inference process using TFLite. \
[English-ASR pip wheel](https://pypi.org/project/english-asr/1.2/)\
[TF Hub](https://tfhub.dev/neso613/lite-model/ASR_TFLite/pre_trained_models/English/1)

## Installation
- tensorflow
- numpy
- librosa

## Models
- [Conformer Transducer](https://arxiv.org/abs/2005.08100) using [LibriSpeech](http://www.openslr.org/12) dataset.

## References
- [TensorFlow Lite Conversion](https://www.tensorflow.org/lite/convert)
- [Float16 quantization in TensorFlow Lite](https://www.tensorflow.org/lite/performance/post_training_float16_quant)
- [Dynamic-range quantization in TensorFlow Lite](https://www.tensorflow.org/lite/performance/post_training_quant)
