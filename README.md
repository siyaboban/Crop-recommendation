**Developing a Transformer-Based Crop Recommendation System for Precision
Agriculture**

Welcome to the **Transformer-Based Crop Recommendation System for
Precision Agriculture** project! This repository contains code and
resources for developing and comparing various machine learning models,
including transformer-based models, traditional machine learning
algorithms, and boosting algorithms, to recommend suitable crops based
on specific soil and climatic conditions.

**Overview**

The goal of this project is to enhance precision agriculture by
providing farmers with accurate crop recommendations tailored to their
local environmental conditions. By leveraging advanced machine learning
techniques, we aim to optimize crop selection processes, thereby
increasing yield, improving resource utilization, and promoting
sustainable farming practices.

**Objectives**

-   **Data Collection and Preprocessing**

    -   Gather a comprehensive dataset containing soil nutrient levels,
        climatic conditions, and corresponding crop types.

    -   Perform thorough data preprocessing to ensure quality and
        suitability for model training, including handling missing
        values and encoding categorical variables.

-   **Model Development**

    -   Develop and train traditional machine learning models such as
        Decision Trees, Random Forests, Support Vector Machines (SVM),
        and K-Nearest Neighbors (KNN).

    -   Develop and train boosting algorithms including XGBoost,
        LightGBM, and CatBoost.

    -   Develop and fine-tune a transformer-based model tailored for
        crop recommendation tasks.

-   **Performance Evaluation**

    -   Evaluate and compare the performance of all models using metrics
        such as accuracy, precision, recall, and F1-score.

    -   Analyze computational efficiency by measuring training and
        inference times.

    -   Visualize results and correlations within the data to provide
        intuitive insights.

**Features**

-   **Comprehensive Data Analysis**

    -   Detailed exploratory data analysis (EDA) including
        visualizations like histograms, violin plots, box plots, and
        heatmaps to understand data distributions and feature
        correlations.

-   **Multiple Machine Learning Models**

    -   Implementation of various machine learning algorithms allowing
        for performance comparison and selection of the most suitable
        model for crop recommendation.

-   **Hyperparameter Optimization**

    -   Utilization of techniques like Randomized Search
        Cross-Validation for optimal hyperparameter tuning across
        different models.

-   **Performance Metrics and Evaluation**

    -   Comprehensive evaluation using standard classification metrics
        and confusion matrices to assess and compare model performances.

-   **Modular and Extensible Codebase**

    -   Well-structured and documented code allowing for easy
        understanding, maintenance, and extension by other developers
        and researchers.

**Installation**

Follow the steps below to set up the project locally:

**Prerequisites**

-   **Python 3.7 or higher**

-   **Git**

**Clone the Repository**

bash

Copy code

git clone
https://github.com/yourusername/transformer-crop-recommendation.git

cd transformer-crop-recommendation

**Create a Virtual Environment**

It\'s recommended to use a virtual environment to manage dependencies.

bash

python -m venv env

Activate the virtual environment:

-   **On Windows:**

> bash
>
>
> env\\Scripts\\activate

-   **On macOS and Linux:**

> bash
>
> Copy code
>
> source env/bin/activate

**Install Dependencies**



**Download Dataset**

The dataset used in this project is available on Kaggle. Follow these
steps to download it:

1.  **Download the Dataset**

    -   Visit the Crop Recommendation Dataset on Kaggle.

    -   Download the dataset file (crop_recommendation.csv).

2.  **Place Dataset in the Data Directory**

    -   Create a directory named data in the project root if it doesn\'t
        exist:

> bash
>
> Copy code
>
> mkdir data

-   Move the downloaded crop_recommendation.csv file into the data
    directory.

**Usage**

Follow the instructions below to run the models and reproduce the
results:

**1. Data Preprocessing**

Run the data preprocessing script to clean and prepare the data for
model training:



**2. Training Traditional Machine Learning Models**

Train and evaluate traditional machine learning models:



**3. Training Boosting Models**

Train and evaluate boosting algorithms:


**4. Training Transformer Model**

Train and evaluate the transformer-based model:

bash



Generate comparative analysis and visualizations of all models:



**6. Results and Outputs**

All results, including trained models, performance metrics, and
visualizations, will be saved in the results directory for further
inspection and analysis.

**Data**

**Dataset Description**

The **Crop Recommendation Dataset** provides comprehensive information
necessary for building an effective crop recommendation system. The
dataset includes:

-   **Soil Features**

    -   Nitrogen content (N)

    -   Phosphorus content (P)

    -   Potassium content (K)

    -   pH level (ph)

    -   Organic carbon (oc)

-   **Climatic Conditions**

    -   Temperature (temperature)

    -   Humidity (humidity)

    -   Rainfall (rainfall)

-   **Target Variable**

    -   Recommended crop type (label)

**Data Preprocessing Steps**

-   **Handling Missing Values**

    -   Checked and confirmed that there are no missing values in the
        dataset.

-   **Handling Duplicates**

    -   Removed duplicate entries to ensure data integrity.

-   **Feature Scaling**

    -   Applied standard scaling to numerical features to normalize data
        distribution.

-   **Encoding Categorical Variables**

    -   Encoded target variable using label encoding for model
        compatibility.

-   **Train-Test Split**

    -   Split the dataset into training, validation, and testing sets to
        evaluate model performance effectively.

**Exploratory Data Analysis**

Performed extensive EDA to understand data distributions and
relationships between features:

-   **Distribution Plots**

    -   Histograms, violin plots, and box plots for each feature.

-   **Correlation Analysis**

    -   Heatmaps to visualize correlations between different features.

**Contributing**

We welcome contributions from the community to enhance this project.
Follow the guidelines below to contribute:

**Steps to Contribute**

1.  **Fork the Repository**

    -   Click the \'Fork\' button on the top right to create a copy of
        this repository on your GitHub account.

2.  **Clone Your Fork**

> bash
>
> Copy code
>
> git clone
> https://github.com/yourusername/transformer-crop-recommendation.git

3.  **Create a New Branch**

> bash
>
> Copy code
>
> git checkout -b feature/your-feature-name

4.  **Make Your Changes**

    -   Implement your feature or fix bugs.

5.  **Commit and Push**

> bash
>
> Copy code
>
> git add .
>
> git commit -m \"Add your commit message\"
>
> git push origin feature/your-feature-name

6.  **Create a Pull Request**

    -   Go to the original repository and click on \'New Pull Request\'.

**Contribution Guidelines**

-   Follow the existing code style and structure.

-   Write clear and concise commit messages.

-   Update documentation and comments where necessary.

-   Ensure that your code passes all tests and checks before submitting.

-   Be respectful and collaborative in code reviews and discussions.
