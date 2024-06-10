1. **Data Preprocessing**:
   - Loaded the dataset and checked for missing values (there were none).
   - Examined descriptive statistics to understand the dataset.
   - Explored the distribution of age and duration using box plots and histograms.
   - Transformed categorical variables into dummy variables.
   - Converted 'pdays' values of -1 to a large value (10000) to indicate clients not previously contacted.
   - Created a new column 'recent_pdays' and dropped 'pdays'.
   - Combined similar job categories, education categories, and poutcome categories.

2. **Exploratory Data Analysis**:
   - Investigated the relationship between variables, such as age and balance.
   - Analyzed the characteristics of people who signed up for a term deposit, including their age, balance, duration of the last contact, etc.
   - Explored specific scenarios, like people with loans or credit defaults who signed up for term deposits.

3. **Data Visualization**:
   - Utilized bar charts to visualize the relationship between job category, previous outcome, and deposit subscription.
   - Examined the correlation between the duration of the call and the previous outcome.

4. **Classification**:
   - Calculated the correlation matrix to understand the relationships between variables.
   - Prepared the dataset for classification by creating dummy variables.
   - Identified correlations between various features and the target variable ('deposit_cat').

5. **Model Building**:
   - Implemented a decision tree classifier to predict whether a client will subscribe to a term deposit.
   - Split the dataset into training and testing sets.
   - Trained the decision tree model and evaluated its performance using metrics like accuracy, precision, recall, and F1-score.
