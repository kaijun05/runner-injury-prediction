# **Data-Driven Training Analytics for Competitive Runners 🏃‍♂️**
CDS6214 Data Science Fundamentals (Trimester March/April 2024 - Term 2410)

## **Overview**
<div align="justify"> 
This project focuses on predicting injury occurrences in runners using machine learning techniques. The dataset, obtained from <a href='https://test.dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/UWU9PV'>DataVerseNL</a>, consists of training logs from a Dutch high-level running team (2012-2019), including various training and physiological metrics.
</div>

## **Main Problem**
How to Improve the Effectiveness of Runner’s Training Program?

## **Questions Addressed**
1. **Descriptive:** What are the distributions of key training metrics across different athletes and training sessions?
2. **Exploratory:** What patterns or relationships exist between training intensity, success rates, and recovery times across different athletes?
3. **Causal:** Does increasing the intensity of interval sessions and the overall demand of workouts cause improvements in training outcomes, or does it increase the risk of overtraining and injury?
4. **Predictive:** Can we predict whether an athlete is likely to sustain an injury based on their historical data and recorded features?

## **Installation & Requirements**
Before running the project, make sure you have installed the following:
* Python 3.13+
* pip (Python Package Manager)
* Virtual Environment
* Jupyter Notebook

1. In your terminal, clone the repository by typing
```bash
git clone https://github.com/kaijun05/runner-injury-prediction.git
cd runner-injury-prediction
```
2. Create a virtual environment (recommended)
```bash
# On macOS/Linux
python<version> -m venv <virtual-environment-name>
source <virtual-environment-name>/bin/activate  

# On Windows
python<version> -m venv <virtual-environment-name>
<virtual-environment-name>\Scripts\activate
```
3. Install Jupyter Notebook. Alternatively, you may install Jupyter Notebook through Anaconda (recommended) [here](https://docs.jupyter.org/en/latest/install/notebook-classic.html)
```bash
pip install notebook
```
4. Install the required packages by typing:
```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install imblearn
pip install xgboost
```
5. If you use Conda environment, you can install dependencies using Conda as such:
```bash
conda create --name <env> --file requirements.txt
```

## **Running the Project**
1. Open the repository in your terminal and activate the virtual environment:
```bash
source env/bin/activate  # On macOS/Linux  
env\Scripts\activate  # On Windows
```
2. Start Jupyter Notebook
```bash
jupyter notebook
```
3. Open the notebook (`main.ipynb`) and **run all the cells**.
