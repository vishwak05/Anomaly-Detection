# Anomaly Detection using DBSCAN

## Overview
This project demonstrates the implementation of anomaly detection using the DBSCAN (Density-Based Spatial Clustering of Applications with Noise) algorithm. Anomaly detection is crucial for identifying rare events or observations that deviate significantly from the normal patterns in data.

## Types of Anomalies
As described in the original documentation (```markdown:README.md startLine: 2 endLine: 7```), there are three main categories of anomalies:

1. **Point Anomaly**: Individual data points that significantly deviate from the normal pattern
2. **Contextual Anomaly**: Observations that are anomalous in a specific context
3. **Collective Anomaly**: Groups of related data instances that are anomalous

## Project Features
- Synthetic dataset generation for demonstration
- Implementation of DBSCAN clustering algorithm
- Visualization of normal and anomalous data points
- Identification and marking of anomalies

## Technologies Used
- Python 3.11.5
- NumPy
- Matplotlib
- Scikit-learn

## Installation
'''
pip install numpy matplotlib scikit-learn
'''


## Usage
The project is implemented in a Jupyter notebook format. To run the analysis:

1. Clone this repository
2. Install the required dependencies
3. Open `Anomaly Detection.ipynb` in Jupyter Notebook or JupyterLab
4. Run all cells sequentially

## Implementation Details
The implementation follows these key steps:

1. Data Generation: Creates synthetic data using `make_blobs`
2. Data Preparation: Combines normal data with intentionally introduced anomalies
3. DBSCAN Application: Uses DBSCAN algorithm with parameters:
   - eps = 1
   - min_samples = 41
4. Visualization: Plots the results with normal points in blue and anomalies in red

## Results
The project provides:
- Visual representation of the dataset
- Clear identification of anomalous points
- Detailed coordinates of identified anomalies

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Contact
Please open an issue in the repository for any questions or concerns.