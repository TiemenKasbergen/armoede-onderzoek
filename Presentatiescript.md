# Presentation Script – Go/No-go
## Poverty in the Netherlands | Tiemen & Thijs

*Speaking time: approx. 2.5 minutes*

---

### TIEMEN – Introduction & Data (approx. 1 minute)

"Our research is about poverty in the Netherlands. We wanted to quantify it: how big is the problem, for whom, and where?

As our data source we used two CBS tables. The first provides national poverty figures by household type from 2011 to 2024, the second provides provincial figures for 2022. We downloaded the data ourselves from CBS Open Data and loaded it into R.

The data wasn't immediately ready for analysis. We had to filter first: the dataset contains both national and regional rows, so we selected only the national rows. Then we chose the right income threshold, because there are multiple variants. Finally, we had to harmonize the province names, because the map used 'Friesland' while CBS writes 'Fryslân'. That kind of thing only becomes visible when you actually start working with the data.

We also created two new variables. The first is the year-on-year change in poverty, so you can see how quickly it rises or falls. The second is a logical variable indicating whether a province scores above the national average."

---

### THIJS – Visualizations & Conclusion (approx. 1.5 minutes)

"We made four visualizations to analyze the data.

The first is a time series from 2011 to 2024. You can clearly see that poverty peaked in 2013 at almost 9%, and then steadily declined to 3.6% in 2024. That is a massive drop over 10 years.

The second graph breaks that down by household type. And there you see a big difference: single-parent households are structurally much higher than other types. In 2013 that was at 21%, while couples with children were only at 4 to 5%. That difference matters for policy.

The third visualization is a map of the Netherlands. It shows that South Holland and Groningen have the highest poverty rates, which is likely due to the large cities in those provinces. Zeeland and Drenthe score the lowest.

Finally, we looked at the impact of COVID-19. What stands out is that poverty continued to fall after 2020, despite the economic shock. The average before was 8%, after 5.8%. That is probably explained by government support, such as the NOW-scheme for wage subsidies.

Our conclusion is that poverty in the Netherlands has declined significantly, but not equally fast for everyone. Single-parent households and single-person households remain vulnerable. In the rest of our research, we want to dig deeper into this and also look for causal relationships."

---

*Tip: practice it once out loud — that will get the timing right.*
