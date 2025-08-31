# 🚢 Kaggle Competition: Titanic - Machine Learning from Disaster

Repositorio con mis experimentos y notebooks para la clásica competencia de Kaggle **Titanic: Machine Learning from Disaster**.  
El objetivo es predecir qué pasajeros sobrevivieron al hundimiento del Titanic usando distintos algoritmos de Machine Learning.

## 📊 Historial de experimentos

| Notebook                       | Modelo        | CV mean (std)   | Kaggle Score | Notas |
|--------------------------------|---------------|-----------------|--------------|-------|
| EPA_TITANIC_KNN_V2.ipynb       | KNN           | ~0.811          | 0.76315      | Baseline con GridSearch |
| EPA_TITANIC_KNN_FE_V1.ipynb    | KNN + FE      | ~0.81           | 0.75598      | Incluye ingeniería de atributos |
| EPA_TITANIC_LOGREG_V1.ipynb    | LogReg        | 0.8249 (0.0091) | 0.77272      | Estable, baseline fuerte |
| EPA_TITANIC_LOGREG_V2.ipynb    | LogReg        | 0.8272          | 0.77033      | GridSearch en C y solver |
| EPA_TITANIC_SGD_V1.ipynb       | SGDClassifier | 0.8215          | 0.77511      | loss=hinge, alpha=0.01 |
| EPA_TITANIC_LINSVC_V1.ipynb    | LinearSVC     | 0.8294 (0.0097) | 0.77272      | Baseline sin GridSearch |
| **EPA_TITANIC_LINSVC_V2.ipynb**| **LinearSVC** | **0.8260 (0.0123)** | **0.77751** | Mejor resultado hasta ahora |


📌 *Este repo sirve como bitácora de aprendizaje en Kaggle, manteniendo cada notebook/versionado como un experimento independiente.*
