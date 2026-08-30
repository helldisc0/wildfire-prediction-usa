# US Wildfire Incidence Prediction

## Overview
Built a machine learning model to forecast monthly wildfire 
probability across the contiguous United States using 
historical fire records, with the goal of supporting 
early warning and resource allocation decisions.

## Key Findings
- Trained on 1.88 million fire records spanning multiple 
  decades
- Achieved 68.8% prediction accuracy using Random Forest
- Cyclical month features (sin/cos encoding) improved 
  model performance by capturing seasonal fire patterns
- Spatial analysis revealed distinct regional fire 
  frequency patterns across the US

## Predictive Model
- **Algorithm:** Random Forest Classifier
- **Accuracy:** 68.8%
- **Features:** Historical fire records, state-level 
  predictors, cyclical month encoding (sin/cos)
- **Target:** Next-month wildfire probability per 
  1° x 1° grid cell

## Visualizations
- Geographic heatmaps of fire frequency distribution 
  across 1° x 1° grid cells
- Spatial severity maps by region
- Seasonal trend analysis

## Tools Used
- Python (pandas, matplotlib, scikit-learn)
- Google Colab

## Data Source
[US Wildfire Records Dataset] ← add your source link

## Methodology Note
Model relies solely on historical fire records without 
incorporating real-time weather, drought indices, or 
vegetation data — factors that would likely improve 
predictive accuracy in a production setting.

## Project Preview
Download `.html` file from the repository.
