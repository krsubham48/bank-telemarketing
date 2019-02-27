# Bank Telemarketing Success Analysis

This repository contains the solution of a Decision Support System problem proposed in the intern hiring process of [UpGrad](https://www.upgrad.com). The data provided is past data collected during direct marketing campaigns of a Portuguese banking institution from May 2008 to November 2010 and can be found in `Data/bank-additional-full.csv` folder. The complete data repository is available [here](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing). The data is in `.csv` format delimited by `;` and contains **21 features** and **41188 datapoints**. The 20 features contains information about the customer based on personal, socio-economic and last contacted factors. The last column is a response column which states whether a subject buy the term deposit product or not
<br /><br />
The goal here is to reduce the marketing cost and acquire more number of prospects by making well targeted calls to potential success points. The **random calling approach** has a very low success rate and thus it is not reliable to achieve successful campaign results. The **targeted customer approach** is expected to make an accurate prediction before the call, which will help a call operator to deciding how much time should be spent on that customer. In this way the extra time wasted on convincing a negative reponse customer can be minimized and that extra time can be used to contact new potential buyers
<br /><br />
I first performed a detailed **Data Exploration** using mathematical tools and **visualisation** techniques to get a proper insight about the data. I used those insight to decide important **discriminative features** to perform this **binary classification task**. **Feature engineering** was used on those selected features to make them further separable and useful. Lastly, the classification task was performed using **Random Forest** and **Neural Networks** and the results were compared
<br /><br />
All the tasks mentioned above is displayed in `Home` folder. A pdf version of the same is available `.pdf` in `Files/` folder. All the files is well documented with comments as required for easy and clear understanding. All the `.ipynb` files can be opened in this github window by clicking on it. The pdf version can be opened the usual way. If you wish to run the code yourself, instructions to run the code is provided at the bottom of this page

## Analysis Results

• The reponse for term-deposit reponse is positive for an age group ranging roughly between 23-60 years. Customes less than 23yrs of age are mostly unemployed students who does not posses sufficient money to invest. Similarly, people belonging to age group grater than 60 doesnot buy term-deposit having long maturity period. Hence, the next campaign should focus on the said age group more specifically

• we see students, self-employed, entrepreuners, unemployed, housemaid and unknowns seems to be broke and cannot afford to buy a term-deposit. On the other hand, technician, blue-collar, management, services, retired and admin have sufficient funds to invest in term-deposit. Again, the conclusion is very distinct here that it is more useful to target subjects that have money to invest these kinds of scheme and products. Already broke people have little chances to buy the product

• Divorced seem to have less positive response compared to singles and married. They have a positive aura around that might drive them to buy the product. Also, there might be cases where their future plans and savings might be a major driving factor in decision making

• People who are not under any kind of loan repayment burden are more likely to buy term insurance and thus those group of people should be targeted more

• We see Day of Week has little effect on term-deposit sell. In contrast, Month shows large variation with sell in May almost four times the sell in March and more than 8 times the sell in Dec. This gives us a clear hint and indication that the sell remain moderate in year start, peaks in the middle and drops significantly towards year end

• We observe an interesting pattern in analysing Campaign feature. Most of the subjects who bought the term-deposit made it clear in first few contacts and the number of positive responses fell drastically as the number of contacts increased. Thus we can safely conclude that it is a waste of cost, time and effort to contact the same client multiple times and it is more benefitial to target new customers

• For the subjects already contacted before, the number of sells is max after 2-7 days since last contact. This might be inferred as the time a customer to rethink about a deal and make a deal. As the number of days passed increases after 10 days, the client is less likely to buy the product and thus can be contacted and urged again


## Instructions to Run

1. First, clone this repository in your local computer<br />
2. Open the terminal or enviornment in which Python3 exists. Type the following command while inside the prompt window: ``pip3 install -r /path/to/requirements.txt`` This will install all the libraries needed to run this project<br />
3. Now, type `jupyter notebook` in the command window and browse to the `.ipynb` files<br />
4. Click on the file to open and now run each cell to observe and experiment with the outputs