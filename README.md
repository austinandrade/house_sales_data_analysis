<a name="readme-top"></a>

[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/austinandrade/house_sales_data_analysis">
    <img src="images/house.svg" alt="Home" width="140" height="140">
  </a>

<h3 align="center">House Sales Data Analysis</h3>

  <p align="center">
    This project involves analyzing house sales data from King County, Washington, to predict past and future trends in the housing market. Utilizing a dataset from Kaggle, the data was reformatted with pandas for               manipulation and analysis and then visualized using Tableau to draw insightful conclusions and predictions.
    <br />
    <br />
    <a href="https://public.tableau.com/views/HouseSalesViz_17139744908580/KingCountyHouseSales?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link">View Interactive Dashboard</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#insights">Insights</a></li>
        <li><a href="#reccomendations">Reccomendations</a></li>
        <li><a href="#project-outcomes">Project Outcomes</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This data analysis project explores house sales data from King County, Washington. The primary goal is to apply statistical and predictive analysis techniques to understand historical trends and forecast future movements in the housing market.

The dataset, sourced from Kaggle, comprises comprehensive details on house sales, including prices, lot sizes, number of bedrooms, bathrooms, and other relevant attributes. This dataset provides a rich foundation for conducting detailed exploratory data analysis and predictive modeling.

The analysis began with data cleaning and preprocessing to handle missing values, outliers, and incorrect data types. Descriptive statistics provided initial insights into the central tendencies and dispersions within the data.

Predictive models were developed to forecast future prices and assess the impact of various features on house values. The project also explored seasonal trends, price distributions by geographic locations, and the influence of house features like waterfront views and home condition on sale prices.

![tableau-preview](/images/tableau_preview.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- INSIGHTS -->
## Insights

### 1. Descriptive Statistics
The average sale price of a house is approximately $540,088. The average home has 3 bedrooms, 2.5 bathrooms, and an average living space of around 2,080 square feet. Bathrooms and above-ground square feet show strong positive correlations with price, which is typical as these factors contribute to a home's overall space and functionality.

![bedrooms-histogram](/images/bedrooms_insight.png)

![bathrooms-histogram](/images/bathrooms_insight.png)



### 2. Special Features
Homes with waterfront views have a significantly higher average price ($1.66 million) than those without ($531.5 thousand). This feature is a significant price booster alongside the home's overall condition.

![view-vs-condition heatmap](/images/heatmap.png)

### 3. Expensive Zip Codes
Zipcodes like 98039, 98004, and 98040 are among the highest in average prices, indicating affluent areas that could be targeted for luxury home sales or investments.

![map-insights](/images/map_insights.png)


### 4. Monthly Price Trends
The data shows seasonal variations in average prices, with peaks around April and May 2015. This suggests that late spring is possibly the best time to sell for higher prices.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Reccomendations -->
## Reccomendations

### Home Buyers

#### 1. Prioritize Established High-Value Areas
Consider purchasing in zip codes like 98039 (Medina), 98004 (Bellevue), and 98040 (Mercer Island), which consistently show the highest average prices. These areas are known for their affluent communities and strong school districts.
#### 2. Look for Growth Opportunities
For those looking for potentially rising areas, zip codes such as 98112 (Capitol Hill/Madrona) and 98102 (Eastlake) have shown substantial appreciation while still being relatively more affordable than the top-tier zip codes.

---

### Investors

#### 1. Invest in High-Demand Areas
Focus investments in 98039, 98004, and 98040, which have high property values and stability in those values, indicating a safe, high-return investment.
Also, properties in areas like 98112 and 98102 should be considered for diversification, which could capture a different market segment that might yield high returns due to increasing demand.

#### 2. Waterfront Properties
Properties with waterfront views or access have shown significantly higher values, especially in areas like 98118 (Seward Park) or along the Lake Washington and Puget Sound shorelines. These rare properties tend to appreciate faster than those without waterfront access.

---

### Real Estate Agents/Sellers

#### 1. Effective Listing Strategies
When listing properties, highlight key selling points such as views, lot size, and renovations, especially in high-value areas like 98039, 98004, and 98040.
For properties in 98112 and 98102, emphasize community features, proximity to downtown Seattle, and vibrant local amenities, which are big draws.

#### 2. Seasonal Selling
Analyzing the data suggests listing properties around April and May when prices peak due to increased buyer activity. This timing can help maximize sale prices.

#### 3. Renovation Advice
Recommend renovations that align with current trends seen in the data. For example, adding luxury fittings or updating kitchens and bathrooms in older homes in areas like 98004 (Bellevue) can significantly increase the property's market value.

#### 4. Target Marketing 
Focus marketing efforts on houses with large living areas, high-grade constructions, and especially those with waterfront views could yield higher returns.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- PROJECT OUTCOMES -->
## Project Outcomes
The visualizations and models developed have shed light on the critical drivers of house prices in King County and reasonably accurately predicted future market trends. These insights can aid potential home buyers, sellers, and real estate investors in making informed decisions.

This project highlights the practical applications of data analysis in real estate and demonstrates how modern data science techniques can be leveraged to extract meaningful information from large datasets.

## Built With

* [Python](https://www.python.org/)
* [Tableau Public](https://public.tableau.com/)
* [Kaggle](https://www.kaggle.com/)


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Austin Andrade - [Connect with Me](https://www.linkedin.com/in/austinandrade/) - austinmandrade@gmail.com

Project Link: [https://github.com/austinandrade/house_sales_data_analysis](https://github.com/austinandrade/house_sales_data_analysis)



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Dataset](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)
* [pandas - Python Data Analysis Library](https://pandas.pydata.org/)
* [Zipfile36](https://pypi.org/project/zipfile36/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/austinandrade/house_sales_data_analysis.svg?style=for-the-badge
[license-url]: https://github.com/austinandrade/house_sales_data_analysis/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/austinandrade
