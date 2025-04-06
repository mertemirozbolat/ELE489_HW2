# Decision Tree Classification on Dataset

## Project Description
This project applies a **Decision Tree** classifier model on a dataset. The model splits the data into training and test sets and is trained with various parameters. Additionally, the model's performance is evaluated using a **Confusion Matrix** and a **Classification Report**. Different hyperparameters, such as the **entropy** and **gini** criteria, as well as tree depth, are experimented with throughout the project. The dataset typically consists of feature columns (variance, skewness, curtosis, entropy) and a class label indicating whether a sample is "Fake" or "Authentic".

## Libraries Used
The following libraries are used in this project:

- `pandas`: Data analysis and manipulation.
- `seaborn`: Visualization and plotting.
- `matplotlib`: Plotting and graphing.
- `scikit-learn`: Machine learning modeling and evaluation.
- `google.colab`: Used for file upload functionality in Colab.

## Installation
The project can be run directly in **Google Colab**. Since the required libraries are already pre-installed in Colab, no additional installation is required. However, if running locally, you can install the necessary libraries using the following command:

`bash
pip install pandas seaborn matplotlib scikit-learn`

## Dataset
This project works with a user-uploaded .txt file. The file typically contains the following columns:

Variance: Variance feature.
Skewness: Skewness feature.
Curtosis: Curtosis feature.
Entropy: Entropy feature.
Class: The class label ("Fake" or "Authentic").

## Results
The Decision Tree model is tested with different criteria (e.g., entropy and gini) and tree depths (max_depth).

The model's classification performance is analyzed using classification reports and confusion matrices.

Feature importance is visualized to highlight which features are most influential in the model.
