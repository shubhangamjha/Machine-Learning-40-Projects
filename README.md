# Machine Learning 40 Projects

<hr><br>

<h1>01. <a href = "https://github.com/UTSAVS26/Machine-Learning-40-Projects/tree/main/01%20Credit%20Score%20Classification">Credit Score Classification</a></h1>
<p>
  <h2>Overview</h2>
  <p>This repository contains a machine learning model for predicting credit scores based on various financial attributes of individuals. The goal is to help financial companies assess the creditworthiness of applicants.</p>
  <h2>Financial Attributes</h2>
  <h3>Identification</h3>
  <table>
    <tr>
        <td><code>ID</code></td>
        <td>Unique ID of the record</td>
    </tr>
    <tr>
        <td><code>Customer_ID</code></td>
        <td>Unique ID of the customer</td>
    </tr>
    <tr>
        <td><code>Month</code></td>
        <td>Month of the year</td>
    </tr>
  </table>
  <h3>Personal Information</h3>
  <table>
    <tr>
        <td><code>Name</code></td>
        <td>The name of the person</td>
    </tr>
    <tr>
        <td><code>Age</code></td>
        <td>The age of the person</td>
    </tr>
    <tr>
        <td><code>SSN</code></td>
        <td>Social Security Number of the person</td>
    </tr>
    <tr>
        <td><code>Occupation</code></td>
        <td>The occupation of the person</td>
    </tr>
  </table>
  <h3>Financial Details</h3>
  <table>
    <tr>
        <td><code>Annual_Income</code></td>
        <td>The Annual Income of the person</td>
    </tr>
    <tr>
        <td><code>Monthly_Inhand_Salary</code></td>
        <td>Monthly in-hand salary of the person</td>
    </tr>
    <tr>
        <td><code>Num_Bank_Accounts</code></td>
        <td>The number of bank accounts of the person</td>
    </tr>
    <tr>
        <td><code>Num_Credit_Card</code></td>
        <td>Number of credit cards the person is having</td>
    </tr>
    <tr>
        <td><code>Interest_Rate</code></td>
        <td>The interest rate on the credit card of the person</td>
    </tr>
    <tr>
        <td><code>Num_of_Loan</code></td>
        <td>The number of loans taken by the person from the bank</td>
    </tr>
    <tr>
        <td><code>Type_of_Loan</code></td>
        <td>The types of loans taken by the person from the bank</td>
    </tr>
    <tr>
        <td><code>Delay_from_due_date</code></td>
        <td>The average number of days delayed by the person from the date of payment</td>
    </tr>
    <tr>
        <td><code>Num_of_Delayed_Payment</code></td>
        <td>Number of payments delayed by the person</td>
    </tr>
    <tr>
        <td><code>Changed_Credit_Card</code></td>
        <td>The percentage change in the credit card limit of the person</td>
    </tr>
    <tr>
        <td><code>Num_Credit_Inquiries</code></td>
        <td>The number of credit card inquiries by the person</td>
    </tr>
    <tr>
        <td><code>Credit_Mix</code></td>
        <td>Classification of Credit Mix of the customer</td>
    </tr>
    <tr>
        <td><code>Outstanding_Debt</code></td>
        <td>The outstanding balance of the person</td>
    </tr>
    <tr>
        <td><code>Credit_Utilization_Ratio</code></td>
        <td>The credit utilization ratio of the credit card of the customer</td>
    </tr>
    <tr>
        <td><code>Credit_History_Age</code></td>
        <td>The age of the credit history of the person</td>
    </tr>
    <tr>
        <td><code>Payment_of_Min_Amount</code></td>
        <td>Yes if the person paid the minimum amount to be paid only, otherwise no</td>
    </tr>
    <tr>
        <td><code>Total_EMI_per_month</code></td>
        <td>The total EMI per month of the person</td>
    </tr>
    <tr>
        <td><code>Amount_invested_monthly</code></td>
        <td>The monthly amount invested by the person</td>
    </tr>
    <tr>
        <td><code>Payment_Behaviour</code></td>
        <td>The payment behaviour of the person</td>
    </tr>
    <tr>
        <td><code>Monthly_Balance</code></td>
        <td>The monthly balance left in the account of the person</td>
    </tr>
    <tr>
        <td><code>Credit_Score</code></td>
        <td>The credit score of the person</td>
    </tr>
  </table>
</p>

<hr>

<h1>02. <a href="https://github.com/UTSAVS26/Machine-Learning-40-Projects/tree/main/02%20Weather%20Forecasting">Weather Forecasting</a></h1>

<p>
  <h2>Overview</h2>
  <p>This repository focuses on weather forecasting using machine learning techniques. The dataset provides data from 1st January 2013 to 24th April 2017 in the city of Delhi, India. The 4 parameters included are:</p>
  <table>
    <tr>
        <td><code>meantemp</code></td>
        <td>Mean temperature</td>
    </tr>
    <tr>
        <td><code>humidity</code></td>
        <td>Humidity</td>
    </tr>
    <tr>
        <td><code>wind_speed</code></td>
        <td>Wind speed</td>
    </tr>
    <tr>
        <td><code>meanpressure</code></td>
        <td>Mean pressure</td>
    </tr>
  </table>
</p>

<hr>

<h1>03. <a href=""https://github.com/UTSAVS26/Machine-Learning-40-Projects/tree/main/03%20Food%20Delivery%20Time%20Prediction">Food Delivery Time Prediction</a></h1>

<p>
  <h2>Overview</h2>
  <p>This repository focuses on predicting food delivery time by calculating the distance between the point of picking up the order and the point of delivering the order. The prediction is based on the historical delivery time for similar distances covered by delivery partners.</p>
  <h2>Dataset Features</h2>
  <table>
    <tr>
        <td><code>ID</code></td>
        <td>Order ID number</td>
    </tr>
    <tr>
        <td><code>Delivery_person_ID</code></td>
        <td>ID number of the delivery partner</td>
    </tr>
    <tr>
        <td><code>Delivery_person_Age</code></td>
        <td>Age of the delivery partner</td>
    </tr>
    <tr>
        <td><code>Delivery_person_Ratings</code></td>
        <td>Ratings of the delivery partner based on past deliveries</td>
    </tr>
    <tr>
        <td><code>Restaurant_latitude</code></td>
        <td>The latitude of the restaurant</td>
    </tr>
    <tr>
        <td><code>Restaurant_longitude</code></td>
        <td>The longitude of the restaurant</td>
    </tr>
    <tr>
        <td><code>Delivery_location_latitude</code></td>
        <td>The latitude of the delivery location</td>
    </tr>
    <tr>
        <td><code>Delivery_location_longitude</code></td>
        <td>The longitude of the delivery location</td>
    </tr>
    <tr>
        <td><code>Type_of_order</code></td>
        <td>The type of meal ordered by the customer</td>
    </tr>
    <tr>
        <td><code>Type_of_vehicle</code></td>
        <td>The type of vehicle the delivery partner rides</td>
    </tr>
    <tr>
        <td><code>Time_taken(min)</code></td>
        <td>The time taken by the delivery partner to complete the order</td>
    </tr>
  </table>
</p>

<hr>

<h1>04. <a href=""https://github.com/UTSAVS26/Machine-Learning-40-Projects/tree/main/04%20Time%20Series%20Forecasting%20with%20Arima">Time Series Forecasting using ARIMA</a></h1>

<p>
  <h2>Overview</h2>
  <p>In my recent endeavor, I delved into the intriguing world of time series forecasting using the ARIMA model. Time series forecasting allows us to predict future data points based on historical patterns, unlocking valuable insights for decision-making.</p>
  <h2>ARIMA - What is it?</h2>
  <p>ARIMA (AutoRegressive Integrated Moving Average) is a powerful tool in time series analysis. It combines information from past observations, adjusts for trends, and accounts for seasonality to provide forecasts. Think of it as a reliable guide into what might happen next.</p>
  <h2>Key Steps:</h2>
  <table>
    <tr>
        <td><strong>Data Exploration:</strong></td>
        <td>Uncovered hidden patterns and trends within historical data.</td>
    </tr>
    <tr>
        <td><strong>ARIMA Model Implementation:</strong></td>
        <td>Leveraged the ARIMA model to make predictions.</td>
    </tr>
    <tr>
        <td><strong>Fine-Tuning Parameters:</strong></td>
        <td>Adjusted model parameters for optimal performance.</td>
    </tr>
  </table>
  <h2>Results:</h2>
  <p>The ARIMA model provided valuable insights into future trends, helping me make informed decisions based on data-driven predictions.</p>
</p>

<hr>

<h1>05. <a href="https://github.com/UTSAVS26/Machine-Learning-40-Projects/tree/main/05%20Instagram%20Reach%20Analysis">Instagram Reach Analysis</a></h1>
<p>
  <h2>Project Overview 📈</h2>
  <p>This project focuses on analyzing key Instagram metrics, including:</p>
  <table>
    <tr>
        <th>Metric</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><code>Impressions</code></td>
        <td>Uncover the total reach of a post.</td>
    </tr>
    <tr>
        <td><code>From Home</code></td>
        <td>Explore reach from users' home feeds.</td>
    </tr>
    <tr>
        <td><code>From Hashtags</code></td>
        <td>Examine reach attributed to hashtags.</td>
    </tr>
    <tr>
        <td><code>From Explore</code></td>
        <td>Understand reach originating from the Explore page.</td>
    </tr>
    <tr>
        <td><code>From Other</code></td>
        <td>Explore reach from various other sources.</td>
    </tr>
    <tr>
        <td><code>Saves</code></td>
        <td>Measure the number of times the post was saved.</td>
    </tr>
    <tr>
        <td><code>Comments</code></td>
        <td>Evaluate the level of audience interaction.</td>
    </tr>
    <tr>
        <td><code>Shares</code></td>
        <td>Assess virality through the number of shares.</td>
    </tr>
    <tr>
        <td><code>Likes</code></td>
        <td>Gauge the overall popularity of the post.</td>
    </tr>
    <tr>
        <td><code>Profile Visits</code></td>
        <td>Track the impact on profile visits.</td>
    </tr>
    <tr>
        <td><code>Follows</code></td>
        <td>Count the new followers gained from the post.</td>
    </tr>
  </table>
</p>

<hr>

<h1>06. <a href = "https://github.com/UTSAVS26/Machine-Learning-40-Projects/tree/main/06%20Online%20Payments%20Fraud%20Detection">Online Payments Fraud Detection</a></h1>

<p>
  <h2>Project Overview 📈</h2>
  <p>This project focuses on identifying online payment fraud using machine learning. The dataset used for training the model contains historical information about fraudulent transactions. Below are the key columns in the dataset:</p>
  <table>
    <tr>
        <th>Column</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><code>step</code></td>
        <td>Represents a unit of time where 1 step equals 1 hour</td>
    </tr>
    <tr>
        <td><code>type</code></td>
        <td>Type of online transaction</td>
    </tr>
    <tr>
        <td><code>amount</code></td>
        <td>The amount of the transaction</td>
    </tr>
    <tr>
        <td><code>nameOrig</code></td>
        <td>Customer starting the transaction</td>
    </tr>
    <tr>
        <td><code>oldbalanceOrg</code></td>
        <td>Balance before the transaction</td>
    </tr>
    <tr>
        <td><code>newbalanceOrig</code></td>
        <td>Balance after the transaction</td>
    </tr>
    <tr>
        <td><code>nameDest</code></td>
        <td>Recipient of the transaction</td>
    </tr>
    <tr>
        <td><code>oldbalanceDest</code></td>
        <td>Initial balance of recipient before the transaction</td>
    </tr>
    <tr>
        <td><code>newbalanceDest</code></td>
        <td>New balance of recipient after the transaction</td>
    </tr>
    <tr>
        <td><code>isFraud</code></td>
        <td>Fraud transaction</td>
    </tr>
  </table>
  <p>You can download the dataset from <a href="https://drive.google.com/file/d/1TPZBey_a4IqZn-sp7tfd78hNhAjIb3LG/view?usp=drive_link">here</a>.</p>
</p>

<hr>

<h1>07. <a href = "https://github.com/UTSAVS26/Machine-Learning-40-Projects/tree/main/07%20Website%20Traffic%20Forecasting">Forecasting Website Traffic</a></h1>

<p>
  <h2>Project Overview 📈</h2>
  <p>In this project, we aim to enhance business preparedness by forecasting website traffic through the analysis of a year's worth of daily data, including the date and total views. By leveraging historical patterns, we seek to provide insights that enable proactive marketing strategies to address anticipated fluctuations in website traffic. Below are the key columns in the dataset:</p>
  <table>
    <tr>
        <th>Column</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><code>Date</code></td>
        <td>Date of the record</td>
    </tr>
    <tr>
        <td><code>Views</code></td>
        <td>Total number of views in the day</td>
    </tr>
  </table>
</p>

<hr>
