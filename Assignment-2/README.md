# Train Logs

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003150000027380884.
60000/60000 [==============================] - 5s 76us/step - loss: 0.1840 - acc: 0.9420 - val_loss: 0.0712 - val_acc: 0.9774
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0033075000043027106.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0688 - acc: 0.9786 - val_loss: 0.0586 - val_acc: 0.9820
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0034728749189525845.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0558 - acc: 0.9824 - val_loss: 0.0733 - val_acc: 0.9782
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0036465186160057786.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0478 - acc: 0.9847 - val_loss: 0.0315 - val_acc: 0.9896
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.003828844497911632.
60000/60000 [==============================] - 4s 61us/step - loss: 0.0447 - acc: 0.9856 - val_loss: 0.0259 - val_acc: 0.9909
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.004020286747254432.
60000/60000 [==============================] - 4s 61us/step - loss: 0.0412 - acc: 0.9871 - val_loss: 0.0365 - val_acc: 0.9877
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.004221301060169935.
60000/60000 [==============================] - 4s 63us/step - loss: 0.0389 - acc: 0.9875 - val_loss: 0.0297 - val_acc: 0.9908
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0041368750389665365.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0372 - acc: 0.9885 - val_loss: 0.0278 - val_acc: 0.9906
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.004054137766361237.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0325 - acc: 0.9893 - val_loss: 0.0307 - val_acc: 0.9900
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.003973055211827159.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0327 - acc: 0.9894 - val_loss: 0.0264 - val_acc: 0.9909
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0038935940619558096.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0295 - acc: 0.9902 - val_loss: 0.0324 - val_acc: 0.9909
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.0038157221442088485.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0296 - acc: 0.9907 - val_loss: 0.0247 - val_acc: 0.9929
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.003739407742395997.
60000/60000 [==============================] - 4s 61us/step - loss: 0.0285 - acc: 0.9904 - val_loss: 0.0232 - val_acc: 0.9928
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0036646195966750384.
60000/60000 [==============================] - 4s 63us/step - loss: 0.0277 - acc: 0.9913 - val_loss: 0.0341 - val_acc: 0.9899
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0025652336655184625.
60000/60000 [==============================] - 4s 63us/step - loss: 0.0230 - acc: 0.9928 - val_loss: 0.0212 - val_acc: 0.9931
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0017956636147573588.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0177 - acc: 0.9944 - val_loss: 0.0204 - val_acc: 0.9929
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.0012569645303301513.
60000/60000 [==============================] - 4s 62us/step - loss: 0.0163 - acc: 0.9948 - val_loss: 0.0188 - val_acc: 0.9941
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0008798751630820334.
60000/60000 [==============================] - 4s 63us/step - loss: 0.0149 - acc: 0.9951 - val_loss: 0.0186 - val_acc: 0.9937
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0006159126060083508.
60000/60000 [==============================] - 4s 63us/step - loss: 0.0134 - acc: 0.9957 - val_loss: 0.0202 - val_acc: 0.9936
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.00043113882420584557.
60000/60000 [==============================] - 4s 63us/step - loss: 0.0130 - acc: 0.9956 - val_loss: 0.0190 - val_acc: 0.9935
<keras.callbacks.History at 0x7f898a27bb38>


Acc reached in Epoch: 17

Model has ~ 8k params.
It has only 16 kernels for each convolution - kept so to keep the params low. Used Dropout to compensate for it.
Used LR Schedule to first increase the LR rate till epoch 7, then decrease it gradually.
Used batch size of 128.
