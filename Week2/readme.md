# APPROACH
First I reduced the number of channel from 32 to 16 in second layer to reduce the number of parameters to 14,060.

Then to increase the accuracy decreased dropout rate near output and increased the rate near input. I believe this reduces any chances of overfitting of training data without much loss of information near the output, thus enabling better learning. 


# MODEL SCORE
model.evaluate(X_test, Y_test, verbose=0):
[0.018090104812802748, 0.9945]


# EPOCH LOG:

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 20s 335us/step - loss: 0.4046 - acc: 0.9179 - val_loss: 0.0957 - val_acc: 0.9816
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 7s 118us/step - loss: 0.1285 - acc: 0.9707 - val_loss: 0.0513 - val_acc: 0.9868
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0936 - acc: 0.9769 - val_loss: 0.0391 - val_acc: 0.9908
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0780 - acc: 0.9793 - val_loss: 0.0411 - val_acc: 0.9897
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0690 - acc: 0.9816 - val_loss: 0.0282 - val_acc: 0.9929
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0624 - acc: 0.9831 - val_loss: 0.0319 - val_acc: 0.9918
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0586 - acc: 0.9832 - val_loss: 0.0257 - val_acc: 0.9929
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0550 - acc: 0.9839 - val_loss: 0.0242 - val_acc: 0.9936
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0528 - acc: 0.9851 - val_loss: 0.0241 - val_acc: 0.9937
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 7s 118us/step - loss: 0.0492 - acc: 0.9859 - val_loss: 0.0232 - val_acc: 0.9927
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0476 - acc: 0.9866 - val_loss: 0.0220 - val_acc: 0.9936
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0454 - acc: 0.9869 - val_loss: 0.0209 - val_acc: 0.9947
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 7s 116us/step - loss: 0.0423 - acc: 0.9882 - val_loss: 0.0201 - val_acc: 0.9942
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 7s 115us/step - loss: 0.0412 - acc: 0.9880 - val_loss: 0.0196 - val_acc: 0.9946
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 7s 116us/step - loss: 0.0415 - acc: 0.9876 - val_loss: 0.0193 - val_acc: 0.9943
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 7s 116us/step - loss: 0.0393 - acc: 0.9886 - val_loss: 0.0195 - val_acc: 0.9940
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 7s 116us/step - loss: 0.0374 - acc: 0.9891 - val_loss: 0.0184 - val_acc: 0.9945
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 7s 116us/step - loss: 0.0373 - acc: 0.9899 - val_loss: 0.0194 - val_acc: 0.9941
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0373 - acc: 0.9898 - val_loss: 0.0177 - val_acc: 0.9944
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 7s 117us/step - loss: 0.0336 - acc: 0.9905 - val_loss: 0.0181 - val_acc: 0.9945
<keras.callbacks.History at 0x7f2098ea77f0>
