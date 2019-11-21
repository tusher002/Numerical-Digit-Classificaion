# Numerical-Digit-Classificaion

It is a numerical digit classification system by sign language.
I have applied some image processing techniques - gaussian blur, histogram equalization, edge detection, adaptive mean thresholding
I have applied 2 deep learning architechture here.
i) VGG16      ii)Inception-V3.
Adam ad RMSprop optimzer have been used.
Finally, noticed that VGG16 with adam optimizer works well for my data.
Data courtesy: Ishara Lipi - DIU NLP Lab
Data can be found here- https://drive.google.com/drive/folders/1zS2Zn7CPzl_AksgTghcfDqFh9LCvtDUr
The final results are given below

accuracy: 0.8561151027679443 

              precision    recall  f1-score   support

           0       0.87      0.93      0.90        28
           1       0.85      0.91      0.88        32
           2       0.89      0.86      0.87        28
           3       0.76      0.73      0.75        26
           4       0.90      0.87      0.89        31
           5       0.85      0.97      0.90        29
           6       0.81      0.81      0.81        27
           7       0.87      0.74      0.80        27
           8       0.85      0.81      0.83        27
           9       0.91      0.91      0.91        23

                                       0.86       278
   macro avg       0.86      0.85      0.85       278
weighted avg       0.86      0.86      0.85       278
