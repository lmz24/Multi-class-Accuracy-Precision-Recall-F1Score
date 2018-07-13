The PDF file (TheoreticalDetails.pdf) explains how to calculate accuracy, weighted precision, weighted recall, and weighted F1-score for multi-class classification (more than 2 classes). The Python code (multi_class_acc_rec_prec_f1.py) has a function (multi_class_accuracy_precision_f1score) that efficiently calculates the accuracy, weighted precision, weighted recall, and weighted F1-score. It has 3 inputs (y_true, y_pred, num_classes) where y_true is the list of true classes, y_pred is the list of corresponding predicted classes, and num_classes is the total number of classes. Note that y_true and y_pred must contain only whole numbers. For example, 3 classes (‘bird’, ‘cat’, ‘dog’) may be mapped to 0, 1, and 2, respectively. The Python code also includes a simple example that is shown below.

Run: python3 multi_class_acc_rec_prec_f1.py

Simple Example:

- Inputs to multi_class_accuracy_precision_f1score:

  1) y_true = [1, 2, 0, 0, 1, 2, 2, 0, 0, 1, 2, 1, 1, 1, 1, 2, 2, 2, 2, 2, 0, 0, 0, 2, 2, 1, 0, 2]
  2) y_pred = [0, 1, 0, 1, 1, 0, 2, 0, 0, 2, 2, 1, 1, 1, 1, 2, 2, 2, 2, 2, 0, 0, 0, 1, 1, 2, 2, 0]
  3) num_classes = 3

- Outputs:

  1) Accuracy = 0.6428571428571429
  2) Weighted precision = 0.6492063492063492
  3) Weighted recall = 0.6428571428571429
  4) Weighted F1-score = 0.6424751718869367
