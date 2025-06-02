# Airline Passenger Satisfaction Modeling

This project investigates factors that predict airline passenger satisfaction using machine learning techniques. It was developed as part of a graduate-level data science course (ANA500) and demonstrates end-to-end modeling, evaluation, and interpretation.

## ✈️ Project Objective

To identify which flight-related and customer service factors are most predictive of passenger satisfaction, and to compare the performance of various classification models in making this prediction.

## 📁 Contents

- `AirlineSatisfaction.ipynb` — Main Jupyter notebook containing all code and analysis
- `AirlineSatisfaction_Transformed.csv` — Preprocessed dataset used for modeling (transformed from the raw dataset)
- `airline.csv` — Original raw dataset (provided in the ANA500 course materials)
- `Flight Satisfaction Model Comparisons Excel Helper.xlsx` — Supplementary Excel file used for creating some of the model comparison table visuals for the presentation
- `Presentation PDF Export.pdf` — Final slide deck in PDF format to retain formatting consistency
- `Presentation.pptx` — Final slide deck in native PowerPoint .pptx format (editable file, but formatting may not render properly accross user environments, so use PDF for viewing)

## 🧠 Models Used

- Logistic Regression (including full and reduced versions)
- Support Vector Machine (LinearSVC)
- Deep Learning Classification (Recurrent Neural Network using Keras & TensorFlow)

## 🧪 Evaluation Metrics

- **Accuracy**: Proportion of correct predictions
- **Precision**: How many predicted positives were actually positive
- **Recall**: How many actual positives were correctly predicted
- **F1 Score**: Harmonic mean of Precision and Recall

## 💡 Key Takeaways

- The deep learning recursive neural network model outperformed others in accuracy and F1 score, but offers less interpretability.
- While initial hypotheses emphasized certain predictors (Class, On-board service, etc.), the results suggested that satisfaction is influenced by a broader combination of factors.
- Interpretability trade-offs are key when choosing between models like logistic regression, SVM, and deep learning.

## 🔧 Setup Notes

To run the Jupyter notebook:
- Python
- Required packages are found in the import statements

## 📬 Contact

For questions or follow-up, reach out via the Issues tab or contact the project author directly.
