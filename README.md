# Bank Fraud Detection Using CNN, Fuzzy Logic, and Genetic Algorithm

This project implements a hybrid approach to detect bank fraud by combining **Fuzzy Logic**, **Genetic Algorithms (GA)**, and **Convolutional Neural Networks (CNN)**. The solution leverages fuzzy membership functions for feature evaluation, optimizes detection thresholds using a genetic algorithm, and can be extended with CNN for feature extraction and advanced predictions.


#Features
- **Data Preprocessing**: Handles missing values and prepares the dataset for analysis.
- **Fuzzy Logic**: Utilizes fuzzy membership functions to evaluate transaction features like amounts and balances.
- **Genetic Algorithm**: Optimizes thresholds for fuzzy membership functions to maximize detection accuracy.
- **Fraud Detection**: Predicts fraudulent transactions based on optimized thresholds.
- **Visualization**: Provides insights into threshold evolution and membership functions over generations.


#Technologies Used
- **Python Libraries**: 
  - `NumPy`, `Pandas` for data manipulation
  - `Matplotlib` for visualization
  - `sklearn` for accuracy evaluation
- **Genetic Algorithm**: Applied for threshold optimization.
- **Fuzzy Logic**: For feature evaluation and fraud classification.
- **CNN (optional)**: For advanced feature extraction and classification.


---

#Dataset Description
The dataset consists of transaction details such as:
- **Amount**: The transaction amount.
- **Old Balance**: The balance before the transaction.
- **New Balance**: The balance after the transaction.
- **Is Fraud**: Indicator of whether the transaction is fraudulent.

---

#Methodology

1. **Data Preprocessing**: 
   - Handle missing values using median or mode.
   - Normalize the data for better performance.

2. **Fuzzy Logic**:
   - Define fuzzy membership functions for transaction features.
   - Classify transactions based on fuzzy rules.

3. **Genetic Algorithm**:
   - Randomly initialize thresholds for fuzzy functions.
   - Evaluate fitness using the `accuracy_score` metric.
   - Apply selection, crossover, and mutation to evolve the population.

4. **Visualization**:
   - Monitor fitness improvement and threshold evolution.
   - Visualize optimized fuzzy membership functions.

5. **Optional CNN Extension**:
   - Train a CNN model for feature extraction and enhanced predictions.




