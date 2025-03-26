## Airbnb Investment Analysis Project: Best NYC Neighborhood 

### Project Overview

This project conducts an in-depth Exploratory Data Analysis (EDA) of Airbnb listings in New York City to identify the best neighborhood for investing in an apartment to maximize rental earnings. I used Python libraries including Pandas, Numpy, Matplotlib and Seaborn for data cleaning, visualization and comprehensive statistical evaluation.

### Objective

The primary aim of this analysis is to:

- Determine the most profitable neighborhood in NYC for Airbnb hosts.
- Evaluate rental pricing trends and host performance.
- Identify patterns influencing booking frequency and listing profitability.
- Offer actionable insights and investment recommendations based on data findings.

### Dataset

The dataset have over 100,000 Airbnb listings in NYC, featuring key details:

- `id`, `host id`, `host_identity_verified`
- `neighbourhood group`, `neighbourhood`
- Geographic coordinates (`latitude`, `longitude`)
- Pricing details (`price`, `service fee`)
- Guest metrics (`minimum nights`, `number of reviews`, `reviews per month`, `availability 365`)
- Listing specifics (`room type`, `Construction year`, `instant_bookable`, `cancellation_policy`)

### Steps and Workflow

#### 1. Data Cleaning

- Handled missing and inconsistent values.
- Converted monetary fields (`price`, `service fee`) to numerical types.
- Corrected geographic data typos in neighborhoods.
- Managed anomalies (negative availability, excessive minimum nights).

#### 2. Exploratory Data Analysis (EDA)

##### Price Analysis:

- Conducted univariate analysis using histograms and boxplots.
- Identified typical Airbnb prices ($341 - $913) and confirmed symmetry in distribution.

##### Neighborhood Profitability:

- Calculated median price by neighborhood, filtering out neighborhoods with fewer than 100 listings.
- Highlighted neighborhoods with highest median nightly prices.

##### Review Activity:

- Computed average reviews per listing to measure neighborhood demand.
- Identified neighborhoods with highest guest activity, indicating strong demand.

#### 3. Data Visualization

- Histograms and boxplots to illustrate price distribution.
- Bar charts depicting top neighborhoods by median price and review activity.

### Key Findings and Insights

#### Pricing and Profitability:

- **Battery Park City, NoHo, Gravesend, and Briarwood** show the highest median nightly prices, ideal for premium market targeting.

#### Neighborhood Demand:

- **Concourse and Prospect Heights** exhibit high demand and strong pricing, making them attractive for investment.
- **South Ozone Park** offers strong guest activity with lower prices, providing a balanced risk-return profile.

#### Investment Recommendation:

- **Concourse** stands out due to high guest activity (approximately 50 reviews per listing), reasonable property prices ($250,000 - $375,000), and robust market performance, marking it as the best neighborhood for new Airbnb hosts.

### How to Run This Project

Clone the repository:

```bash
git clone https://github.com/eduard240/AirbnbInvestmentAnalysisProject.git
```

Install necessary libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Execute the Jupyter notebook:

```bash
jupyter notebook nyc_airbnb_investment_analysis.ipynb
```

### Recommendations

#### For Investors/Hosts:

- Prioritize neighborhoods with strong market activity and reasonable entry costs (ex: Concourse).
- Balance between nightly price potential and guest activity levels.
- Maintain competitive pricing aligned with neighborhood median values.
- Focus on guest experience and responsiveness to maintain high reviews and visibility.

### Future Work

- Integrate predictive modeling to forecast rental income based on historical data.
- Create dynamic dashboards using Plotly or Tableau for continuous performance monitoring.

### Conclusion

This comprehensive analysis identifies Concourse as an optimal NYC neighborhood for Airbnb investment, balancing affordability, guest demand and profitability. Insights provided will assist investors in making data-driven decisions to maximize returns.

### Contact

For any queries, reach out via:

- **LinkedIn**: [Profile](https://www.linkedin.com/in/eduard-alexandru-kasaj-6217ab296/)
