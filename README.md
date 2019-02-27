# Bank Telemarketing Success Analysis

This repository contains the solution of a Decision Support System problem proposed in the intern hiring process of [UpGrad](https://www.upgrad.com). The data provided is past data collected during direct marketing campaigns of a Portuguese banking institution from May 2008 to November 2010 and can be found in `Data/bank-additional-full.csv` folder. The complete data repository is available [here](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing). The data is in `.csv` format delimited by `;` and contains **21 features** and **41188 datapoints**. The 20 features contains information about the customer based on personal, socio-economic and last contacted factors. The last column is a response column which states whether a subject buy the term deposit product or not
<br /><br />
The goal here is to reduce the marketing cost and acquire more number of prospects by making well targeted calls to potential success points. The **random calling approach** has a very low success rate and thus it is not reliable to achieve successful campaign results. The **targeted customer approach** is expected to make an accurate prediction before the call, which will help a call operator to deciding how much time should be spent on that customer. In this way the extra time wasted on convincing a negative reponse customer can be minimized and that extra time can be used to contact new potential buyers
<br /><br />
I first performed a detailed **Data Exploration** using mathematical tools and **visualisation** techniques to get a proper insight about the data. I used those insight to decide important **discriminative features** to perform this **binary classification task**. **Feature engineering** was used on those selected features to make them further separable and useful. Lastly, the classification task was performed using **Support Vector Machine** and **Neural Networks** and the results were compared
<br /><br />
All the tasks mentioned above is displayed in `complete.ipynb` file. A pdf version of the same is available as `complete.pdf`. The `Notebooks/` folder contains experimentations with code to complete different sections. All the files is well documented with comments as required for easy and clear understanding. The complete.ipynb file can be opened by clicking on it. The pdf version can be opened the usual way or by clicking [here](). If you wish to run the code yourself, instructions to run the code is provided at the bottom of this page
<br /><br />
**THANK YOU**
<br /><br />

## Instructions to Run

1. First, clone this repository in your local computer<br />
2. Open the terminal or enviornment in which Python3 exists. Type the following command while inside the prompt window: ``pip3 install -r /path/to/requirements.txt`` This will install all the libraries needed to run this project.<br />
3. Now, type `jupyter notebook` in the command window and browse to the `complete.ipynb` file.<br />
4. Click on the file to open and now run each cell to observe and experiment with the outputs