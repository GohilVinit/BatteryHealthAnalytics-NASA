# Instructions for Running the Notebook

### Setup Requirements:
```bash
pip install pandas numpy matplotlib scikit-learn seaborn
```

### To Run with Real Data:
1. Download the NASA battery dataset from: https://www.kaaale.com/datasets/patrickfleith/nasa-battery-dataset/data
2. Extract the files to your working directory
3. Ensure `metadata.csv` is in the same folder as this notebook
4. Run all cells in sequence

### Expected Outputs:
- **Task A**: 3D EIS impedance plot showing aging effects
- **Task B**: Incremental capacity analysis with 3D peak evolution
- **Task C**: ML model achieving R² > 0.85 for capacity prediction

### Files Generated:
- `nasa_battery_ml_model.pkl` - Trained model
- `training_dataset.csv` - Training data
- `capacity_predictions.csv` - Sample predictions
- `analysis_summary.txt` - Summary report
