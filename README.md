# Optimization of Artificial Neural Networks for Diabetes Prediction

This project aims to optimize the use of artificial neural networks (ANN) for diabetes prediction using the **PIMA Indians Diabetes** dataset. Compared to traditional models like Random Forest, this approach offers significant improvements in accuracy and reduction of false negatives.

## Introduction
Diabetes is a chronic disease that poses a significant challenge to healthcare systems worldwide. This project proposes an artificial neural network (ANN) model to improve the accuracy of diabetes prediction and reduce critical errors such as false negatives.

The study uses the **PIMA Indians Diabetes** dataset, which is widely recognized in medical prediction studies, to develop a robust model capable of achieving at least 80% test accuracy.

## Contributions
This work successfully designed a new ANN model that improved test accuracy by up to 6.5% compared to a baseline Random Forest model. Additionally, extensive experimentation provided valuable insights into:
- Hyperparameter tuning (layers, neurons, epochs).
- Data preprocessing techniques (scaling, regularization).
- Early stopping mechanisms to prevent overfitting.

These optimizations not only improved the model’s accuracy but also significantly reduced false negatives.

## Methodology

### Dataset Description
The **PIMA Indians Diabetes** dataset contains 768 samples and 9 features, including:
- **Pregnancies**: Number of previous pregnancies.
- **Glucose**: Glucose concentration after a test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skinfold thickness (mm).
- **Insulin**: Insulin levels (milliunits per gram).
- **BMI**: Body Mass Index.
- **DiabetesPedigreeFunction**: Diabetes likelihood based on family history.
- **Age**: Participant’s age.
- **Outcome**: Target variable (1 = diabetic, 0 = non-diabetic).


### Experimental Design
Experiments were conducted incrementally, starting with a simple ANN model and gradually incorporating:
- Regularization techniques.
- Data scaling.
- Hyperparameter optimization.

Performance was evaluated on training, validation, and test datasets using metrics such as accuracy, precision, recall, and confusion matrices.

## Results
The final ANN model achieved:
- **Test accuracy**: 83.77%
- **Precision**: 80%
- **Recall**: 72.73%
- **False negatives**: Reduced by over 20% compared to the Random Forest baseline.

This demonstrates that ANN models are effective for structured data analysis and outperform traditional methods like Random Forest in reducing critical errors.

## Conclusions
Key takeaways from this project include:
1. Scaling data and applying L2 regularization significantly enhance model performance.
2. Early stopping prevents overfitting while maintaining accuracy.
3. Reducing false negatives is crucial for clinical applications, where missed diagnoses can have severe consequences.

Future research should focus on fine-tuning hyperparameters and exploring external datasets to further improve model generalization.
