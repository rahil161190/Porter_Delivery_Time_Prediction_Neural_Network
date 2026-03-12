# Porter Delivery Time Prediction

## Situation  
Porter, India’s largest intra-city logistics marketplace, needed a way to estimate delivery times more accurately to improve customer satisfaction and optimize driver allocation.

## Task  
Build a machine learning pipeline to predict delivery times using historical order data, including features like order size, store category, dashers on shift, and driving duration.

## Action  
- Cleaned and engineered features from 175k+ delivery records.  
- Applied preprocessing with `ColumnTransformer` (scaling, one-hot encoding).  
- Designed and tuned a neural network using Keras Tuner with dropout, batch normalization, and early stopping.  
- Integrated **LIME** for local interpretability, explaining feature contributions to individual predictions.

## Result  
Achieved strong predictive accuracy (MAE ~ few minutes) and generated interpretable insights.  
LIME explanations highlighted operational drivers (day-of-week, store category, outstanding orders), making the model recruiter-ready and business-aligned.
