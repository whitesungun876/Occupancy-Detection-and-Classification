This project applies machine learning techniques to predict building occupancy and temperature, leveraging k-Nearest Neighbors (k-NN) classification, Linear Regression, and Principal Component Analysis (PCA) on the Occupancy Dataset.

Project Overview
Data Preprocessing & Visualization:

Cleaned and visualized data to understand the distribution of occupancy status and key environmental factors.

Plotted correlations to evaluate feature correlations with the target variable (occupancy).

Principal Component Analysis (PCA):

Performed PCA on the Occupancy Dataset to reduce dimensionality and visualize the variance explained by the principal components.

Generated a variance vs. PC index plot, showing how the variance stabilizes at a low level for higher principal components.

k-NN Classification:

Built a k-NN classifier to predict occupancy, optimizing the model using 5-fold cross-validation to select the best hyperparameters.

Linear Regression for Temperature Prediction:

Applied linear regression to predict the temperature of a building based on environmental factors like relative humidity, light, and CO2 levels.

Analyzed the relationship between these features and temperature, reporting the regression coefficients.

Getting Started
To run the Jupyter Notebook, follow these steps to set up the environment:

Prerequisites
You will need the following Python packages:

numpy

pandas

scikit-learn

matplotlib

seaborn

Install these dependencies using pip:

pip install numpy pandas scikit-learn matplotlib seaborn
Running the Notebook
Clone this repository to your local machine:

git clone https://github.com/yourusername/repository-name.git
Navigate into the project directory:

cd repository-name
Launch Jupyter Notebook:

jupyter notebook
Open the Jieyu_Lian.3.ipynb notebook and follow the steps to run the analysis.

Dataset
The Occupancy Dataset contains environmental data from a building to detect occupancy. It includes:

Temperature (Celsius)

Relative Humidity (%)

Light (lux)

CO2 (ppm)

Occupancy (class label: 0 = not occupied, 1 = occupied)

The dataset is available in the following CSV files:

OccupancyTrain.csv

OccupancyTest.csv

Results
PCA: Reduced data dimensionality and visualized the variance captured by the principal components, showing how the variance stabilizes for higher components.

k-NN Classification: Predicted building occupancy, optimized using 5-fold cross-validation for best model performance.

Linear Regression: Predicted building temperature from environmental features like humidity, light, and CO2 levels, analyzing the relationships between these factors.

Conclusion
This project demonstrates the application of PCA, k-NN classification, and linear regression to real-world environmental data for building occupancy detection and temperature prediction. These techniques have practical applications in smart buildings and energy efficiency.

License
This project is licensed under the MIT License - see the LICENSE file for details.



