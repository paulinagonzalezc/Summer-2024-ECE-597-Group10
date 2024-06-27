# Summer-2024-ECE-597-Group10

## *Logistic Regression*

## Results of base LR

- **AUC Score:** `0.9985969484842256` 
- **Balanced Accuracy Score:** `0.8597495993905557` 
- **F1 Score:** `0.8315565031982942` 
- **Confusion Matrix:**
[[51724 3]
[ 76 195]]

### Optimization Process

1. **Threshold Optimization:**
   - Predicted probabilities for the test data.
   - Evaluated performance metrics (F1 score, precision, recall, balanced accuracy) across a range of thresholds from 0 to 1 in increments of 0.01.
   - Selected the threshold that maximized the F1 score, balancing precision and recall effectively.

2. **Evaluation:**
   - Evaluated the model at the best threshold and generated performance metrics such as AUC score, balanced accuracy, and confusion matrix.

## Results with optimization

After optimization, the best threshold was found to be `0.1`. The evaluation metrics at this threshold are as follows:

- **AUC Score:** `0.9993083187158355` 
- **Balanced Accuracy Score:** `0.9315603269706407` 
- **F1 Score:** `0.8948374760994263` 
- **Confusion Matrix:**
[[51727 0]
[ 74 197]]

Below is a plot showing how the F1 score, precision, recall, and balanced accuracy vary with the threshold. The best threshold is highlighted in red.

![Metrics vs. Threshold](/ML_Techniques/LR_optimization_results.png)

## *Logistic Regression with new balanced dataset*

## Results of base LR

- **AUC Score:** `0.9953506511382493` 
- **Balanced Accuracy Score:** `0.9522638811357258` 
- **F1 Score:** `0.9480249480249481` 
- **Confusion Matrix:**
[[519 2]
[ 23 228]]

## Results with optimization

After optimization, the best threshold was found to be `0.4`. The evaluation metrics at this threshold are as follows:

- **AUC Score:** `0.9953506511382493` 
- **Balanced Accuracy Score:** `0.9583126228292205` 
- **F1 Score:** `0.9527720739219713` 
- **Confusion Matrix:**
[[517 4]
[ 19 232]]

Below is a plot showing how the F1 score, precision, recall, and balanced accuracy vary with the threshold. The best threshold is highlighted in red.

![Metrics vs. Threshold](/ML_Techniques/LR_optimization_results_balanced.png)

## *Logistic Regression with new balanced dataset & new processing*

## Results 

- **AUC Score:** `0.9970261657496791` 
- **Balanced Accuracy Score:** `0.9687215173872836` 
- **F1 Score:** `0.9626769626769627` 
- **Confusion Matrix:**
[[754   9]
 [ 20 374]]

![Metrics vs. Threshold](/ML_Techniques/LR_optimization_results_balanced_newpreprocessing.png)

