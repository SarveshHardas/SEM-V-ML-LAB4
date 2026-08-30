# Machine Learning Practical - Lab 4

## Lab 4: Decision Tree Classification

### Aim
To implement the Decision Tree Classification algorithm on a dataset.

### Objective
To implement and evaluate a Decision Tree Classification model using the Wine Quality dataset.

## Dataset Used

**Dataset:** Wine Quality - Red Wine Dataset

**File:** `winequality-red.csv`

The dataset contains chemical properties of red wine samples and their corresponding quality scores.

### Features Used

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

### Target Variable

- `quality`

## Technologies and Libraries Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Implementation

The practical includes:

1. Loading the Wine Quality dataset
2. Inspecting the dataset
3. Checking and removing duplicate records
4. Performing descriptive statistical analysis
5. Performing univariate analysis
6. Performing bivariate analysis
7. Performing outlier analysis using the IQR method
8. Performing multivariate analysis
9. Preparing features and target variable
10. Splitting the dataset into training and testing sets
11. Implementing Decision Tree Classification
12. Using Entropy as the splitting criterion
13. Generating predictions
14. Evaluating the model using accuracy, precision, recall and F1-score
15. Generating a confusion matrix
16. Visualizing the Decision Tree

## Model Used

**Algorithm:** Decision Tree Classifier

**Criterion:** Entropy

**Random State:** 42

**Train-Test Split:** 80:20

## Results

- Original Dataset: 1599 rows × 12 columns
- Duplicate Records Removed: 240
- Cleaned Dataset: 1359 rows × 12 columns
- Training Samples: 1087
- Testing Samples: 272
- Training Accuracy: 100%
- Test Accuracy: 49.63%
- Tree Depth: 18
- Number of Leaves: 299

The difference between training and testing accuracy indicates that the Decision Tree model is highly complex and shows signs of overfitting.

## Files

- `Lab_4_B_04_SarveshHardas.ipynb` - Google Colab notebook containing the implementation
- `winequality-red.csv` - Dataset used for the practical
- `README.md` - Description of the practical

## Student Details

**Name:** Sarvesh Hardas 
**Roll No:** 04
**Section:** B 
**Batch:** B1

## Conclusion

The Decision Tree Classification algorithm was successfully implemented on the Wine Quality dataset using Entropy as the splitting criterion. The model achieved 100% accuracy on the training data and approximately 49.63% accuracy on the test data. The difference indicates overfitting and demonstrates the importance of controlling Decision Tree complexity for better generalization.
