Project Overview: The Rise and Rise of AI Large Language Models (LLMs)
This project visualizes the explosive growth of Large Language Models (LLMs) using data from Makeover Monday / Information is Beautiful. The Tableau dashboard combines trend analysis, ranking charts, and interactive filters to explore how model sizes have scaled, which companies lead the race, and how long organizations have been investing in LLM development. Custom calculated fields were created to measure years invested, identify the largest models, and enable parameter-driven interactivity.

Objective
Analyze the scaling trend of LLMs (2018–2025).


Compare organizations by largest LLM released, years invested, and total models.


Provide business insights into competitive dynamics between established leaders (Google, OpenAI, Baidu) and emerging startups (Mistral AI, Adept).



Project Components
1. Data Extraction
Source: Makeover Monday public dataset on LLMs.


Extracted fields: name, owner, trained on x billion parameters, date, notes, link.


Imported as Excel into Tableau for direct connection.



2. Data Design
Reformatted date into year for trend analysis.


Cleaned and grouped company names so they are consistent


Created calculated fields to support analysis:


Years Invested → computed from min/max release dates per owner.


Rank Parameters by Owner → unique ranking of owners by model size.


Name of Biggest LLM → identifies top models dynamically using FIXED LOD.


Range of Parameters → difference between min/max per owner.


Is Selected Owner → parameter-driven highlight for interactivity.



3. Data Analysis
Model Size Trend → Scatter/line chart showing exponential parameter growth over time.


Owner Ranking by Largest LLM → Bar chart ranking companies by their biggest released model.


Owner Ranking by Years Invested → Bar chart showing years of sustained LLM activity.


Enabled interactive filters for owners, allowing deeper exploration.



4. Business Insights
Exponential scaling: Model sizes skyrocketed post-2021, showing acceleration in AI investment.


Market leaders: Google, OpenAI, and Baidu dominate, releasing the largest LLMs.


Emerging disruptors: Startups like Mistral AI and Adept entered recently but are innovating quickly.


Strategic advantage: Early movers (Google, OpenAI) continue to benefit from years of R&D.



Technology Used
Data Source: Makeover Monday / Information is Beautiful dataset.


Data Cleaning & Preparation: Excel (basic cleaning), Tableau calculated fields (advanced transformations).


Visualization: Tableau (trend line, ranking charts, parameter-driven interactivity).



What Did You Learn?
How to use LOD (Level of Detail) expressions in Tableau for dynamic calculations (e.g., biggest LLM per owner, years invested).


That visualization makes technical AI trends understandable to non-technical audiences.


The AI race is highly competitive, with exponential scaling creating new market dynamics.




