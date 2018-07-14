The PDF file (TheoreticalDetails.pdf) explains how to calculate accuracy, weighted precision, weighted recall, and weighted F1-score for multi-class classification (more than 2 classes). The Python 3 code (multi_class_acc_prec_rec_f1.py) has a function (multi_class_accuracy_precision_f1score) that efficiently calculates the accuracy, weighted precision, weighted recall, and weighted F1-score. It has 3 inputs (y_true, y_pred, num_classes) where y_true is the list of true classes, y_pred is the list of corresponding predicted classes, and num_classes is the total number of classes. Note that y_true and y_pred must contain only whole numbers. For example, 3 classes (‘bird’, ‘cat’, ‘dog’) are mapped to 0, 1, and 2, respectively. The code also includes the same simple example as that in the PDF file, and the generated output is shown below:

Accuracy = 0.6428571428571429<br />
Weighted precision = 0.6492063492063492<br />
Weighted recall = 0.6428571428571429<br />
Weighted F1-score = 0.6424751718869367<br />
