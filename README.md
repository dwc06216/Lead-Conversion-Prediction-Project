# Lead-Conversion-Prediction-Project

## 📚 Project Overview

This project focuses on lead conversion prediction for **ExtraaLearn**, an early-stage EdTech startup offering upskilling programs to students and professionals. Given the increasing volume of leads generated through multiple digital channels, the goal is to help ExtraaLearn:

- Predict which leads are more likely to convert into paying customers
- Identify key factors driving conversion
- Provide actionable business recommendations for resource allocation

## 🌐 Context

The EdTech sector has grown rapidly in recent years and is projected to reach $286.62 billion by 2023. Especially during and post-COVID-19, online learning platforms have gained a wider user base due to their accessibility, flexibility, and personalization.

ExtraaLearn collects leads via multiple channels such as websites, mobile apps, emails, and advertisements. With limited sales resources, it's critical to identify high-potential leads to optimize outreach and improve conversion rates.

## 🎯 Objectives

- Perform exploratory data analysis (EDA) to uncover key behavioral and demographic insights.
- Build a machine learning model to classify leads based on their likelihood to convert.
- Analyze feature importance to understand which factors most influence conversion.
- Generate business recommendations based on data insights.

## 📁 Dataset Description

The dataset contains lead-related information including demographics, user engagement, and marketing channel exposure.

Key features include:
- `current_occupation`: Student, Professional, or Unemployed
- `first_interaction`: Website or Mobile App
- `profile_completed`: Percentage of profile completion (Low, Medium, High)
- `last_activity`: Email, Website, or Phone interactions
- `print_media`, `digital_media`, `referral`: Lead source flags
- `time_spent_on_website`, `website_visits`, `page_views_per_visit`
- `status`: Whether the lead converted (target variable)

## 📊 Key Findings

### Lead Profile Insights
- **Professionals** have the highest conversion rate.
- **Unemployed** leads convert at a decent rate despite smaller volume.
- **Students** are most frequent but have lower conversion rates.

### Channel Performance
- **Website** interactions lead to significantly better conversion than Mobile App.
- **Referrals** show the highest success rate among all marketing channels.
- **Website activity** (e.g., live chat, profile updates) has the strongest conversion signal.

### Engagement Metrics
- Leads with **Medium to High profile completion** are more likely to convert.
- **Time spent** and **website visits** are positively correlated with conversions.

### Feature Importance (ML)
Top predictors identified by Random Forest:
1. `first_interaction_website`
2. `time_spent_on_website`
3. `profile_completed`
4. `age`
5. `last_activity`
6. `current_occupation`

## ✅ Business Recommendations

- **Lead Prioritization**: Focus on Professionals and Unemployed with high website engagement.
- **Channel Optimization**: Invest more in Website UX and Referral campaigns.
- **Profile Completion Campaigns**: Use gamification, reminders, and rewards.
- **Communication Strategy**: Emphasize email + website engagement over phone.
- **Predictive Scoring**: Use ML models to prioritize leads daily for sales teams.

## 🧠 Technologies Used

- Python (Pandas, NumPy, scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook
- Machine Learning: Decision Tree, Random Forest
- EDA and Visualization

## 📌 Conclusion

By analyzing user engagement and marketing attributes, this project provides a scalable machine learning solution to improve lead conversion targeting. Insights derived here can directly inform ExtraaLearn’s marketing and sales strategies, leading to more efficient resource allocation and higher ROI.

---

## 📈 Future Improvements

- Implement lead scoring in a live dashboard
- Evaluate additional ML models like XGBoost or Logistic Regression
- A/B test strategies based on the recommendations

## 📝 License

This project is for educational and research purposes only.
