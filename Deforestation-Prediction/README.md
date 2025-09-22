# Deforestation Prediction Using Transfer Learning & XGBoost

## About
This project aims to predict deforestation in Indonesia using **satellite imagery** and **numerical data**. 
- Image classification is performed with **EfficientNet-B0** (transfer learning).  
- Predictive modeling on numerical data is done using **XGBoost**.  
The project combines **Computer Vision** and **Machine Learning** to provide actionable insights on forest loss.  

## Dataset
- **Satellite images:** Available on [Kaggle](https://www.kaggle.com/username/dataset-name)  
- **Numeric data:** Global Forest Watch (forest loss per province, 2002–2024)  

## Methodology
### Image Classification
- Preprocessing: resize images, data augmentation (rotation, horizontal & vertical flips)  
- Model: EfficientNet-B0 as feature extractor  
- Metrics: Accuracy, Precision, Recall, F1 Score  

### Numeric Prediction
- Model: XGBoost  
- Metrics: MAE, MSE, RMSE, R² Score  
- Visualization: bar charts and distribution maps of deforestation  

## Recognition
- **Top 10 SDG Summit UB Competition 2025**

## How to Run
1. Clone this repository  
2. Install dependencies: `pip install -r requirements.txt`  
3. Download datasets from Kaggle and place in `data/` folder  
4. Open and run the notebook: `Deforestation_Prediction.ipynb`  

## Visualization
- Include images for confusion matrix, bar charts, and maps in `images/` folder.
