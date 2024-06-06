# Summer-2024-ECE-597-Group10

## Logistic Regression

### Optimization Process

1. **Threshold Optimization:**
   - Predicted probabilities for the test data.
   - Evaluated performance metrics (F1 score, precision, recall, balanced accuracy) across a range of thresholds from 0 to 1 in increments of 0.01.
   - Selected the threshold that maximized the F1 score, balancing precision and recall effectively.

2. **Evaluation:**
   - Evaluated the model at the best threshold and generated performance metrics such as AUC score, balanced accuracy, and confusion matrix.

## Results

After optimization, the best threshold was found to be `0.1`. The evaluation metrics at this threshold are as follows:

- **AUC Score:** `0.9993083187158355` 
- **Balanced Accuracy Score:** `0.9315603269706407` 
- **F1 Score:** `0.8948374760994263` 
- **Confusion Matrix:**
[[51727 0]
[ 74 197]]

Below is a plot showing how the F1 score, precision, recall, and balanced accuracy vary with the threshold. The best threshold is highlighted in red.

![Metrics vs. Threshold](/workspaces/Summer-2024-ECE-597-Group10/ML_Techniques/LR_plot.png)

