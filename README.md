## Introduction ##

- A classification task implement in pytorch, contains some neural networks in [models](https://github.com/bamtercelboo/cnn-lstm-bilstm-deepcnn-clstm-in-pytorch/tree/master/models).

* Recenely,  I've readjusted the code structure to make it easier to read. 
	* The old version in the branch of [old-version-17](https://github.com/bamtercelboo/cnn-lstm-bilstm-deepcnn-clstm-in-pytorch/tree/old_version_17), It still works directly. 
	* The newest version in here([master](https://github.com/bamtercelboo/cnn-lstm-bilstm-deepcnn-clstm-in-pytorch)), It also can works directly now.

## Requirement ##

	pyorch : 0.3.1
	python : 3.6.1
	torchtext: 0.2.1
	cuda : 8.0 (support cuda speed up, can chose)

## Usage ##
 
modify the config file, see the Config directory([here](https://github.com/bamtercelboo/cnn-lstm-bilstm-deepcnn-clstm-in-pytorch/tree/master/Config)) for detail.  

	1、python main.py
	2、python main.py --config_file ./Config/config.cfg 

## Model ##

- Contains some neural networks implement in pytorch, see the [models](https://github.com/bamtercelboo/cnn-lstm-bilstm-deepcnn-clstm-in-pytorch/tree/master/models) for detail.

## Data ##

- SST-1 and SST-2.

## Result ##

- I haven't adjusted the hyper-parameters seriously, you can also see train log in [here](https://github.com/bamtercelboo/cnn-lstm-bilstm-deepcnn-clstm-in-pytorch/tree/master/result).
- The following test set accuracy are based on the best dev set accuracy.

![](https://i.imgur.com/HsJe3Qz.jpg)

## Reference ##

- [基于pytorch的CNN-LSTM神经网络模型调参小结](http://www.cnblogs.com/bamtercelboo/p/7469005.html "基于pytorch的CNN-LSTM神经网络模型调参小结")
- [Convolutional Neural Networks for Sentence Classification](https://arxiv.org/pdf/1408.5882.pdf)
-  [Context-Sensitive Lexicon Features for Neural Sentiment Analysis](https://arxiv.org/pdf/1408.5882.pdf)

## Question ##

- if you have any question, you can open a issue or email `bamtercelboo@{gmail.com, 163.com}`.

- if you have any good suggestions, you can PR or email me.
