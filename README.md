The PDF file (TheoreticalDetails.pdf) explains how to calculate accuracy, weighted recall, weighted precision, and weighted F1-score for multi-class classification (more than 2 classes). The Python code (multi_class_acc_rec_prec_f1.py) efficiently calculates the accuracy, weighted recall, weighted precision, and weighted F1-score. It also includes a simple example that is shown below.

Run: python3 multi_class_acc_rec_prec_f1.py

Simple Example:

Inputs:

1) y_true = [1, 2, 0, 0, 1, 2, 2, 0, 0, 1, 2, 1, 1, 1, 1, 2, 2, 2, 2, 2, 0, 0, 0, 2, 2, 1, 0, 2]
2) y_pred = [0, 1, 0, 1, 1, 0, 2, 0, 0, 2, 2, 1, 1, 1, 1, 2, 2, 2, 2, 2, 0, 0, 0, 1, 1, 2, 2, 0]
3) num_classes = 3

Output:

1) Accuracy = 0.6428571428571429
2) Weighted recall = 0.6428571428571429
3) Weighted precision = 0.6492063492063492
4) Weighted F1-score = 0.6424751718869367

