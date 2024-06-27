# Running the code
> Note: [Pdf](Project1.pdf) file is well formatted and easy to read.

## Requirements
- **Jupyter Notebook Support**
- Run `pip install -r requirements.txt` to install all the dependencies in your environment.

## Running the code
- Run `jupyter notebook` in your terminal to open the notebook in your browser.
- Open the `Project1.ipynb` file and run the cells in the notebook.

## Simply want to see the results?
- Open the `Project1.pdf` file to see the results of the notebook.

## Author

|Name                       | Roll Number   |
|---                        |---            |
|Yelisetty Karthikeya S M   | 21CS30060     |

Github: [lurkingryuu](https://github.com/lurkingryuu)

---
# Project-I 
## Objective
1. Classify breast tumor dataset into 2 classes, i.e., benign or malignant using machine learning models like Logistic Regression, SVM, Neural Network.
2. Evaluate the model accuracy.

## About Dataset
The given dataset is made up with fine needle aspiration biopsy reports where a thin needle is inserted into abnormal tissue or fluid, aiding in diagnosis or excluding conditions like cancer. The dataset contains a total of 569 biopsy reports out of which 357 are benign, and 212 are malignant. The "diagnosis" column contains the report, with "M" indicating Malignant and "B" indicating Benign.

### Parameters
Ten real-valued features are computed for each cell nucleus:

- a) radius (mean of distances from center to points on the perimeter)
- b) texture (standard deviation of gray-scale values)
- c) perimeter
- d) area
- e) smoothness (local variation in radius lengths)
- f) compactness (perimeter * 2 / area - 1.0)
- g) concavity (severity of concave portions of the contour)
- h) concave points (number of concave portions of the contour)
- i) symmetry
- j) fractal dimension

The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features.

## Project Structure
Create a folder with the name `<YourRoll>_A1`. Copy your code and all your supporting files into this folder, including one README file on how to execute the code.

## Note
> Do not use the logistic regression function directly. Write the code for logistic regression from scratch.
