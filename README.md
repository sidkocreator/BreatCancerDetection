# BreatCancerDetection

DESCRIPTION:

There are many different types of breast cancer, with different stages or spread, aggressiveness, and genetic
makeup. Survival rates for breast cancer may be increased when the disease is detected in its earlier stage through
mammograms. The implementation of mass screening would result in increased caseloads for radiologists. This will
increase chances of improper diagnosis. The prediction using logistic regression would aid the radiologist to detect
the breast cancer. This project aims to classify the severity of the beast cancer using attributes such as mean radius, mean texture, mean perimeter among others and label it benign or malignant. Logistic Rgression is used to train the model and a sample data is provided to the trained model to classify as benign or malignant.

OBJECTIVE:

The aim of this analysis is to use Logistic Regression to classify the data into two classes of diagnosis— Malignant & Benign.

DATASET:

The Wisconsin Breast Cancer (Diagnostic) dataset has been extracted from the UCI Machine Learning Repository. Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.

kaggle link to dataset: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

data.csv link : https://drive.google.com/file/d/1z1YIzmhLc21vCkQb9JiIR9nMmnuRvzla/view?usp=sharing

STEPS TO RUN:

Run the BreastCancerDetection.ipynb file. You will notice a pickle file to be generated and an app.py file. Use !pip install streamlit --quiet to install streamlit and then run the file using !streamlit run app.py & npx localtunnel --port 8501. Now, go over to the generated link and enter any sample data from the data.csv file and observe the output ( either Malignant or Benign ).
