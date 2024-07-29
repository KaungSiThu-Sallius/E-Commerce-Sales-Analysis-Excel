# E-Commerce-Sales-Analysis-Excel
<p>In this analysis, we will examine key aspects of e-commerce sales data to uncover insights and trends that can inform business strategies and decision-making. The specific questions addressed in this analysis include:</p>
<ol>
  <li><b>Which products have the highest sales?</b>
    <p>Identifying the top-performing products in terms of sales volume and revenue.</p>
  </li>
  <li><b>In what month do specific products experience low sales?</b>
    <p>Analyzing monthly sales trends to pinpoint periods of low sales for different products.</p>
  </li>
  <li><b>Which product category has the highest sales?</b>
    <p>Determining the most successful product categories based on overall sales figures.</p>
  </li>
  <li><b>Which states have the highest and lowest sales?</b>
    <p>Assessing state-wise sales performance to identify geographic trends and opportunities.</p>
  </li>
  <li><b>Which brand is the most popular?</b>
    <p>Evaluating brand popularity by analyzing sales data across different brands.</p>
  </li>
</ol>

## Cleaning the dataset
### Step 1: Understand the dataset

<p>The dataset contains 5096 records of sales transactions between 11/01/2020 - 31/12/2022. <br>There are 14 columns of data as below: </p>

<ol>
  <li><b>Order_Number</b>: Unique identifier for each order.</li>
  <li><b>State_Code</b>: The code representing the state where the order was placed.</li>
  <li><b>Customer_Name</b>: The name of the customer who placed the order.</li>
  <li><b>Order_Date</b>: The date when the order was placed.</li>
  <li><b>Status</b>: The current status of the order (e.g., Order, Processing, Shipped, Delivered).</li>
  <li><b>Product</b>: The name or identifier of the product sold.</li>
  <li><b>Category</b>: The category to which the product belongs.</li>
  <li><b>Brand</b>: The brand of the product.</li>
  <li><b>Cost</b>: The cost incurred by the business to acquire or produce the product.</li>
  <li><b>Sales</b>: The revenue earned from selling the product.</li>
  <li><b>Quantity</b>: The number of units sold in the order.</li>
  <li><b>Total_Cost</b>: The total cost for the quantity sold (Cost * Quantity).</li>
  <li><b>Total_Sales</b>: The total revenue for the quantity sold (Sales * Quantity).</li>
  <li><b>Assigned Supervisor</b>: The supervisor responsible for the order.</li>
</ol>

<p>Firstly, I converted the cells into a table by using <kbd>Cmd</kbd> + <kbd>T</kbd> in Excel.</p>

### Step 2: Check for Duplicates Records

<p>After understanding the dataset, I check for any duplicates first by Excel built-in functionality, "Remove Duplicates".</p>

### Step 3: Check for Any Blanks or Irregular Values in Records

<p>By using conditional formatting, I highlighted the blank cells. Since the highlighted rows were all empty, I deleted them. I didn't find any blank cells or irregular values.</p>




