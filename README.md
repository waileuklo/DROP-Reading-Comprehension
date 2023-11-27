# DROP-Reading-Comprehension
An extended QANet architecture to solve the DROP dataset

## Structure

QANet_main.py: code for training QANet.

trainer/QANet_trainer.py: trainer.

model/QANet_model.py: defines NAQANet.

data_loader/SQuAD.py: DROP data loader.

Other codes are utils or neural network common modules library.

## Acknowledge

The QANet structure implementation is mainly based on https://github.com/BangLiu/QANet-PyTorch, https://github.com/hengruo/QANet-pytorch, https://github.com/andy840314/QANet-pytorch- and https://github.com/hackiey/QAnet-pytorch.

For a TensorFlow implementation, please refer to https://github.com/NLPLearn/QANet.
