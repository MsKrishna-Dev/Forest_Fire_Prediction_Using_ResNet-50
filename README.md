# Forest Fire Prediction Using ResNet-50
This project focuses on predicting forest fire occurrences using deep learning with the ResNet-50 architecture. The model utilizes remote sensing data such as NDVI (Normalized Difference Vegetation Index), Land Surface Temperature (LST), and burned area features to classify fire and no-fire events.

The work is based on the research paper titled **“Forest Fire Prediction through Deep Learning using ResNet-50 Model”**, published in the *Grenze International Journal of Engineering and Technology* (January Issue, Scopus Indexed).

## Dataset
The dataset consists of numerical remote sensing indicators related to vegetation health, temperature, and fire-affected area.  
It is placed in the `WildFires_DataSet` file.

## Project Structure
```
├── WildFires_DataSet
├── notebook.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- ResNet-50
- Jupyter Notebook

## How to Run
1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Open and run the Jupyter Notebook:
   jupyter notebook notebook.ipynb

## Notes
- This repository is intended for academic and research purposes.
- The dataset used is publicly available and included for reference.
