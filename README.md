# Deliverables
[presentation.pdf](https://github.com/raguilarsoriano/CapstonePod5/files/10886040/presentation.pdf) | 
[notebook.pdf](https://github.com/raguilarsoriano/CapstonePod5/files/10886789/notebook.pdf)

# Overview
Our team, Fantastic Five, conducted an analysis of several datasets to give insights for Computing Vision, a big movie company, to be better equipped to create original movies. We used python and inferential statistics to come to three recommendations/insights for Computing Vision to utilize. Juan analyzed our first business case, Roberto and Sasha analyzed our second business case, and Jordan and Mercedez analyzed our third business case. Our recommendations will hopefully enable Computing Vision to create effective original films and stay atop the movie industry!

In the Files above, you can find links to our presentation PDF to Computing Vision, our Jupyter Notebook (live and PDF) containing our analysis/code, our exploratory Jupyter Notebooks, and our datasets. Below in this README is a summary of each of our sections of our final analysis.

# Business Understanding
Computing Vision, a major movie company, has seen other big companies create original films. They have created a new movie studio to do the same. However, they do not have much experience or background in creating original films. Our team, Fanastic Five, have analyzed movie data to provide Computing Vision with business recommendations and insights that their stakeholders can leverage to create effective original films and stay on top of the movie industry.

# Data Understanding & Analysis
We are using the im.db and tn.movie_budgets.csv datasets in our analysis. These datasets provide us extensive and useful data that can derive insights that are helpful to Computing Vision. A major limitation of our analysis was time, as our datasets were very large and we did not have as much time as we would have liked to clean and amalyze the data.

Business Recommendation #1:
We conducted an analysis to determine the most profitable genre of movies to create. Based on our analysis, the adventure genre generates the highest profitibility.

![image](https://user-images.githubusercontent.com/125094602/222841706-02b4b454-008c-4c7c-9e5e-977724a049cd.png)

Business Recommendation #2:
We conducted an analysis to determine the amount of budget to use to increase revenue. Based on our analysis, bigger budgets did not translate to higher revenue.

![image](https://user-images.githubusercontent.com/125094602/222847191-b1575a20-a537-4689-9a09-bf6b0690bb06.png)
![image](https://user-images.githubusercontent.com/125094602/222847223-16cc666d-4faf-4aec-916d-f78591dafb07.png)

Business Recommendation #3:
We conducted an analysis to determine a release season that would yield more profitibility. Based on our findings, release season did not affect movie profitability. However, the Spring & Summer seasons yield higher gross worldwide profits.

![image](https://user-images.githubusercontent.com/125094602/222847638-da743bc4-45c6-42f5-9f75-2c2ddebe9120.png)
![image](https://user-images.githubusercontent.com/125094602/222847662-24f36345-6d7d-4c0a-9c5f-e31f8a7e8adc.png)
![image](https://user-images.githubusercontent.com/125094602/222847691-095bbbc2-3f3f-471f-aeba-c2e17219dc1b.png)
![image](https://user-images.githubusercontent.com/125094602/222847726-8c266f98-12b9-48ab-90a0-bc3e3471d74f.png)

# Statistical Communication
Our null hypothesis stated that there is no difference between the seasonal release date and gross worldwide profits.
Our alternative Hypothesis stated that there is a difference between the seasonal release date and gross worldwide profits, the sample mean for gross worldwide profits is higher in the Spring & Summer seasons than Fall & Winter seasons.
We conducted a one-tailed Z-Test, with a significance level of 0.05 (95% confidence) that gross worldwide profits are higher during Spring & Summer. The Z-Score is 1.50, p-value is 0.065, putting movies released in Spring & Summer in the 93.94th percentile.
We fail to reject the null hypothesis, and therefore we cannot recommend a specific season to release movies. We speculate that Spring & Summer movie releases will lead to higher gross worlwide profits.

![image](https://user-images.githubusercontent.com/125094602/222848046-5a86ccd5-63eb-4e20-927f-212e3a4ce38d.png)

# Conclusion
Our concluding recommendations for Computing Vision is for them to create their movies in the adventure genre, to consider other factors than bigger budget to increase revenue, and to keep in mind that Spring & Summer seasons yield higher gross worldwide profits. We derived these insights from analyzing extensive and useful datasets through python and statistic tests. A limitation that prevented us from analyzing our datasets fully was the lack of time.
