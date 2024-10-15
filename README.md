# 🎯 Kickstarter Startups Analysis (2009-2017)

This project focuses on analyzing data from over **375,000 crowdfunding projects** launched on Kickstarter between **2009 and 2017**. The objective is to explore **trends, performance, and key factors** that contribute to the success or failure of projects across different **categories and countries**.

![Overview](https://github.com/MohamedR4dy/Kickstarter-Analytics-Dashboard/blob/main/Overview.png)

The dataset includes comprehensive information about each project’s name, category, launch and deadline dates, funding goals, pledged amounts, number of backers, and their final status (e.g., successful, failed). This data is critical in understanding the dynamics of crowdfunding and the behavioral patterns of backers across industries and regions.

---

## 📁 **Data Fields and Definitions**
- **ID**: Internal Kickstarter identifier for each project.  
- **Name**: Title of the project.  
- **Category**: Primary category (e.g., Games, Design, Film).  
- **Subcategory**: More specific type within the main category (e.g., Documentary under Film).  
- **Country**: Country where the project was launched.  
- **Launched**: Date when the crowdfunding campaign began.  
- **Deadline**: The end date of the crowdfunding campaign.  
- **Goal**: Funding target set by the creator (in USD).  
- **Pledged**: Actual amount pledged by backers (in USD).  
- **Backers**: Total number of people who backed the project.  
- **State**: The final status of the project (successful, failed, canceled, live, or suspended).  

---

## 📊 **Dashboard Insights and Key Metrics**
The analysis is presented through **interactive dashboards** to provide an in-depth view of trends. Below is a breakdown of the main components in the dashboards:

### 1. **Top-Line Metrics**  
- **Total Projects**: 375K  
- **Total Backers**: 4K  
- **Total Goals**: $17.2 billion  
- **Total Pledged**: $3 billion  
- **Successful Projects**: 134K  
- **Failed Projects**: 198K  

These high-level KPIs give an overview of the platform’s scale and the challenges faced by many startups in reaching their funding goals.

![Slicers Page](https://github.com/MohamedR4dy/Kickstarter-Analytics-Dashboard/blob/main/Slicers%20Page.png)

---

### 2. **Top 10 Projects by Pledged Amount**  
Projects like **Pebble Time** raised $20.3M, followed by **COOLEST COOLER** at $13.3M, demonstrating how tech-related or innovative ideas tend to attract significant backer support.

![Tooltip](https://github.com/MohamedR4dy/Kickstarter-Analytics-Dashboard/blob/main/Tooltip.png)

---

### 3. **Total Projects and Backers by Country**  
The **United States** dominates with **293K projects**, followed by the **United Kingdom (34K)** and **Canada (15K)**.  

Similarly, backers are primarily from the **United States (3.7K)**, with other significant contributors from the **UK (1.2K)** and **Canada (0.8K)**.  

This distribution suggests that certain countries have a more active culture of crowdfunding, with both creators and supporters engaging heavily.

![Backers](https://github.com/MohamedR4dy/Kickstarter-Analytics-Dashboard/blob/main/Backers.png)

---

### 4. **Project Trends Over Time (2009-2017)**  
The number of projects **peaked around 2014-2016**. However, there was a noticeable **drop in the following years**, potentially due to market saturation or shifting trends in crowdfunding.

![Column visual](https://github.com/MohamedR4dy/Kickstarter-Analytics-Dashboard/blob/main/Column%20visual.png)

---

### 5. **Funding Performance by Category**  
Categories such as **Games, Design, Technology, and Film & Video** account for the highest amounts pledged.  

- Projects in **Games** tend to secure large funding but also carry a higher risk of failure.  
- The chart showing **Goals vs. Pledged by Category** highlights discrepancies between ambitious goals and actual backer pledges, helping identify underfunded sectors.

---

### 6. **Project Success Rate by State and Category**  
- **Games and Technology** have the most pledged amount, but also a considerable number of **failed campaigns**.  
- Categories like **Film & Video and Design** show a relatively better success rate.  

This section helps understand what types of projects resonate most with backers and have a higher chance of success.

![Successful Details](https://github.com/MohamedR4dy/Kickstarter-Analytics-Dashboard/blob/main/Successful%20Datails.png)  
![Failed Details](https://github.com/MohamedR4dy/Kickstarter-Analytics-Dashboard/blob/main/Failed%20Datails.png)

---

### 7. **Average Goals and Pledged Amounts by Country and Category**  
- **Austria and Switzerland** lead in terms of average pledged amounts per project, indicating either high-value projects or more generous backers.  
- On the category side, **Technology projects** have the highest average goal, reflecting the capital-intensive nature of product development.

---

### 8. **Sankey Diagram for Project Flows**  
The **Sankey diagram** visualizes successful projects by country, category, and subcategory:  
- The **United States** leads with **109K successful projects**.  
- Popular subcategories include **Music (21K)** and **Film & Video (19K)**.  

This view shows the hierarchical distribution and helps in identifying which countries specialize in specific types of campaigns.

---

### 9. **Backer Engagement Analysis**  
The dashboard includes a **pie chart** to visualize project states (successful, failed, live, canceled, and suspended). The majority of projects are either **successful or failed**, reflecting the binary outcome of most crowdfunding campaigns.

![Tooltip Chart](https://github.com/MohamedR4dy/Kickstarter-Analytics-Dashboard/blob/main/Tooltip%20chart.png)

---

## 📈 **Conclusion and Business Implications**
This project demonstrates how **Kickstarter data** can offer valuable insights into the performance and dynamics of crowdfunding. A few key takeaways:

- **Games and Technology projects** are lucrative but also face higher risks.  
- Creative categories like **Film, Music, and Design** perform well, indicating the backers' inclination towards arts and innovation.  
- The **United States** dominates both in terms of projects launched and backer participation, with other countries following at a distance.  
- Understanding **project goals vs. pledged amounts** helps identify realistic targets for future campaigns.

These insights can assist **startups, investors, and backers** in making **data-driven decisions** when planning or supporting crowdfunding campaigns. Identifying key trends and gaps may also help platform providers and marketers optimize their strategies to increase campaign success rates.

