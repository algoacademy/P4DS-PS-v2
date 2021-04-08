This quiz is part of Algoritma Academy assessment process. Congratulations on completing the Programming for Data Science and Practical Statistics course! We will conduct an assessment quiz to test the practical programming techniques that you have learned from the course. The quiz is expected to be taken in the classroom, please contact our team of instructors if you missed the chance to take it in class.

# Instruction

In this quiz, we will be using a retail dataset. You can get the CSV file stored within the `datainput` folder under the `retail.csv` file. The data stored a record of transactions of a retail store specifying several variables. Please take a look at the following glossary for your reference:

- `Order.ID`: Id of order.
- `Order.Date`: Date of order.
- `Ship.Date`: Date of shipment.
- `Ship.Mode`: Type of shipment.
- `Customer.ID`: Id of customer.
- `Segment` : Customer's segment.
- `Product.ID`: Id of product.
- `Category` : Product category with 3 levels ("Furniture", "Office Supplies", "Technology")    
- `Sub.Category`: more specific product category
- `Product.Name`: Name of product that was sold.
- `Sales`: How much earning from each sale.
- `Quantity`: Quantity of item sold.
- `Discount`: How much discount was given for each sale.
- `Profit`: How much can a company earn from each sale.

We will split this quiz into 2 main sections: Programming for Data Dcience and Practical Statistics, each assessing the respective knowledge we have learned in the 2 courses.

## Programming for Data Science

1. Among the records, most of the products were sent using "Standard Class" shipment. However, we are more interested in finding out how many transactions that generate above-average Sales and were sent using other than "Standard Class" shipment. Use a conditional subsetting to find out the number of transactions with the given conditions!
  - [ ] 337
  - [ ] 948
  - [ ] 2034
  - [ ] 4026

2. If you take a look at the `Category` column, you will see there are several types of product categories. Among all shipment types, which shipment type is mostly used for the *Office Supplies* category?
  - [ ] First Class
  - [ ] Same Day
  - [ ] Second Class
  - [ ] Standard Class

3. If we analyze the product subcategories purchased by the corporate segment, which are the 3 most profitable subcategories, taking into account the total profit earned from each subcategory?
  - [ ] Copiers, Accessories, Phones
  - [ ] Copiers, Phones, Paper
  - [ ] Tables, Fasteners, Supplies 
  - [ ] Tables, Supplies, Bookcases

## Practical Statistics

4. In descriptive statistics, there are two main measurements that are commonly used to describe data distribution: central tendency and measure of spread. Which statistical measure can be used to describe the first one and is sensitive to outliers?
  - [ ] Range
  - [ ] IQR
  - [ ] Mean
  - [ ] Median

5. Find out the correlation between Sales and Quantity of the transactions using the `cor()` function. Based on the correlation between the two, which of the following statements are true?
  - [ ] Correlation = 0.8, Quantity and Sales are positively related
  - [ ] Correlation = -0.2, when Quantity increases Sales also increases
  - [ ] Correlation = 0.8, Quantity and Sales are not related
  - [ ] Correlation = 0.2, when Quantity increases Sales also increases

6. Consider this case: The retail company would like to apply a promotion to increase the number of sales. Based on historical records, we know that the monthly sales population has an average of 228.61 USD with a standard deviation of 26.24 USD and is distributed normally. After the promotion applied for a month, the company gained an average sales of 294.55 USD. Using 95% confidence interval, perform a significance test using z-test to find out whether the promotion managed to significantly affect the number of sales. How would you conclude the test using the given information?
  - [ ] Reject the null hypothesis, The promotion has no significant effect on sales  
  - [ ] Reject the null hypothesis, The promotion has significant effect on sales
  - [ ] Fail to reject the null hypothesis, The promotion has no significant effect on sales
  - [ ] Fail to reject the null hypothesis, The promotion has significant effect on sales
