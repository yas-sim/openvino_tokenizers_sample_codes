# OpenVINO Tokenizers sample code

## OpenVINO Tokenizers Extension
[OpenVINO Tokenizers Extension](https://github.com/openvinotoolkit/openvino_tokenizers) is a set of tool to convert the tokenizer into an OpenVINO IR model. It also provides a feature to connect two models into one. This feature allow users to integrate a tokenizer model into a NLP models.  
The code in this repository demonstrates how to convert the tokenizers into OpenVINO models and how to integrate the converted tokenizer model into an NLP model.

|#|file|description|
|---|---|---|
|1|[converting-tokenizer.ipynb](./converting-tokenizer.ipynb)|Download a Tiny-Llama-1.1B tokenizer models from HuggingFace hub, and convert the tokenizer into OpenVINO IR models.|
|2|[sentiment-analysis-tokenizer-integration.ipynb](./sentiment-analysis-tokenizer-integration.ipynb)|Integrate a tokenizer model into a sentiment analysis model.|

## Test environment
OpenVINO 2024.1  
Windows 11
