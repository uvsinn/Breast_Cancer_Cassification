# Breast Cancer Classification

This project aims to develop a breast cancer classification system using *Logistic Regression* technique. The goal is to accurately classify breast tumors as either malignant or benign based on various features extracted from medical images and patient data.

## Introduction

Breast cancer is a critical health concern worldwide, and early detection plays a crucial role in improving survival rates. Machine learning techniques offer promising avenues for developing accurate and efficient classification systems to assist medical professionals in diagnosing breast cancer.

This project utilizes a dataset consisting of various features extracted from breast tumor images, such as texture, shape, and margin properties. By training a machine learning model on this dataset, we aim to create a classification system that can accurately predict whether a tumor is malignant (cancerous) or benign (non-cancerous).

## Dataset

The dataset used for this project can be found [here](https://github.com/uvsinn/Breast_Cancer_Cassification/dataset.csv). It contains the following columns:

- `id`: Unique identifier for each sample
- `radius_mean`: Mean of distances from center to points on the perimeter
- `texture_mean`: Standard deviation of gray-scale values
- `perimeter_mean`: Perimeter size of the tumor
- `area_mean`: Area size of the tumor
- `smoothness_mean`: Local variation in radius lengths
- `compactness_mean`: Measure of perimeter^2 / area - 1.0
- `concavity_mean`: Severity of concave portions of the contour
- `symmetry_mean`: Symmetry of the tumor
- `fractal_dimension_mean`: "Coastline approximation" - 1
- 
## Getting Started

To run this project locally, follow these steps:

1. Clone the repository: git clone https://github.com/uvsinn/Breast_Cancer_Classification.git
   
2. Install the required dependencies: pip install -r requirements.txt

3. Navigate to the `notebooks/` directory
   
4. Open the Jupyter notebooks to explore, preprocess, train, and evaluate the model.

## Model Evaluation

The model's performance is evaluated using various evaluation metrics, such as accuracy, precision, recall, and F1 score. The evaluation results are displayed and discussed in the project notebooks.

## Conclusion

Breast Cancer Classification is an important task in the field of medical imaging analysis. A reliable and accurate classification system can assist healthcare professionals in making informed decisions. This project aims to contribute to the development of such systems.

For more details and in-depth analysis, please refer to the Jupyter notebooks in this repository.
   
## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contact

If you have any questions or inquiries, feel free to contact:

- Name: Yuvraj Singh Shishodia
- Email: yuvrajsinghshishodia@gmail.com
