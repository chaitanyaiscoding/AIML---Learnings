# Random Forest Classifier Implementation

This project demonstrates how to implement a Random Forest Classifier (and Decision Tree for comparison) using Python and scikit-learn on an e-commerce dataset.

## Dataset
- **File:** `shop_smart_ecommerce.csv`
- The dataset contains features such as ExitRates, PageValues, SpecialDay, Month, OperatingSystems, Browser, Region, TrafficType, VisitorType, Weekend, and the target variable Revenue.

## Steps Performed

1. **Import Libraries**
   - pandas, scikit-learn modules for preprocessing, modeling, and evaluation.

2. **Load Dataset**
   - Read the CSV file into a pandas DataFrame.

3. **Data Preprocessing**
   - Checked for missing values.
   - Split the data into features (`X`) and target (`y`).
   - Encoded categorical columns (e.g., Month, VisitorType) using `LabelEncoder`.

4. **Train-Test Split**
   - Split the data into training and testing sets using `train_test_split`.

5. **Model Training**
   - Trained a `DecisionTreeClassifier` (for baseline) and can be extended to `RandomForestClassifier`.

6. **Evaluation**
   - Predicted on the test set and calculated accuracy for both training and testing sets.

## How to Run

1. Make sure you have the required packages installed:

```bash
pip install pandas scikit-learn
```

2. Open the notebook `Random_forest.ipynb` and run the cells sequentially.

## Key Files
- `Random_forest.ipynb`: Jupyter notebook with all code and explanations.
- `shop_smart_ecommerce.csv`: Dataset used for training and testing.

## Results
- The notebook provides accuracy scores for both training and testing sets.
- You can extend the notebook to include Random Forest and compare its performance with Decision Tree.

---

**Author:** Chaitanya
