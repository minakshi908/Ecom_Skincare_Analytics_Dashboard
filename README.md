# Ecom_Skincare_Analytics_Dashboard
An intermediate Power BI data analytics dashboard processing 611K rows of e-commerce transactions using a Star Schema relational model and custom DAX metrics.
🚀 Project Showcase: Building an E-Commerce Skincare & Beauty Analytics Dashboard for 611K Reviews! 📊

I am excited to share my latest data analyst project: a full, interactive dashboard built using a dataset of over 611,000+ skincare and cosmetic customer reviews! 

Instead of just looking at raw spreadsheets, I wanted to build a clean visual tool that helps store managers make smart business decisions about their stock and pricing instantly.

🛠️ The 5 Charts on My Screen:
1️⃣ The KPI Number Card: Uses a custom DAX formula (COUNTROWS) to scan our database and flash the total scale—611,000 reviews loaded smoothly.
2️⃣ Product Category Chart: A vertical bar chart showing that Skincare completely dominates customer traffic compared to items like Tools or Fragrances.
3️⃣ Brand Donut Wheel: A colorful circular chart displaying how store revenue is split across hundreds of different beauty brands.
4️⃣ Top Brand Leaderboard: A clean table grid displaying a scrolling list of our top-performing brands right next to their total reviews.
5️⃣ Pricing Analytics Chart: A column chart tracking financial trends by calculating the Average Price (USD) of items in each category.

🏗️ What I Did Behind the Scenes (The Technical Part):
• Data Modeling: I connected a product detail table (Dimension) to a massive transaction log table (Fact) using a clean 1-to-Many relationship so all my dashboard filters flow smoothly without lagging.
• Data Cleaning: Used Power Query to clean up dirty data columns, override format errors, and delete bad rows so the dashboard calculations stay 100% accurate.

💡 Smart Business Conclusions:
• Skincare is our absolute champion: It commands the highest number of customer sales and holds our highest average price point. We should shift more marketing budget here!
• The "Blank" Data Leak: I caught a specific bar labeled (Blank) on my chart. This reveals that the team is uploading products without tagging their categories. My recommendation is to add a mandatory field to fix this data gap immediately.



#DataAnalytics #PowerBI #SQL #DAX #BusinessIntelligence #DataModeling #DataEngineering #AnalyticsDashboard #PortfolioBuild #TechCareers
