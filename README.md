# ***Supermarket-Sales-Analysis-Using-Python*** 
<p>The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data. Predictive data analytics methods are easy to apply with this dataset.</p>

<p><strong>Attribute information</strong><br />
<br />
Invoice id: Computer generated sales slip invoice identification number<br />
<br />
Branch: Branch of supercenter (3 branches are available identified by A, B and C).<br />
<br />
City: Location of supercenters<br />
<br />
Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.<br />
<br />
Gender: Gender type of customer<br />
<br />
Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel<br />
<br />
Unit price: Price of each product in $<br />
<br />
Quantity: Number of products purchased by customer<br />
<br />
Tax: 5% tax fee for customer buying<br />
<br />
Total: Total price including tax<br />
<br />
Date: Date of purchase (Record available from January 2019 to March 2019)<br />
<br />
Time: Purchase time (10am to 9pm)<br />
<br />
Payment: Payment used by customer for purchase (3 methods are available &ndash; Cash, Credit card and Ewallet)<br />
<br />
COGS: Cost of goods sold<br />
<br />
Gross margin percentage: Gross margin percentage<br />
<br />
Gross income: Gross income<br />
<br />
Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)</p>

# ***Univariate Analysis***
<img src="Images/Univariate Analysis.png"/>
<img src="Images/Univariate Analysis2.png"/>

# ***Bivariate Analysis***
<img src="Images/Bivariate Analysis Before Normalize.png"/>

### We need to observe `the count of invoices`, therefore we need to `Normalize` the total to start 1, to do this we will *devid the total of each column by day One.*

### $$Norm = df/df.iloc[0,:]$$
## ***We will apply Normalization on Dataset***
<img src="Images/Bivariate Analysis After Normalize.png"/>

## *Now we can Say the most branch Make big Sales Movement in All Time is `branch C` and then `branch B` and then `branch A`*
### It is calear that the branch 'A' has less sales Movement than the other, we need more data to investigate why.  

