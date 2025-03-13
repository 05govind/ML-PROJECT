# ML-PROJECT
## Dataset

The dataset comprises hyperspectral imaging data representing corn samples, with spectral bands serving as features and vomitoxin concentration as the target variable.

Data was preprocessed to ensure proper format for CNN training.

## Preprocessing Steps

Missing values handled with appropriate imputation techniques.

Data normalized to enhance model performance.

Dataset split into 80% training and 20% testing for evaluation.

## Dimensionality Reduction

Principal Component Analysis (PCA) was applied to reduce spectral data complexity while retaining key features.

## Model Selection and Training

A 1D CNN model was designed with the following layers:

Two convolutional layers with ReLU activation and max pooling.

Flatten layer for feature extraction.

Fully connected (dense) layer for final prediction.

Hyperparameter tuning was performed using GridSearchCV to optimize parameters such as:

Number of filters

Kernel size

Dense layer units

Batch size and epochs

## Evaluation Metrics

Model performance was assessed using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

A scatter plot comparing actual and predicted values was generated for visual assessment.
