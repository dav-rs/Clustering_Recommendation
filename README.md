# CodeChallengeExp

## Coffee classification challenge 
This repository contains 2 main folders with two tasks, scrapping and clustering for around 1.5K records from the Coffee Institute database. In the scrapping folder there is a  Jupyter notebook,  scrapper_clean.ipynb, containing all the code to get the latest records using Selenium and BeautifulSoup. The final part of the code performs the cleaning and transformation of the data to join it with the cleaned data obtained from https://github.com/jldbc/coffee-quality-database/tree/master/data. This output is then used in the clustering task.  
**Note:** It may be necessary to !pip install webdriver-manager in order to execute the ChromeDriverManager. In that case the first cell in the code can be uncommented. 

The clustering folder, contains another Jupyter notebook, clustering.ipynb, with the code and conclusions about the complete task. The cleaned dataset obtained from the previous task is loaded and then sklearn library is used to train some clustering algorithms (K-means and Hierarchical clustering). Some visualizations are included using matplotlib and seaborn. 

Additional pdf versions of the notebooks can be found in each corresponding folder.

The code in both Jupyter notebooks uses:
* Python 3.7.1
* sklearn 0.23.1
* selenium.webdriver 3.14.1
* pandas 0.25.2
* numpy 1.18.5
* seaborn 0.10.1

