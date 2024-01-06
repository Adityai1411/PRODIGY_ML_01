# linear-regression-house-price-prediction
This repository implements a linear regression model to predict the prices of houses based on three key features: square footage, number of bedrooms, and number of bathrooms.

This project embarks on the journey of predicting house prices using the powerful XGBoost regression algorithm. It commences by meticulously preparing the housing data, ensuring its readiness for modeling. Missing values are addressed thoughtfully, with numerical features filled using mean or mode, and categorical features handled through one-hot encoding. The dataset is then gracefully split into training and validation sets, laying the foundation for model development.

Next, the XGBoost regression model takes center stage.It's configured with the objective of minimizing squared error, ensuring its predictions align closely with actual house prices. The model diligently trains on the prepared training data, meticulously learning the intricate relationships between various house features and their corresponding prices.

Upon completion of training, the model confidently steps into the realm of prediction.It's presented with the validation set, tasked with estimating house prices unseen during training. The resulting predictions are carefully captured and prepared for submission.

The project culminates in the creation of a submission file, containing the predicted house prices for the validation set. This file stands as a testament to the model's learning and serves as a potential tool for real-world house price estimation.
