</span>


<br />
<p align="center">
  <a href="https://github.com/kanitmann/hackathon_readme_template">
    <img src="https://cdn-icons-png.flaticon.com/512/1535/1535791.png" alt="Logo" width="90" height="90">
  </a> 

  <h1 align="center">Maximum Revenue for Cab Drivers</h1>
  <p align = "center"> Exploratory Data Analysis, Python, Descriptive analysis, Hypothesis testing</p>
<h3 align="left">PROBLEM STATEMENT</h3><p align="justify">In the fast-paced taxi booking sector, making the most of revenue is essential for long-term success and driver happiness. Our goal is to use data-driven insights to maximise revenue streams for taxi drivers in order to meet this need. Our research aims to determine whether payment methods have an impact on fare pricing by focusing on the relationship between payment type and fare amount.</p>


  <h3 align="left">RESEARCH QUESTION</h3><h4 align="justify">Is there a relationship between total fare amount and payment type? Can we nudge customers towards payment methods that generate higher revenue for drivers, without negatively impacting customer experience?</h4>

<details open="open">
  <summary><h2 style="display: inline-block">Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">Data overview</a>
    </li>
    <li>
      <a href="#about-the-project">Methodology</a>
      <ul>
        <li><a href="#about-the-project">Descriptive analysis</a></li>
        <li><a href="#about-the-project">Hypothesis testing</a></li>
      </ul>
    </li>
    <li>
      <a href="#about-the-project">Journey Insights </a>
    </li>
    <li><a href="#about-the-project">Recommendations</a></li>
  </ol>
</details>
<h3>DATA OVERVIEW</h3>

<b>VendorID</b>: A unique identifier for the taxi vendor or service provider.

<b>tpep_pickup_datetime</b>: The date and time when the passenger was picked up.

<b>tpep_dropoff_datetime</b>: The date and time when the passenger was dropped off.

<b>passenger_count</b>: The number of passengers in the taxi.

<b>trip_distance</b>: The total distance of the trip in miles or kilometers.

<b>RatecodeID</b>: The rate code assigned to the trip, representing fare types.

<b>store_and_fwd_flag</b>: Indicates whether the trip data was stored locally and then forwarded later (Y/N).

<b></b>PULocationID: The unique identifier for the pickup location (zone or area).

<b></b>DOLocationID: The unique identifier for the drop-off location (zone or area).

<b></b>payment_type: The method of payment used by the passenger (e.g., cash, card).

<b>fare_amount</b>: The base fare for the trip.

<b>extra</b>: Additional charges applied during the trip (e.g., night surcharge).

<b>mta_tax</b>: The tax imposed by the Metropolitan Transportation Authority.

<b>tip_amount</b>: The tip given to the driver, if applicable.

<b>tolls_amount</b>: The total amount of tolls charged during the trip.

<b>improvement_surcharge</b>: A surcharge imposed for the improvement of services.

<b>total_amount</b>: The total fare amount, including all charges and surcharges.

<b>congestion_surcharg</b>: An additional charge for trips taken during high traffic congestion times.

<h3>PASSENGER COUNT ANALYSIS</h3>
<img src="Figure 1 (1).png" alt="Logo">
<li><a>Among card payments, rides with a single passenger (passenger_count = 1) comprise the largest proportion, constituting 40.08% of all card transactions.</a></li>
<li><a>Similarly, cash payments are predominantly associated with single-passenger ride, making up 20.04% of all cash transactions.</a></li>
<li><a> There is a noticeable decrease in the percentage of transactions as the passenger count increases, suggesting that larger groups are less likely to use taxis or may opt for alternative payments methods.</a> </li>
<li><a>These insights emphasize the importance of considering both payment method and passenger count when analyzing transaction data, as they provide valuable insights into customer behavior and preferences.</a></li>

<h3>JOURNEY INSIGHTS</h3>
<img src="Figure 1.png" alt="Logo">
<li><a>Fig 1. shows customers paying with cards tend to have a slightly higher average trip distance and fare amount compared to those paying the cash.</a></li>
<li><a>Fig 2. indicates that customer prefers to pay more with cards when they have high fare amount and long trip distance.</a></li>
<li><a>Fig 3. indicates a strong preferences among customers for using card payments over cash, potentially due to convenience, security, or incentives offered for card transactions.</a></li>

<h3>HYPOTHESIS TESTING</h3>
<img src="Figure 1 (2).png" alt="Logo">
<li>Null Hypothesis: There is no difference in average fare between customers who use credit cards and customers who use cash.</li>
<li>Alternate Hypothesis: There is a difference in average fare between customers who use credit cards and customers who use cash.</li>
<h4>With a T-statistic of 165.5 and a P-value of less than 0.05, we reject the null hypothesis, suggesting that there is indeed a significant difference in average fare between the two payment methods. Hence, the alternate hypothesis is correct since the p-value is less than 0.05</h4>



<h3>RECOMMENDATIONS</h3>
<li>
  <a>Implement strategies such as offering incentives or discounts for credit card transactions to incentivize customers to choose this payment method.</a>
</li>
<li>
  <a>Provide seamless and secure credit card payment options to enhance customer convenience and encourage adoption of this preferred payment method.</a>
</li>
<li>
  <a>Encourage customers to pay with credit cards to capitalize on the potential for generating more revenue for taxi can drivers.</a>
</li>

### Built With

- [Python 🐍](https://www.python.org/)
- [Googe colab 🔥](https://colab.research.google.com/)
- [Love 💝](https://en.wikipedia.org/wiki/Love)
- [Chai ☕](https://en.wikipedia.org/wiki/Masala_chai)





   


## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Open it in Google colab.
2. Download the data from this place.  (`git checkout -b feature/AmazingFeature`)
3. Run the notebook (`git commit -m 'Add some AmazingFeature'`)


> Made by Disha 🙋‍♀️⚡!


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[product-screenshot]: (images/screenshot.png)
