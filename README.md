# 🚢 Kaggle Competition: Titanic - Machine Learning from Disaster

Repositorio con mis experimentos y notebooks para la clásica competencia de Kaggle **Titanic: Machine Learning from Disaster**.  
El objetivo es predecir qué pasajeros sobrevivieron al hundimiento del Titanic usando distintos algoritmos de Machine Learning.

## 🧪 Resultados hasta ahora
- **Notebook:** `EPA_TITANIC_KNN.ipynb`  
- **Modelo:** KNN con GridSearchCV (mejor k=11, Manhattan distance)  
- **Score en Kaggle (Accuracy):** `0.76315`  

## 🔜 Próximos pasos
- Crear nuevas features (FamilySize, IsAlone, Title, CabinKnown).  
- Probar modelos adicionales (Logistic Regression, Random Forest, XGBoost).  
- Comparar resultados y registrar scores en nuevos notebooks.  

## 📊 Historial de experimentos

| Notebook                   | Modelo | Score   | Notas                       |
|----------------------------|--------|---------|-----------------------------|
| EPA_TITANIC_KNN_V2.ipynb   | KNN    | 0.76315 | GridSearch (k=11, p=1, uniform). Baseline sólido |


---

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
│   └── EPA_TITANIC_KNN.ipynb  # baseline con KNN + GridSearch
│
├── .gitignore                 # ignora checkpoints, submissions, modelos pesados
├── LICENSE                    # licencia del proyecto (opcional)
└── README.md                  # este archivo
