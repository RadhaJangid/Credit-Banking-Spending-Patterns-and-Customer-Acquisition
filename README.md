# 
<h1 style="font-family:verdana;">Credit Banking Spending Patterns and Customer Acquisition</h1> 
<h2 style="font-family:verdana;">Overview</h2>
<p style="font-family:courier;">As a Data Analytics Intern at <b>EduLyt India</b>, I engaged in a comprehensive project focused on Credit Banking Spending Patterns and Customer Acquisition. Using Python, I delved deep into the datasets, extracting valuable insights for informed decision-making in e-commerce sector. This experience not only showcased my analytical skills but also highlighted my meaningful contribution during my internship at <b>EduLyt India</b>.
</p>
<h2 style="font-family:verdana;">About the Organization</h2> 
<P style="font-family:courier;">
Edulyt India is an early age start-up working towards reducing the Gap between Education & 
Employment, founded in 2015 with a mission to train fresh graduates. Disrupting the education 
management sector mainly focused on the field of Analytics. 
Our core area of working is in Data Analytics for BFSI domain. 
Our team is working on basic AI tools to make the world a better easier place to live. Our core 
expertise lies in making the Graduates industry ready. We are highly skilled and trained in 
delivering training to aspiring Graduates. </p>

<h2 style="font-family:verdana;">Dataset Used</h2>
<h4 style="font-family:verdana;">Customer Acquisition :</h4>
<p style="font-family:courier;">The Customer Acquisition dataset contains information about individuals acquiring credit card products. This dataset helps in understanding customer demographics and acquisition details.</p>
<h4 style="font-family:verdana;">Spend : </h4>
<p style="font-family:courier;">The Spend dataset captures spending patterns, associating customers with different spending categories.This dataset provides insights into how customers distribute their expenditures across various categories over time.</p>
<h4 style="font-family:verdana;">Repayment : </h4>
<p style="font-family:courier;">The Repayment dataset focuses on customer repayments. This dataset allows tracking customer repayment behaviors and understanding how timely repayments correlate with other financial aspects. </p>

<h2 style="font-family:verdana;">Project Details</h2>
<h4 style="font-family:verdana;">Internship : Edulyt India</h4>
<h4 style="font-family:verdana;">Domain/Field : Analytics</h4>
<h4 style="font-family:verdana;">Project Type : Data Analysis</h4>
<h4 style="font-family:verdana;">Features : </h4>
  <p style="font-family:verdana;">
     ⚡Python Programming Language<br>
     ⚡EDA [For insights gathering and analysis]<br>
     ⚡Pandas [For working with datasets/For analyzing, cleaning, exploring, and manipulating data]<br>
     ⚡Matplotlib & Seaborn [For answer some business questions in the form of visuals]<br>
     ⚡Statistics [For calculating  mathematical statistics of numeric data]<br>
     ⚡Google Colab</p>
  








# DATASET INFO
<div class="w3-container">
  <table class="w3-table-all w3-card-4">
    <tr>
      <th>COLUMN NAME</th>
      <th>DATA TYPE</th>
      <th>TABLE</th>
      <th>DESCRIPTION</th>
    </tr>
    <tr>
      <td>Sl No:</td>
      <td>integer</td>
      <td>Customer Acqusition</td>
      <td>Unique identifier for each record</td>
    </tr>
    <tr>
      <td>Customer</td>
      <td>string</td>
      <td>Customer Acqusition</td>
      <td>Contains identifiers of the customers</td>
    </tr>
    <tr>
      <td>Age</td>
      <td>decimal</td>
      <td>Customer Acqusition</td>
      <td>Age of customers</td>
    </tr>
    <tr>
      <td>City</td>
      <td>string</td>
      <td>Customer Acqusition</td>
      <td>The city where the customer resides</td>
    </tr>
    <tr>
        <td>Credit Card Product</td>
        <td>string</td>
        <td>Customer Acqusition</td>
        <td>The type of the credit card product acquired by the customer</td>
    </tr>
    <tr>
        <td>Limit</td>
        <td>integer</td>
        <td>Customer Acqusition</td>
        <td>Credit limit associated with each customer's credit card</td>
    </tr>
    <tr>
        <td>Company</td>
        <td>string</td>
        <td>Customer Acqusition</td>
        <td>The company or financial institution providing the credit card product</td>
    </tr>
    <tr>
        <td>Segment</td>
        <td>string</td>
        <td>Customer Acqusition</td>
        <td>Customer segment to which each customer belongs</td>
    </tr>    
    <tr>
      <td>Sl No:</td>
      <td>integer</td>
      <td>Spend</td>
      <td>Unique identifier for each record</td>
    </tr>
    <tr>
      <td>Costomer</td>
      <td>string</td>
      <td>Spend</td>
      <td>Identifiers of customers associated with spending records.</td>
    </tr>
    <tr>
      <td>Month</td>
      <td>date</td></td>
      <td>Spend</td>
      <td>Date indicating when the spending occurred</td>
    </tr>
    <tr>
      <td>Type</td>
      <td>string</td>
      <td>Spend</td>
      <td>Type of spending</td>
    </tr>
    <tr>
        <td>Amount</td>
        <td>decimal</td>
        <td>Spend</td>
        <td>The amount spent in the respective spending type</td>
    </tr>
    <tr>
      <td>SL No:</td>
      <td>integer</td>
      <td>Repayment</td>
      <td>Unique identifier for each record</td>
    </tr>
    <tr>
      <td>Costomer</td>
      <td>string</td>
      <td>Repayment</td>
      <td>Identifiers of customers associated with repayment records.</td>
    </tr>
    <tr>
      <td>Month</td>
      <td>date</td>
      <td>Repayment</td>
      <td>Date or timestamp indicating when the repayment occurred</td>
    </tr>
    <tr>
        <td>Amount</td>
        <td>decimal</td>
        <td>Repayment</td>
        <td>The amount repaid by the customer in the respective month</td>
    </tr>
  </table>
</div>



# DATA ANALYTICS PROCESS
<img src="Data_Analytics_Process.png" alt="Data Analytics Process" width="500" height="400">

# METHODOLOGY
<h2>Loading Dataset</h2> 
<p>In this project we will use “Credit Banking Dataset”.
First, we will load data from an Excel file using the Pandas.ExcelFile() function, the data is available in three worksheets. The names of the worksheets are - 
    <ul>
        <li>Customer Acquisition</li>
        <li>Spend</li>
        <li>Repayment</li>
    </ul>
Then we will read data from different sheets using read_excel() function and store the data in a DataFrame object.</p>

<h2>Basic Data Analysis</h2>
<ul>
    <li>Look at the top/bottom 5 records of data.</li>
    <li>Check various attributes of data like shape (rows and columns), columns, datatype.</li>
    <li>Checking data types of all columns.</li>
    <li>Consize summary of dataframe.</li>
    <li>Check descriptive statistics of numerical variables.</li> 
    <li>Missing data :- Initial intuition</li>
    <li>Data Cleaning
                <ol type = "1">
                    <li>Create a copy of base data for manupulation & processing.</li>
                    <li>Converting the date into year and month columns</li>
                    <li>Rename Costomer column as Customer</li>
                    <li>Invalid / Missing data</li>
                    <li>Invalid value Treatment</li>
                    <li>Feature Binning</li>
                    <li>Remove columns not required for processing.</li>
                </ol>
     </li>
</ul>
<h2>Merging Data</h2>
<ul>
    <li>Merge Customer and Spend , Customer and Repayment</li>
    <li>Merge Customer , Spend, Repayment dataset</li>
</ul>
<h2>EDA(Exploratory data analysis) - Data Exploration</h2>
<ol type="1">
    <li>Plot distibution of individual predictors.
        <ul>
            <li>Univariate Analysis</li>
            <li>Bivariate Analysis</li>
        </ul>
    </li>
    <li>Convert all the categorical variables into dummy variables.</li>
    <li>Build a corelation of all predictors.</li>
</ol>


<h2 style="font-family:verdana;">How to Use</h2>
<p style="font-family:courier;">This repository includes a Python file for data analysis. Feel free to delve into the code and explore the insights.</p>

<h2 style="font-family:verdana;">Acknowledgments</h2>
<p style="font-family:courier;">I would like to express my gratitude to the entire team of <b>EduLyt India</b> for providing the necessary facilities and allowing me to complete this project in the organization. I would especially like to thank <b>Mr. Lalit Chaudhary</b> for providing me with this wonderful opportunity to work on this project, gaining experience in data analysis, and for his constant guidance and support throughout the project.</p>
