### Retail Price Optimization using Python and Machine Learning





#### What is Retail Price Optimization?

Optimizing retail prices means finding the perfect balance between the price you charge for your products and the number of products you can sell at that price.

The ultimate aim is to charge a price that helps you make the most money and attracts enough customers to buy your products.

It involves using data and pricing strategies to find the right price that maximizes your sales and profits while keeping customers happy.









#### Project Retail Price Optimization:

This solution applies machine learning to historical sales, promotions, inventory, product attributes, and competitor pricing to produce data-driven price recommendations. By performing exploratory analysis and estimating demand elasticity, the system forecasts sales at alternative price points, evaluates profit and volume trade-offs, and proposes constraint-aware prices that maximize margin while preserving competitiveness. It also supports competitor benchmarking, scenario simulation, and A/B testing to validate recommendations and enable safe, measurable rollout.







#### 📂 Dataset

The dataset used contains:



Product identifiers and categories

Pricing metrics: unit\_price, total\_price, freight\_price, comp\_1, comp\_2, comp\_3

Product attributes: score, weight, photo count, etc.

Time data: month\_year, weekday, holiday

Customer data: number of buyers, ratings, etc







#### 🧪 Technologies Used

Python

Pandas for data manipulation

Plotly Express \& Graph Objects for interactive visualizations

Scikit-learn for modeling and evaluation

Streamlit for deployment







#### 🔍 Exploratory Data Analysis (EDA)

Visualizations include:



Distribution of total and unit prices

Scatter plot of qty vs total\_price (linear trend)

Box plots by weekday and holiday

Correlation heatmap of numerical features

Average competitor price difference by category







#### 📌 Project Highlights

Cleaned and explored 676 rows x 30 columns retail dataset

Engineered features to capture competitor pricing dynamics

Visualized key pricing behaviors and trends

Built an ML model to predict optimized retail prices

Deployed live on Streamlit for interactive exploration

