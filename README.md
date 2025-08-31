# 🚢 Kaggle Competition: Titanic - Machine Learning from Disaster

Repositorio con mis experimentos y notebooks para la clásica competencia de Kaggle **Titanic: Machine Learning from Disaster**.  
El objetivo es predecir qué pasajeros sobrevivieron al hundimiento del Titanic usando distintos algoritmos de Machine Learning.

## 📊 Historial de experimentos

| Notebook                    | Modelo        | Score   | Notas                                                    |
|------------------------------|---------------|---------|----------------------------------------------------------|
| EPA_TITANIC_KNN_V2.ipynb     | KNN           | 0.76315 | GridSearch (k=11, p=1, uniform). Baseline sólido         |
| EPA_TITANIC_KNN_FE_V1.ipynb  | KNN + FE      | 0.75598 | Feature Engineering + GridSearch (k=13, p=1)             |
| EPA_TITANIC_LOGREG_V1.ipynb  | LogReg        | 0.77272 | FE + Preproc. CV=0.8249 (std 0.0091)                     |
| EPA_TITANIC_LOGREG_V2.ipynb  | LogReg        | 0.77033 | GridSearchCV (C≈7.74, l2, lbfgs). CV=0.8272              |
| EPA_TITANIC_SGD_V1.ipynb     | SGDClassifier | 0.77511 | GridSearchCV (hinge, l2, alpha=0.01). Mejor hasta ahora  |
| EPA_TITANIC_LINSVC_V1.ipynb  | LinearSVC     | 0.77272 | Baseline LinearSVC (C=1, l2, squared_hinge). Empatado con LogReg V1 |

📌 *Este repo sirve como bitácora de aprendizaje en Kaggle, manteniendo cada notebook/versionado como un experimento independiente.*
