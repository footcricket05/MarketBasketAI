# Market Basket Analysis in Python using Apriori Algorithm

Market basket analysis is a versatile use case in the retail industry that helps cross-sell products in a physical outlet and also helps e-commerce businesses recommend products to customers based on product associations. Apriori and FP growth are the most popular machine learning algorithms used for association learning to perform market basket analysis.


## Overview
This project uses the Apriori algorithm in Python to perform market basket analysis on a retail dataset. The goal is to identify associations between products that are frequently bought together and provide recommendations for cross-selling. The implementation uses the mlxtend library for Apriori algorithm and the pandas library for data manipulation.

## Dataset
The dataset used in this project is the Online Retail dataset, which contains sales transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based online retail store. The dataset has 541,909 transactions and 8 columns containing product details, such as description, quantity, and price.

## Requirements

1. Python 3.6 or higher
2. 
3. Pandas
4. 
5. NumPy
6. 
7. mlxtend



## Usage
Clone the repository:
```
git clone https://github.com/footcricket05/Market-Basket-Analysis-ML.git
```

Navigate to the project directory:
```
cd Market-Basket-Analysis-ML
```

Install the required libraries:
```
pip install -r requirements.txt
```

Open the market_basket_analysis.ipynb Jupyter Notebook:
```
jupyter notebook market_basket_analysis.ipynb
```

Run the cells in the notebook to see the results of the market basket analysis.


## Results
The market basket analysis was able to identify several product associations with high support and confidence, such as the association between bread and milk. This information can be used to make recommendations for cross-selling, such as displaying milk near the bread aisle in a physical store or recommending milk to customers who have added bread to their online shopping cart.


## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or feedback.

## License
This project is licensed under the MIT License.
