![Getting Started](./dashboard.jpeg)
<a name="readme-top"></a>

<div align="center">
  <h1><b>Transborder Freight Data Analyst</b></h1>
</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [Project Description ](#Transborder Freight-Analysis-)
  - [🛠 Built with ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
  - [Key Insights ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
  - [👥 Authors ](#-authors-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

<!-- PROJECT DESCRIPTION -->

# Transborder Freight Data Analysis <a name="about-project"></a>

**Transborder Freight Data Analysis:** Transportation systems are the foundation of modern economies, playing a crucial role in commerce, tourism, and everyday living by facilitating the efficient movement of goods, services, and people. However, as these systems expand and become more intricate, they face growing challenges, such as:

- **Safety concerns** (e.g., accidents and fatalities).
- **Congestion** (leading to delays and economic inefficiencies).
- **Infrastructure stress** (aging systems unable to meet rising demand).
- **Environmental impacts** (e.g., greenhouse gas emissions).
- **Economic disruptions** (e.g., supply chain delays affecting productivity).

The Bureau of Transportation Statistics (BTS) collects and maintains comprehensive data across multiple transportation modes—road, rail, air, and water. This data includes metrics like passenger travel, freight movement, safety incidents, infrastructure capacity, and environmental impacts. These insights are critical for policymakers, transportation agencies, and businesses to design strategies that address inefficiencies, improve safety, and enhance sustainability.


### Data Understanding
1. **TRDTYPE**: Trade Type Code
2. **USASTATE**: USA State 
3. **DEPE**: Port/District Code
4. **DISAGMOT**: Mode of Transportation Code
5. **MEXSTATE**: Mexico State 
6. **CANPROV**: Canada Province
7. **COUNTRY**: Transborder Country Code
8. **VALUE**: Value of goods in US Dollars
9. **SHIPWT**: Shipping Weight in Kilograms
10. **FREIGHT_CHARGES**: Freight Charges in US Dollars
11. **DF**: Domestic/Foreign Code
12. **CONTCODE**: Container Code
13. **MONTH**: Month of the year
14. **YEAR**: Year of Transportation
15. **COMMODITY2**: Commodity Classification Code


## 🛠 Built With <a name="Technologies Used"></a>
The Transborder Freight Data Analysis using the 2020-2024 Bureau of Transportation Statistics(BTS) datasets was done following the CRISP-DM process. It also involved a variety of technologies, programming languages, and libraries to process, analyze, and visualize the data. The following tools were utilized:
1. _Python_: Python programming language was the backbone of the project, used for data processing, analysis, and visualization tasks. The python version used was Python 3.13.1
2. _Pandas_ and NumPy: Pandas and NumPy libraries were essential for data manipulation and numerical computations.
3. _Matplotlib and Seaborn_: Matplotlib and Seaborn were employed for data visualization, creating insightful charts and graphs to represent the findings.
4. _Plotly_: The plotly library was used for more advanced visualisations like the Tree Map
5. _Visual Studio Code and Jupyter Notebooks_: Jupyter Notebooks within the Visual Studio IDE provided an interactive environment for running code, visualizing data, and documenting the analysis process.
7. _Scikit-learn_: Scikit-learn's library SimpleImputer was utilized for imputing null values in the some column.
8. _PowerBI_: The Power BI is a Business Intelligence tool used for creating the dashboard for visualising the findings of my analysis to the stakeholders.
9. _Git and GitHub_: GitHub served as the version control system for the project, enabling collaboration and tracking changes in the codebase.
    These technologies played a crucial role in the successful implementation of the project, providing the necessary tools to analyze and derive insights from the Indian Startup Ecosystem funding datasets.

<details>
  <summary>Data Sources</summary>
  <p>The data for this project was a very complex one sourced from different locations. The data consists 2020 to 2024 datasets collected from the US Bureau of Transportation Statistics (BTS) available in a zip file. The dataset is grouped yearly and each year put in a separate folder. The 2020 and the 2024 folder contains datasets for the months from January to September and the remaining year contains datasets from January to December.For every month of the datasets contains minimum of 6 individual csv files, namely: dot_1, dot_2, dot_3, dot1_ytd, dot2_ytd and dot3_ytd. The ytd datasets are comulative datasets of the months from January to the month in focus.</p>
</details>


<details>
<summary>Language</summary>
  <ul>
    <li><a href="">Python</a></li>
  </ul>
</details>


<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- Features -->

## Success Criteria <a name="key-features"></a>
The success of the project will be determined by:

- **Insights Generated:** Delivering actionable insights that address the BTS’s challenges and objectives.
- **Stakeholder Satisfaction:** Meeting or exceeding the expectations of the BTS and other stakeholders.
- **Impact on Decision-Making:** Enabling data-driven strategies that lead to measurable improvements in transportation systems.
- **Feasibility of Recommendations:** Providing realistic and implementable recommendations that can be executed within existing constraints.


## Key Insights <a name="key-Insights"></a>
The analysis of the BTS Data Analysis using the 2020-2024 datasets has yielded valuable insights into understanding freight patterns, volume, costs and environmental impacts within the US Transport Sector. Based on the EDA and visualizations conducted, the following key findings and conclusions have been drawn:
1. _Freight Volumes Over the 5 years_:
   - It was observed that the value of goods transported across the borders of Mexico seems to rise from 2020 and peaked in 2022 where it began to sink until 2023 when there is a sharp increase in the value of goods.
   - The goods transported across the Canadian borders also increased until 2023 when it has been declining since the year 2023. 

2. _Total Freight Charges Across Borders_:
   - From my analysis, the Canadian border has had an overall increase in freight charges over the years as compared to the Mexico border.
   Freight charges significantly impact the US economy by directly influencing the cost of goods and services for consumers, affecting inflation levels, impacting business competitiveness, and ultimately influencing the overall economic growth by determining the efficiency of goods movement across the country; higher freight charges can lead to increased costs for businesses, potentially reducing production and investment, while efficient freight systems can facilitate faster delivery times and lower overall costs, boosting economic activity
3. _Transborder Volume By Mode of Transportation_:
   - The analysis revealed that the pipeline transportation is the leading mode of transport transporting both  liquid and gas products over the years across the transborder countries. The insights drawn from this analysis indicates how significant the pipeline system has on the USA economy and should be strengh
   - The maturity and proven track record of older startu
1. _Investor Preferences_:
   - Investors showed a preference for sectors with high growth potential and proven market demand, aligning their funding decisions with industry trends and market dynamics.
   - Understanding investor preferences and sector trends can help startups tailor their pitches and strategies to attract funding effectively.
1. _Strategic Implications_:
   - The findings suggest that startups in underfunded sectors or regions may need to focus on differentiation, innovation, and networking to attract investment.
   - Startups at earlier stages should emphasize building credibility, market validation, and scalability to increase their attractiveness to potential investors.



<p align="right">(<a href="#readme-top">back to top</a>)</p>

![image](https://github.com/adubrightkwartengsnr/Indian_Startup_Ecosystem_Analysis_2018-2021)




<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Python


### Setup

Clone this repository to your desired folder:


```sh
  cd my-folder
  git clone https://github.com/adubrightkwartengsnr/Indian_Startup_Ecosystem_Analysis_2018-2021
```

Change into the cloned repository

```sh
  cd Indian_Startup_Ecosystem_Analysis_2018-2021
  
```

Create a virtual environment

```sh

python -m venv env

```

Activate the virtual environment

```sh
    env/Scripts/activate
```


### Install

Here, you need to recursively install the packages in the `requirements.txt` file using the command below 

```sh
   pip install -r requirements.txt
```


<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

🕵🏽‍♀️ **Bright Adu Kwarteng Snr**

- GitHub: [GitHub Profile](https://github.com/adubrightkwartengsnr)
- LinkedIn: [LinkedIn Profile](www.linkedin.com/in/bright-adu-kwarteng-snr)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

While the analysis of the Indian Startup Ecosystem using the 2018-2021 funding datasets has provided valuable insights through data cleaning, EDA, visualizations, univariate analysis and dashboarding, there are several areas for potential future work and improvements to enhance the depth and scope of the analysis:
1. _Machine Learning Integration_:
   - Incorporating machine learning models could offer predictive capabilities, such as forecasting funding trends, identifying startup success factors, or building recommendation systems for investors.
   - Machine learning algorithms could be applied to classify startups into different categories based on funding potential or success likelihood.
1. _Advanced Data Analysis Techniques_:
   - Exploring advanced statistical analysis methods, such as regression analysis, cluster analysis, or time series forecasting, could provide deeper insights into the factors influencing funding outcomes.
   - Leveraging advanced data mining techniques to uncover hidden patterns, anomalies, or correlations within the datasets could reveal additional actionable insights.
1. _Real-Time Data Integration_:
   - Integrating real-time data sources and APIs could enable continuous monitoring of funding activities, market trends, and startup performance, allowing for dynamic and up-to-date analysis.
   - Implementing automated data pipelines for data ingestion, cleaning, and analysis could streamline the process and ensure the analysis is always based on the latest information.
1. _Interactive Dashboards_:
   - Developing interactive dashboards and data visualization tools could enhance the accessibility and usability of the analysis results, enabling stakeholders to explore the data and insights in a user-friendly manner.
   - Incorporating drill-down capabilities, filters, and interactive elements in the visualizations could empower users to conduct ad-hoc analysis and derive customized insights.
1. _Collaborative Research Opportunities_:
   - Collaborating with domain experts, industry professionals, or academic researchers could provide additional perspectives, domain knowledge, and validation of the analysis findings.
   - Engaging in cross-disciplinary research projects or partnerships could lead to innovative insights and solutions for addressing challenges within the startup ecosystem.

By considering these potential future work areas and improvements, the analysis of the Indian Startup Ecosystem can be further enhanced, leading to more comprehensive, actionable, and impactful insights based on the 2018-2021 funding datasets.

  
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to express my sincere gratitude to my instructors Racheal Appiah-Kubi and Violette Naa Adoley Allotey for their exceptional guidance, unwavering support, and invaluable mentorship throughout the course of this project. Their expertise, dedication, and commitment to our learning journey have been instrumental in shaping our understanding and skills in data analysis.

I would also like to extend a special thank you to Solomon Nyamson for his valuable advice and insights shared during the development of this project. His experiences and expertise in similar projects have been a source of inspiration and guidance, enriching our project with practical knowledge.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<p> align="right">(<a href="https://medium.com/@adubrightkwarrteng11/exploring-the-indian-startup-ecosystem-a-data-driven-analysis-of-funding-trends-and-industry-c200428666c1">Link to Article</a>)</p>



