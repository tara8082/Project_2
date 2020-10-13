# Predicting Sale Prices in West Chicago Neighborhoods using Linear Regression

This code scrapes Zillow (www.zillow.com) property listing data to fit a linear regression model on home prices in Chicago West Neighborhoods. 

## Tools Used
- Beautiful Soup
- Selenium
- SciKit Learn

## Conclusions

Square footage can have a profound impact on home sale price. Features like "season of home sale", "HOA fees", and "year built" should be added to improve the model.

## Outline of Files

**1. The notebook titled Scraping_Listing_Links_and_HTML scrapes data from Zillow.com for West Town, Wicker Park, and Bucktown neighborhoods. The output for the links and HTML is in the labeled pickle files. 

    

**2. The notebook titled "Features_and_LinearRegression.ipynb" contains code to extract listing data from Zillow's HTML. The output is saved to a CSV and opened as a dataframe.

- Listing Address
- Sale Price
- Square Footage
- Listing Status
- Number fo Bedrooms
- Number of Bathrooms
- Zip Code
- Parking
- HOA Fees
- Sold Date

**3. The notebook titled  "Features_and_LinearRegression.ipynb" is used for exploratory data analysis on the dataframe containing the Zillow listing data. The notebook also contains final R^2 scores using Linear Regression modules and corresponding visuals.


**4. The pdf titled "Pres_Deck_Project_2_PredictingHomePrices" contains presentation materials on the Linear Regression project including background, tools, methodology, results, and recommendations.

**5. The CSV titled "Listing_Dictionary_Combined.csv" contains the CSV file for the listing dictionary scraped from Zillow.com.

**6. Pickle files include scraped data.
- wp_bt_listing_links.pkl : Zillow listing links from Wicker Park and Bucktown.
- listing_html_COMBINED.pkl : listing HTML for Wicker Park, Bucktown, and West Town.



