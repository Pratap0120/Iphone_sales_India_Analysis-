# 📱 iPhone Sales - Data Analysis on Flipkart

## 🔍 Overview
This project analyzes iPhones available on Flipkart in India, focusing on various metrics such as ratings, reviews, sale prices, and discount percentages. By leveraging Python libraries, this analysis provides insights into consumer behavior, market trends, and sales patterns in the Indian iPhone market.

## 🛠 Tools and Libraries
- **Python**: The primary programming language used for data analysis and visualization.
- **Pandas**: Used for data manipulation and processing.
- **NumPy**: Helps with numerical computations for statistical analysis.
- **Plotly**: For creating interactive and visually appealing plots and graphs.
- **Matplotlib**: For static visualizations (e.g., bar charts, line graphs).
- **Seaborn**: For generating more aesthetic and informative statistical plots.

## 📊 Dataset
- **Source**: The dataset, `apple_products.csv`, contains information on various iPhone models listed on Flipkart, including sale price, ratings, reviews, and discount percentages.
- **Data Integrity**: 
  - The dataset was cleaned for missing values, and any missing data points were imputed or dropped to ensure accurate analysis.
  - Duplicates and irrelevant data were filtered out to improve analysis quality.

## 🔑 Key Findings
### 1. **Top 10 Highest-Rated iPhones**
The analysis identified the top 10 highest-rated iPhones. Ratings and reviews were visualized using bar charts, showcasing consumer preferences.

- **Chart**: Top 10 Highest-Rated iPhones by Average Rating & Reviews
- **Insights**: iPhones with high ratings also tend to receive a higher number of reviews, indicating strong consumer feedback.

### 2. **Price vs. Rating Correlation**
Exploring the relationship between sale prices and ratings revealed a **negative correlation**:
- **Observation**: As the price increases, the number of ratings tends to decrease, suggesting that consumers prefer more affordable models over the expensive ones. 
- **Chart**: Scatter plot showing Sale Price vs. Ratings with trend line.

### 3. **Cheapest and Most Expensive iPhones**
The dataset highlighted significant price differences in the iPhone models listed on Flipkart:
- **Cheapest iPhone**: 
  - **Model**: APPLE iPhone SE (Black, White, 64 GB)
  - **Price**: ₹29,999
- **Most Expensive iPhone**:
  - **Model**: APPLE iPhone 12 Pro (Pacific Blue, Silver, 512 GB)
  - **Price**: ₹140,900

### 4. **Discount Analysis**
- **Insight**: There was a direct correlation between high discounts and low sale prices. iPhones with large discounts were typically positioned at a lower price point compared to models with smaller discounts.
- **Chart**: Histogram showing the distribution of discount percentages vs. sale prices.

### 5. **Rating Distribution**
The rating distribution analysis shows that most iPhone models received ratings between 4 and 5 stars. A small percentage of products had low ratings, which could indicate issues such as product defects or consumer dissatisfaction.

- **Chart**: Distribution of Ratings for all iPhone Models.

### 6. **Review Sentiment Analysis (Optional)**  
- **Sentiment Analysis**: Analyzing the reviews of iPhone models using natural language processing (NLP) techniques, I categorized reviews into positive, neutral, and negative sentiments.
- **Chart**: Sentiment distribution for iPhone reviews.
  
## 📈 Visualizations
- **Bar Chart**: Top 10 Highest Rated iPhones
- **Scatter Plot**: Price vs. Rating Correlation
- **Box Plot**: Price Distribution of iPhone Models
- **Histogram**: Discount Percentage Distribution

## 🧑‍💻 Code Implementation Highlights
The analysis was carried out using Python, with the following steps:
1. **Data Import**: The dataset was imported using `pandas`.
2. **Data Cleaning**: Checked for missing values and duplicates, and performed necessary cleaning and transformation.
3. **Exploratory Data Analysis (EDA)**: Utilized `plotly` and `seaborn` to generate interactive and static visualizations.
4. **Sentiment Analysis (Optional)**: Used `TextBlob` or `VADER` for analyzing the sentiment of reviews.

## 🚀 Next Steps
- **Deepen the Analysis**: Implement machine learning models to predict iPhone prices based on features like ratings, sale price, and discount percentages.
- **Deployment**: Build an interactive dashboard using **Streamlit** or **Dash** for a more user-friendly experience.
- **Price Prediction Model**: Train a regression model to predict future iPhone prices based on historical data.

## 🔗 Connect With Me
- **GitHub**: [github.com/Pratap0120](https://github.com/Pratap0120)
- **LinkedIn**: [linkedin.com/in/pratap12](https://www.linkedin.com/in/pratap12)
- **Email**: pratappawar.work@gmail.com

---

Feel free to explore the analysis and share your thoughts! 💬
