# word_embedding_assignment
Word Embedding Assignment

In this assignment , we have to
* Download the IMDB dataset
* Tokenize the records and create train and validation datasets
* Download the Glove pretrained Word Embedding
* Define a model which uses Glove pretrained Word Embedding
* Train the model on IMDB dataset 

The training logs:


Train on 8000 samples, validate on 9243 samples
Epoch 1/10
8000/8000 [==============================] - 4s 506us/step - loss: 0.7381 - acc: 0.6911 - val_loss: 0.5357 - val_acc: 0.7372
Epoch 2/10
8000/8000 [==============================] - 1s 123us/step - loss: 0.5402 - acc: 0.7446 - val_loss: 0.5157 - val_acc: 0.7599
Epoch 3/10
8000/8000 [==============================] - 1s 109us/step - loss: 0.4736 - acc: 0.7855 - val_loss: 0.5497 - val_acc: 0.7486
Epoch 4/10
8000/8000 [==============================] - 1s 115us/step - loss: 0.4240 - acc: 0.8131 - val_loss: 0.5128 - val_acc: 0.7432
Epoch 5/10
8000/8000 [==============================] - 1s 115us/step - loss: 0.3583 - acc: 0.8450 - val_loss: 0.5109 - val_acc: 0.7698
Epoch 6/10
8000/8000 [==============================] - 1s 125us/step - loss: 0.3156 - acc: 0.8648 - val_loss: 0.6290 - val_acc: 0.6852
Epoch 7/10
8000/8000 [==============================] - 1s 117us/step - loss: 0.2570 - acc: 0.8914 - val_loss: 1.0816 - val_acc: 0.5439
Epoch 8/10
8000/8000 [==============================] - 1s 125us/step - loss: 0.2219 - acc: 0.9091 - val_loss: 1.3811 - val_acc: 0.7320
Epoch 9/10
8000/8000 [==============================] - 1s 111us/step - loss: 0.2004 - acc: 0.9210 - val_loss: 0.7722 - val_acc: 0.6781
Epoch 10/10
8000/8000 [==============================] - 1s 115us/step - loss: 0.1520 - acc: 0.9410 - val_loss: 0.9063 - val_acc: 0.7626

Plots are as loss and accuracy are below:

![Training and Validation Loss Plots](https://github.com/monimoyd/word_embedding_assignment/blob/master/train_validation_loss_plot.png)

![Training and Validation Accuracy Plot](https://github.com/monimoyd/word_embedding_assignment/blob/master/train_validation_accuracy_plot.png)


Best validation accuracy: 76.98





