# Datacamp Project: Analyzing Students' Mental Health in SQL

![mentalhealth](https://github.com/ffatihf3/Analyzing-Students-Mental-Health-SQL/assets/69224750/aea911d4-9d28-473f-9023-fbff1ff4d3d7)

Brief: In 2018, a Japanese university conducted a comprehensive survey of their diverse student body. The following year, an approved study was published using ethically obtained data from this survey.

The study found that international students have a higher risk of mental health issues than the general population. It also found that social connectedness (feeling part of a social group) and acculturative stress (stress from adapting to a new culture) can predict depression.

This project aims to explore the student data using PostgreSQL to see if length of stay is a contributing factor to mental health for international students, similar to the original study's conclusions.

Results: International students who had been at the university the longest (10 years maximum in the data) scored highest on average for depression according to test results (Avg Score = 13). However, they scored lowest on the Social Connectedness Test (Avg Score = 32). Their acculturative stress scores also ranked in the second lowest position (SCS = 50).

<img width="1091" alt="Screen Shot 2024-05-02 at 11 45 30" src="https://github.com/ffatihf3/Analyzing-Students-Mental-Health-SQL/assets/69224750/a5b44fac-1e91-4b3d-9f08-d06e29cc4674">
<blockquote>Result Table</blockquote>

<img width="1091" alt="Screen Shot 2024-05-02 at 12 00 34" src="https://github.com/ffatihf3/Analyzing-Students-Mental-Health-SQL/assets/69224750/c61ea7cb-ea28-4218-a49d-fe88e06b7c82">
<blockquote>Figure 1: Relationship between length of stay and average depression score (Y-axis: Length of stay in years, X-axis: Total score on PHQ-9 depression test </blockquote>


<img width="1091" alt="Screen Shot 2024-05-02 at 12 00 46" src="https://github.com/ffatihf3/Analyzing-Students-Mental-Health-SQL/assets/69224750/a48a681b-c2ea-4392-894e-70663955e35b">
<blockquote>Figure 2: Relationship between length of stay and social connectedness score (Y-axis: Length of stay in years, X-axis: Total score on SCS social connectedness test)</blockquote>


<img width="1091" alt="Screen Shot 2024-05-02 at 12 00 52" src="https://github.com/ffatihf3/Analyzing-Students-Mental-Health-SQL/assets/69224750/c45b4b3e-9d51-47d4-8342-aa1986bd161e">
<blockquote>Figure 3: Relationship between length of stay and acculturative stress score (Y-axis: Length of stay in years, X-axis: Total score on ASISS acculturative stress test)</blockquote>

This analysis concludes that international students who stay the longest experience increasing depression over time. However, their ability to adapt improves as they gain more experience socializing with local students and communities and familiarizing themselves with the area after longer stays.

To complete the task, I applied the SQL knowledge that I learned previously in this course. I started by understanding the analysis brief and objectives outlined.

Then I connected to the PostgreSQL database and explored the tables and attributes to understand the data structure. To obtain the requested results, I designed and executed several SQL queries to extract data on average depression test scores, social connectedness scores, and acculturative stress scores based on length of stay for international students.

Finnaly, this case study allowed me to practice applying my SQL knowledge and data analyst to analyze a real dataset and provide insights to address the research questions presented.

[Reference](https://www.mdpi.com/2306-5729/4/3/124)
