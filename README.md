# credicxo
 The task is to classify data as musk or non-musk. I have used LSTM as a deep learning model. The data is a little imbalanced as the data belonging to class 0 is more than 5 times belonging to class 1, hence some data is randomly selected from class 0. The data has is split in  80:20 ratio for training and validation.'Adam' is used as an optimizer and 'categorical_crossentropy' as loss function. The model is trained on 30 epoch and 32 as batch_size. Since it's a classification we have constructed confusion matrix, ROC curve and also computed accuracy, precision, recall, f1score.
