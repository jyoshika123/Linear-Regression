# LinearRegression
training a model from housing dataset
1. **Loaded the dataset**  
2. **Checked for missing values** → no missing values in `area` or `price`
3. **Removed outliers** using IQR method for `area` and `price`
4. **Split the data** into training and testing (80% train, 20% test)
5. **Trained a LinearRegression() model**
6. **Predicted prices** on the test data
7. **Evaluated model** using:
   - R² Score
   - Mean Squared Error
8. **Plotted** the regression line using `matplotlib`
9. **Tested** with my own input (example: area = 3000 sqft).

