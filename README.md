# COVID-19_Image_Classification

![preview](https://github.com/KongpolC/COVID-19_Image_Classification/blob/master/images/preview.png)

Apply transfer learning from ResNet50 v.2 with weights from ImageNet to classify chest X-ray images into 3 classes which are

``` classes
0: COVID-19 infected
1: Normal
2: Pneumonia from causes other than COVID-19
```

Trained on 680 images (200-230-250) and validated on 85 images (25-35-25)

## Result

![confusion_matrix](https://github.com/KongpolC/COVID-19_Image_Classification/blob/master/images/confusion_matrix.png)

``` metrics
              precision    recall  f1-score   support

       covid       0.82      0.92      0.87        25
      normal       0.68      0.77      0.72        35
   pneumonia       0.65      0.44      0.52        25

    accuracy                           0.72        85
   macro avg       0.71      0.71      0.70        85
weighted avg       0.71      0.72      0.71        85

Average F1-Score = 0.7039
```
