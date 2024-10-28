# Unstructured-Data-Competitive-Analysis-of-the-luxury-car-market-
In this project, we were tasked with performing a competitive analysis of the entry-level luxury car market in the USA by analyzing social media conversations from Edmunds.com forums.

Our goal was to provide **JD Power and Associates** with actionable insights based on this data. Below is an overview of the steps we took:

### 1. Data Collection (Web Scraping):
- Developed a **Python web scraper** to extract **5,000 posts** from the **Entry Level Luxury Performance Sedans** forum on Edmunds.com.
- Focused on capturing discussions from either the oldest or most recent posts due to changes in the forum structure.

### 2. Testing Zipf’s Law:
- We tested whether the data supported **Zipf’s Law** by plotting the 100 most common words against the law’s theoretical prediction, without removing stopwords or performing stemming/lemmatization.

### 3. Top Brand Identification:
- Created a script to count word frequencies (excluding stopwords) and identified the **top 10 brands** mentioned in the posts.
- Replaced car model mentions with their corresponding brands for simplified analysis.

### 4. Lift Ratio Calculation:
- Calculated **lift ratios** for associations between the top 10 brands, helping us understand how frequently brands were mentioned together in discussions.

### 5. Multi-Dimensional Scaling (MDS) Map:
- Created an **MDS map** to visualize the relative positioning of brands based on their associations, providing insights into competitive proximity.

### 6. Brand Attributes Analysis:
- Identified the **top 5 most frequently mentioned attributes** of cars (e.g., performance, design, price) and analyzed their association with specific brands to understand brand perception.

### 7. Business Insights and Recommendations:
- **Brand Positioning**: Insights on brand associations and competitive positioning.
- **Attribute Alignment**: Advice on focusing marketing efforts on the most relevant attributes for each brand.
- **Aspirational Brand Identification**: Analyzed which brand was most desired by customers, offering strategic insights for business positioning.

### Conclusion:
This project applied **natural language processing**, **statistical analysis**, and **machine learning techniques** (like MDS) to deliver key insights into the entry-level luxury car market. Our analysis provided JD Power and Associates with valuable recommendations to guide their strategy and decision-making.

