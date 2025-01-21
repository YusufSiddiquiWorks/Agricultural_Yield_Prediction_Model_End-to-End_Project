# Agriculture Yield Prediction Regression Model

## Project Overview
This solo project showcases my expertise in data science and machine learning by developing a robust regression model for agricultural yield prediction. The project covers the entire workflow, including exploratory data analysis (EDA), data preprocessing, feature engineering, model building, and hyperparameter tuning, culminating in deployment on Azure.

## Features
- **Yield Prediction**: Accurately predicts yield based on various input factors such as soil, weather, and crop management practices.
- **Azure Deployment**: The model is deployed and accessible online for seamless integration and usage.
- **Automated CI/CD**: Leveraging GitHub Actions for continuous integration and deployment, ensuring a robust and reliable workflow.

## Live Application
Access the live application here: [Agriculture Yield Prediction App](https://agricultural-yield-predicition-project-d0excudddneufzam.uaenorth-01.azurewebsites.net/)

## Dataset
The model uses a dataset that includes:
- **Properties**: Soil Types, Soil Regions, Crop Types etc.
- **Weather Conditions**: Temperature, rainfall, etc.
- **Crop Management Practices**: Fertilizer use, irrigation, etc.

## Technologies Used
- **Python**: Core language for model development.
- **Pandas**: Data manipulation.
- **NumPy**: Numerical computations.
- **Scikit-learn**: Building and evaluating the regression model.
- **Matplotlib/Seaborn**: Data visualization.
- **Jupyter Notebook**: Interactive development environment.
- **Azure**: Cloud platform for hosting the application.
- **GitHub Actions**: For CI/CD workflows.

## Installation and Setup
### Local Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/agriculture-yield-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd agriculture-yield-prediction
    ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

### Deployment on Azure
The application is deployed on Azure and can be accessed through the provided link. No additional setup is required for usage.

## CI/CD Pipeline
The project utilizes GitHub Actions for automated CI/CD:
- **Continuous Integration**: Runs unit tests and linting on each push.
- **Continuous Deployment**: Automatically deploys to Azure upon successful test completion.

For more details, refer to the GitHub Actions workflows in the [.github/workflows](.github/workflows) directory.

## Usage
1. Access the live application through the provided Azure link.
2. Enter the required input data through the web interface.
3. Receive yield predictions instantly.

## Results
Key performance metrics for the model:
- Root Mean Squared Error: 0.5041
- Mean Absolute Error: 0.4024
- R2 Score: 0.9117

## Future Work
- **Model Enhancements**: Explore additional features and improve accuracy.
- **UI Improvements**: Enhance the web interface for better user experience.
- **Broader Adaptation**: Extend model capabilities for various crops and regions.

## Contributing
As this is a solo project, contributions are not currently op
