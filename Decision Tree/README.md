# Decision Tree Classifier Implementation

This project demonstrates how to implement a Decision Tree Classifier using Python and scikit-learn on an e-commerce dataset.

## Dataset
- **File:** `shop_smart_ecommerce.csv`
- The dataset contains features such as ExitRates, PageValues, SpecialDay, Month, OperatingSystems, Browser, Region, TrafficType, VisitorType, Weekend, and the target variable Revenue.

## Steps Performed

1. **Import Libraries**
   - pandas, numpy, scikit-learn modules, and matplotlib for visualization.

2. **Load Dataset**
   - Read the CSV file into a pandas DataFrame.

3. **Data Preprocessing**
   - Checked for missing values.
   - Split the data into features (`X`) and target (`y`).
   - Encoded categorical columns (e.g., Month, VisitorType) using `LabelEncoder`.

4. **Train-Test Split**
   - Split the data into training and testing sets using `train_test_split`.

5. **Model Training**
   - Trained a `DecisionTreeClassifier` on the training data.

6. **Evaluation**
   - Predicted on the test set and calculated accuracy.
   - Visualized the decision tree using `plot_tree` from scikit-learn and matplotlib.

7. **Pre-Pruning and Post-Pruning**
   - Experimented with different `max_depth` and `min_samples_split` values for pre-pruning.
   - Used cost-complexity pruning (`ccp_alpha`) for post-pruning and selected the best model based on accuracy.

## How to Run

1. Make sure you have the required packages installed:

```bash
pip install pandas numpy scikit-learn matplotlib
```

2. Open the notebook `Decision_tree_classifier.ipynb` and run the cells sequentially.

## Key Files
- `Decision_tree_classifier.ipynb`: Jupyter notebook with all code and explanations.
- `shop_smart_ecommerce.csv`: Dataset used for training and testing.

## Results
- The notebook provides accuracy scores for different tree depths and pruning parameters.
- Visualizations of the decision tree are included for better interpretability.

---

**Author:** Chaitanya
