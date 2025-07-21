# unemppercovideunl_eda
An EDA based on World Bank's unemployment statistics and Our World in Data's COVID-19 database between 2020 and 2023. Narrowed down to the Europe and the Netherlands. This project specifically examines a derived metric: unemployment per excess death, which reflects how economic disruption (in terms of unemployment) compares to the human toll of the pandemic.

I have narrowed down this EDA to the European Union and the Netherlands in particular, as these regions align with my academic and professional interests. For this project, I used Pandas for data cleaning and manipulation, and Matplotlib / Seaborn for visualizing trends through line charts and heatmaps. Additionally, I built an interactive Power BI dashboard to allow dynamic filtering by country and year.

The metric "unemployment per excess death" provides a lens through which we can compare how intensely countries were economically affected relative to the number of excess deaths they recorded. A higher value may suggest greater economic impact per death, while a lower value might imply less economic disruption per fatality. However, it is important to note that this metric does not establish causation, but rather offers a comparative perspective.

Throughout this analysis, countries like Germany and France displayed moderate ratios with relative stability, while Luxembourg stood out with a notably high value in 2020, and Denmark showed a negative value, likely due to data irregularities or anomalies in excess death reporting. The Netherlands, in particular, showed a steady decline in the unemployment per excess death ratio year-over-year, indicating recovery and adaptation over time.

Visualizations and the dashboard can be found at "visualizations-&-dashboard" branch, reports can be found in "essays" branch, datasets used can be found at "data" branch and the notebook I used can be found at the "notebook" branch.

**Resources**

Data sources: The Economist (2024)World Health Organization (2025)Population based on various sources (2024) – with major processing by Our World in Data


[Unemployment, total (% of total labor force) - World Bank](https://data.worldbank.org/indicator/SL.UEM.TOTL.ZS)

 

