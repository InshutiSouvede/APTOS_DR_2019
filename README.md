# APTOS 2019 Diabetic Retinopathy Classification

Dataset: APTOS 2019 Blindness Detection (Extended with Validation Set)
Source: https://www.kaggle.com/datasets/mariaherrerot/aptos2019

Dataset Description:
- Training images: train_images/ with train.csv
- Validation images: valid_images/ with valid.csv (pre-split!)
- Test images: test_images/ with test.csv
- 5 classes: 0 (No DR), 1 (Mild), 2 (Moderate), 3 (Severe), 4 (Proliferative DR)
- Images captured under varying lighting conditions in rural India
- Significant class imbalance present

Analysis Objectives:
1. Compare Traditional ML (Random Forest) vs Deep Learning (CNN + Transfer Learning)
2. Conduct 3 systematic experiments per model (9 total experiments)
3. Demonstrate comprehensive preprocessing and feature engineering
4. Provide deep analysis: learning curves, confusion matrices, bias-variance analysis
5. Document all hyperparameter choices with clear justification

Model Selection:
- Traditional ML: Random Forest (chosen for feature importance interpretability)
- Deep Learning: Custom CNN (demonstrate architecture design skills)
- Transfer Learning: ResNet50 (proven performance on medical images)
