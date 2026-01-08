# Flight Price Prediction with PyTorch

Flight Price Prediction with PyTorch is an end-to-end machine learning project that predicts airline ticket prices using a custom neural network implemented from scratch in PyTorch. The dataset used in this project was obtained from Kaggle.

- Used a ready-to-use flight booking dataset from Kaggle and prepared it for modeling.
- Cleaned and normalized data, handling missing values and inconsistent formats.
- Performed feature engineering to derive useful signals such as trip duration, departure/arrival times, airline and route information, and other derived features.
- Encoded categorical variables and scaled numerical features for model compatibility.
- Implemented custom PyTorch DataLoaders and data transforms to streamline training and evaluation.
- Designed and trained a feedforward neural network with configurable depth/width and regularization (dropout, batch normalization).
- Trained the model in a supervised regression setup and validated performance with training/validation splits.
- Evaluated results using RMSE and MAE, and produced visualizations for prediction vs actual, residuals, and training history.

Results and outputs
- Trained model checkpoints and example predictions.
- Evaluation metrics (RMSE, MAE) computed on validation data.
- Visualizations illustrating model performance and residual behavior.


Notes
- The project focuses on a clear, modular pipeline: raw data (Kaggle) → preprocessing/feature engineering → model → evaluation → visualization.
- The code is structured to be extensible: you can experiment with different architectures, embeddings for categorical features, or additional time-based features.


License
MIT License

Copyright (c) 2026 AbdullohML

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
