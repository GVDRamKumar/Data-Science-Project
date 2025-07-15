# Network Intrusion Detection using Machine Learning

This project implements a machine learning-based intrusion detection system using the UNSW-NB15 dataset. It evaluates several classification models to detect anomalies in network traffic and identify potential intrusions.

## 📁 Project Structure

- `Final_code.ipynb`: Jupyter Notebook containing full EDA, preprocessing, model training, and evaluation.
- `UNSW_NB15_training-set.csv` and `UNSW_NB15_testing-set.csv`: Raw datasets used for the project.
- `NID_Presentation_Bala.pptx`: Presentation summarizing project results and visuals.

## 🔍 Objective

To identify network intrusions using supervised ML models by:
- Preprocessing network traffic data
- Training classifiers
- Comparing performance using accuracy, precision, recall, F1 score, and AUC

## 🧪 Models Used

- Logistic Regression
- Random Forest
- AdaBoost
- Gaussian Naive Bayes
- K-Nearest Neighbors (KNN)
- Multi-Layer Perceptron (MLP)

## 📊 Evaluation Metrics

Each model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve and AUC

## 🔮 Results

Random Forest and MLP classifiers showed the best overall performance with high accuracy and AUC values.

## ⚙️ Requirements

- Python 3.8+
- pandas, numpy, seaborn, matplotlib, scikit-learn, plotly

Install using:

```bash
pip install -r requirements.txt
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Balaji Manjulamma Sriramareddy**  
MSc Data Science | University of Hertfordshire  
