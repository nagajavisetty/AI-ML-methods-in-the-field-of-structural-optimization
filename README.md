## AI/ML methods in the field of structural optimization

1. **Data evaluation and Regression Model analysis**
2. **Mathematical optimization of an objective function**

### Task 1: Data evaluation and Regression Model analysis

#### Files:
- `data_eval_reg_model_analysis.ipynb`: Python code for data evaluation and regression model analysis.
- `data_matrix.csv`: Dataset containing the results of a Design of Experiment study with 100 tests.

#### Instructions:
1. **Load Data**: The program reads the dataset `data_matrix.csv`.
2. **Sensitivity Analysis**: Conducts a sensitivity analysis using correlation plots.
3. **Assess Distribution of Output Variables**: Histograms are used to assess the distribution of output variables.
4. **Split Data**: Splits the data into training and testing sets.
5. **Build Regression Models**: Builds Linear Regression and Support Vector Regression models.
6. **Evaluate Models**: Evaluates the performance of regression models using Mean Squared Error (MSE) and R-squared scores.
7. **Compare Models**: Compares the performance of the built models and selects the best model for each output variable.
8. **Plot Predicted vs Actual Values**: Visualizes the predicted vs actual values for both output variables.

### Task 2: Mathematical optimization of an objective function

#### Files:
- `math_opt_obj_func.ipynb`: Python code for optimizing an objective function.
  
#### Instructions:
1. **Define Objective Function**: Defines the objective function to be optimized.
2. **Optimization Algorithm**: Uses the Nelder-Mead optimization algorithm to minimize the objective function.
3. **Visualize Objective Function**: Creates a 2D visualization of the objective function in x, y-space.
4. **Observations**: Provides observations based on the visualization of the objective function.

### Report:
- `report.pdf`: Contains a detailed report summarizing the approach, analysis, and findings for both tasks.

### How to Run:
1. Ensure you have Python installed on your system.
2. Clone this repository.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Run `data_eval_reg_model_analysis.ipynb` and `math_opt_obj_func.ipynb` to execute the respective tasks.


---
