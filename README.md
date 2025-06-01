#  Smart Agriculture System – Disease, Yield & Soil Classification
This comprehensive AI-driven project tackles three key challenges in agriculture using deep learning and machine learning:

🦠 Paddy Leaf Disease Classification
Utilizes a Kaggle dataset with 4 classes:
Bacterial Leaf Blight, Brown Spot, Leaf Smut, and Blast.

Models used: VGG19, DenseNet201, InceptionResNetV2, MobileNetV2, ResNet50V2, Xception, and EfficientNetV2B4.

Achieved 97–99% accuracy using fine-tuned transfer learning with TensorFlow.

📈 Crop Yield Prediction
Predicts yield based on features like:
State, District, Crop, Crop_Year, Season, Area, Production.

MODELS:

STABiLSTM-BiLSTM: A stacked attention-based BiLSTM followed by BiLSTM layers to capture both spatial and temporal dependencies in tabular crop data.

STABiLSTM-GRU: Similar architecture replacing the second BiLSTM with GRU layers for better efficiency on longer sequences.

CatBoost Regressor, fine-tuned using:

Bayesian Optimization (Hyperopt, Optuna)

GridSearchCV and RandomizedSearchCV

🧪 Soil Type Image Classification
Classifies soil into 4 types:
Alluvial, Clay, Red, and Black soils.

Uses CNN models trained in TensorFlow with custom preprocessing.

📦 Tech Stack:

Python, TensorFlow, Keras, PyTorch

CatBoost, Optuna, Hyperopt, Scikit-learn

Pandas, NumPy, Matplotlib, Seaborn

🔬 A powerful multi-task platform for smart agriculture: identifying diseases, predicting yield, and analyzing soil—all in one solution.
