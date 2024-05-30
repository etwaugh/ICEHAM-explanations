This is genuinely the final, and best model obtained.

Optimiser SGD, 0.01 lr, 0.8 momentum with scheduler step size 5 and gamma 0.1. Trained for 15 epochs with first 7 layers frozen.

Trained for extra 5 epochs, same optimiser parameters, step size 2 and gamma 0.5, but with layer1, layer2 and layer3 unfrozen.

Final Losses: train `0.06998051889240742` valid `0.23118671774864197`

```
Classification Report:
              precision    recall  f1-score   support

           0       0.95      0.97      0.96       695
           1       0.78      0.80      0.79        96
           2       0.86      0.84      0.85        92
           3       0.89      0.85      0.87        48
           4       0.86      0.80      0.83        45
           5       0.90      0.90      0.90        10
           6       0.88      0.44      0.58        16

    accuracy                           0.92      1002
   macro avg       0.87      0.80      0.83      1002
weighted avg       0.92      0.92      0.92      1002
```

![image](https://github.com/etwaugh/ICEHAM-explanations/assets/114034917/21640be7-d204-4488-b88f-ea425015e940)

![image](https://github.com/etwaugh/ICEHAM-explanations/assets/114034917/06e8af12-9c5b-4bcb-a4ee-97133f4e0a88)
