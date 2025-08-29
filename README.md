# 🚢 Kaggle Competition: Titanic - Machine Learning from Disaster

Repositorio con mis experimentos y notebooks para la clásica competencia de Kaggle **Titanic: Machine Learning from Disaster**.  
El objetivo es predecir qué pasajeros sobrevivieron al hundimiento del Titanic usando distintos algoritmos de Machine Learning.

## 🧪 Resultados hasta ahora
- **Notebook:** `EPA_TITANIC_KNN_FE_V1.ipynb`  
- **Modelo:** KNN con Feature Engineering + GridSearchCV (mejor k=13, Manhattan distance)  
- **Score en Kaggle (Accuracy):** `0.75598`  

## 🔜 Próximos pasos
- Probar modelos basados en árboles (Random Forest, Gradient Boosting, XGBoost, LightGBM).  
- Ajustar el Feature Engineering para mejorar la generalización.  
- Comparar resultados y registrar scores en nuevos notebooks.  

## 📊 Historial de experimentos

| Notebook                    | Modelo | Score   | Notas                                           |
|-----------------------------|--------|---------|-------------------------------------------------|
| EPA_TITANIC_KNN_V2.ipynb    | KNN    | 0.76315 | GridSearch (k=11, p=1, uniform). Baseline sólido|
| EPA_TITANIC_KNN_FE_V1.ipynb | KNN FE | 0.75598 | Feature Engineering + GridSearch (k=13, p=1). CV=0.8249 |

📌 *Este repo sirve como bitácora de aprendizaje en Kaggle, manteniendo cada notebook/versionado como un experimento independiente.*

## 📂 Estructura del repositorio

```text
kaggle-titanic/
├── data/                      # datasets oficiales (train, test, sample submission)
│   ├── train.csv
│   ├── test.csv
│   ├── gender_submission.csv
│   └── README.md
│
├── notebooks/                 # notebooks de experimentos
│   ├── EPA_TITANIC_KNN_V2.ipynb
│   └── EPA_TITANIC_KNN_FE_V1.ipynb
│
├── .gitignore                 # ignora checkpoints, submissions, modelos pesados
├── LICENSE                    # licencia del proyecto (opcional)
└── README.md                  # este archivo
