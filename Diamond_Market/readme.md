Here you will find a regression analysis of the US Diamond Market based on the prices collected from [RareCarat](https://www.rarecarat.com).

The project has 3 steps:
1. The data is scraped using the code in the notebook: diamond_scrape.ipynb and saved to several .pkl files.
2. These files (as lists) are loaded into a pandas dataframe and cleaned in the notebook: diamond_model.ipynb
3. A multinomial regression analysis is performed using L1 and L2 norm penalties to categorize the importance of the feature space.
 
