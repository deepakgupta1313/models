This file is maintained in reverse chronological order.

## General Information
1.	Run Command	:	python ptb_word_lm.py --data_path=tmp/simple-examples/data/ --model small
2.	DataSet	:	http://www.fit.vutbr.cz/~imikolov/rnnlm/simple-examples.tgz
3.	Official Tutorial Page : https://www.tensorflow.org/versions/master/tutorials/recurrent/

#### 14/03/2017
The main file is /tutorials/rnn/ptb/ptb_word_lm.py.
I have implemented everything as instructed. I have implemented a new function calcLoss() to calculate the loss. The only problem is, when I introduce stop_gradient(), the perplexity goes to inf.