# 📂 Carpeta `data/`

Esta carpeta contiene los **archivos originales de la competencia Kaggle [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)**.  
Se incluyen para propósitos de **reproducibilidad local** y para mantener la estructura clara del proyecto.

## Archivos

- **train.csv**  
  Contiene 891 registros de pasajeros, con la variable objetivo `Survived` (0 = no sobrevivió, 1 = sobrevivió).  
  Incluye variables como `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`.

- **test.csv**  
  Contiene 418 registros de pasajeros, sin la columna `Survived`.  
  El objetivo del modelo es predecir esta variable para cada fila.

- **gender_submission.csv**  
  Archivo de ejemplo provisto por Kaggle con la estructura de **submission** correcta (`PassengerId`, `Survived`).  
  Sirve como plantilla para verificar el formato antes de subir predicciones.

## Notas importantes
- ⚠️ En Kaggle, estos archivos están disponibles automáticamente en `/kaggle/input/titanic/`.  
- ✅ Se versionan aquí solo los **archivos pequeños** provistos por la competición (≈ 60 KB).  
- 🚫 **No** se deben versionar datasets adicionales o archivos de submission generados (están en `.gitignore`).  
