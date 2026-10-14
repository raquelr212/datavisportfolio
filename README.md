# Data Viz Portfolio  
This repository creates a data visualization portfolio. The portfolio was initially created in Dec 2022. The version of R used and packages run were under version R4.2.1. This ReadMe contains a description of each visualization created and its data source(s). 

Repository Structure:

/code

/input

/output


Data can be found in the /input folder. 
Code can be found in the /code folder.
The visualizations can be found in the /output folder. The output can saved as pdfs from the outputs the file in the /code file runs. 

***Part I: English Language learners*** 

Visualization 1: Ratio of English Language Teachers Learners to English Language Learners, by State, 2018-2019

The U.S. Department of Education published data collected on elementary and secondary schools (K-12) in the U.S. on their Ed Data Express website. The data for visualization 1 come from the implementation of Title III, Part A, English Language Acquisition State Grants during the 2018-2019 school year. Data were also collected from the National Center for Education Statistics on the total number of students and total number of teachers per state for the 2018-2019 school year. Visualization 1 plots the percentage of ELL students/total number of students against the percentage of ELL teachers/total number of teachers to illustrate the ratio of ELL students to ELL teachers by state. 


Visualization 2: English Language Proficiency Exam Results for English Learner Students (ELLs) in Massachusetts, 2012-2019

Data for Visualization 2 come from the U.S. Department of Education Ed Data Express website, implementation of Title III, Part A, English Language Acquisition State Grants for the state of Massachusetts for school years from 2012-2019. All students who are English Language Learners (ELLs) in Massachusetts take the state English proficiency exam each year to measure their progress. Each state uses a different exam to measure proficiency, and thus proficiency levels of students across states cannot be directly compared. Within the state however, the measure tracks how many students are making progress, and how many students pass proficiency and thus no longer participate in the English Language Acquisition program. Massachusetts changed their exam in 2015, which resulted in shifts in the scores. Visualization 2 plots those shifts. 

Visualization 3: Average Proportion of English Learner Students (ELLs) in Highest and Lowest Ranking High Schools in Massachusetts, and Statewide, in 2021

The Massachusetts Department of Elementary and Secondary Education publishes data collected on elementary and secondary schools (K-12) in the state on their website. The data for visualization 3 come from enrollment and attendance data for high schools in the state of Massachusetts for the 2021 school year. High school rankings were researched from the U.S. News & World Report and a sample of the top 30 and bottom 30 ranked schools in the state were combined to calculate the average proportion of English Learner students in the highest and lowest ranking schools. Ranking is determined by scores on college readiness, curriculum, state assessment proficiency, state assessment performance, and graduation rates. Statewide, 11% of all students are English Language Learners (ELL). Visualization 3 shows that this average does not hold when broken down by school rank. In the highest ranking schools, on average, ELLs only make up about 1.4% of the student population. In the lowest ranking schools, on average, ELLs make up almost 27% of the student population. The data suggests ELLs disproportionately attend low ranking schools, that perhaps need additional resources to serve them better. 

Visualization 4: Massachusetts Average High School Graduation Rates by School Ranking and English Learner Population, 2021

The Massachusetts Department of Elementary and Secondary Education publishes data collected on elementary and secondary schools (K-12) in the state on their website. The data for Visualization 4 further explore disparities in low and high ranking high schools, focusing on graduation rates, and comes from enrollment and attendance and performance indicator data for high schools in the state of Massachusetts for the 2021 school year. High school rankings were researched from the U.S. News & World Report and data was collected on a sample of the top 15 and bottom 15 ranked schools in the state. Ranking is determined by scores on college readiness, curriculum, state assessment proficiency, state assessment performance, and graduation rates. Overall, the visual suggests ELLs graduate at similar rates to their non-ELL peers. High ranking schools have similar graduation rates (near 100%), whereas low ranking schools have variation in their graduation rates. Only 5 out of the top 15 ranked schools in the state had greater than 0% ELLs in the student body in 2021. The five high schools are grouped in the top right corner, with graduation rates of nearly 100% for both ELL and all students. Among the low ranked schools, the percentage of ELLs in the student body does not seem to impact graduation rates, as Springfield and Boston Arts are both in the bottom 30 in terms of rankings, have a student body of around 10% ELLs, but have vastly different graduation rates with Springfield near 20% and Boston Arts above 80%. This variation suggests there are likely other unexplored factors, besides the % of ELLs in the student body among high schools that are low ranking that impact graduation rates.

***Part II: Refugee Resettlement Models***

For visuals 5-9, I use data from my graduate thesis project, which evaluates the efficacy of refugee resettlement models by comparing employment outcomes at the state level in the United States from 2005-2019. Data are collected from the Department of Health and Human Services Office of Refugee Resettlement (ORR) annual reports to congress, in which they report on indicators from the Annual Survey of Refugees. For the full dataset, I also compiled data from various other sources, including demographic data from the United States Census Bureau’s American Community Survey, transportation data from the Bureau of Transportation Statistics, unemployment rates from the Bureau of Labor Statistics, and welfare spending data from the Urban Brookings Tax Policy Institute. 

There were two resettlement models used by states: the traditional model and the Wilson/Fish model. The traditional model, established in 1980 and used by the majority of states, offers newly resettled refugees services through a variety of agencies and departments, or multiple providers. The Wilson/Fish model, established in 1984, presents an alternative, integrated, “one stop shop” approach where resettled refugees receive all services and assistance from a single provider. In the traditional model, funding streams go to specific agencies and departments for specific purposes (e.g., refugee health or job training). In the Wilson/Fish model, all funding goes to the single provider, and use of funds is more flexible. The final difference between the two models I will highlight is that Wilson/Fish has an explicit emphasis on early employment, while the traditional model does not. Both models ultimately have the goal of self-sufficiency for resettled refugees. I hypothesize that the integrated Wilson/Fish approach leads to higher employment outcomes. Twelve states and San Diego County employ the Wilson/Fish model. In the visuals, I investigate whether the data support my hypothesis. 

Visualization 5: Demographics: Racial Makeup of State Populations by Refugee Resettlement Model Type, 2013-2018

The following visual takes the averages of the racial groups in each state from pooled five year U.S. Census Bureau American Community Survey estimates and merges them into one average for Wilson/Fish states and one average for traditional resettlement states. Race is one demographic factor I explored using as a control in my thesis regression model. From the visual, there appears to be a difference in the racial makeup of state populations between Wilson/Fish and non-Wilson/Fish states. Wilson/Fish states are whiter and less diverse on average. This may have implications for employment among refugees as it may be easier or harder for refugees to integrate and gain employment in states with different racial landscapes. American Indian and Alaska Natives made up such small proportions of each sample that I added them to the Other Race category for simplicity. 

Visualization 6: San Diego Wilson/Fish Program Outperforms California Traditional State Refugee Resettlement Program on Employment Outcomes, on Average, 2005-2019

This visual compares San Diego County, which uses the Wilson/Fish model of resettlement, to the entire state of California, which follows the traditional model. The visual highlights the four outcomes of interest in my thesis study: percent of refugees employed, percent of refugees terminating cash assistance, percent of refugees in jobs offering health benefits, and percent of refugees retaining their jobs after an initial 90 days. On all four outcomes, San Diego outperforms California, on average. The percentages are based on the total number of refugees seeking employment in each program and averaged by program across the 15 year time period of 2005-2019.  

Visualization 7a: Between 2005-2019, only two states (LA and TN) shifted from Traditional to Wilson/Fish resettlement models 

The visual shows which states operate Wilson/Fish throughout the years of interest, 2005-2019. It highlights the 12 states, plus San Diego County, who use Wilson/Fish, and shows the majority of them have been operating the model for the entire time period. The visual shows little change in model type among states in the years 2005-2019. However, two states, Louisiana and Tennessee, did shift to Wilson/Fish from traditional models during the time period. No states shifted from Wilson/Fish to traditional. 

Visualization 7b: The Wilson/Fish Model Yields Higher Job Retention Rates for Refugees in Tennessee than the Traditional Model

Tennessee became a Wilson/Fish state in 2010. From 2005-2009, it followed a traditional model of refugee resettlement. The visual density plot shows what happened to the percentage of refugees retaining their jobs after 90 days following the shift to the Wilson/Fish model. For the traditional model years, the plot shows an average of about 20% of the TN refugee caseload retaining their jobs after an initial 90 days. After shifting to Wilson/Fish, the average bumps up to about 50% of the TN refugee caseload retaining their jobs after an initial 90 days. The data and visual suggest shifting to the Wilson/Fish model led to higher levels of job retention among refugees in the state. 

Visualization 8: Comparative State and Refugee Employment Rates in Wilson/Fish and Traditional States, 2005-2018

In this visual, I compare state employment rates to refugee employment rates based on resettlement model type. It shows state employment rates are higher than refugee employment rates, or that refugees are a less employed group overall. However, it also shows little to no difference in state employment rates among traditional and Wilson/Fish states, and clear difference between refugee employment rates in traditional and Wilson/Fish states. In the final year of data, 2018, average state employment rates were 95.5% in Wilson/Fish states and 95.7% in traditional states. This is a .02 percentage point difference. However, refugee employment rates were 15 percentage points higher (70% to 55%), on average, in Wilson/Fish states than in traditional model states. This indicates there is noteworthy difference between Wilson/Fish and traditional model states impacting refugee employment, that is not accounted for in state employment/unemployment rates.

Visualization 9: Non-Wilson/Fish states resettle the majority of refugees and tend to have higher caseloads of refugees seeking work

This visual explores actual number of refugee caseloads in each state, from 2005-2019, aggregated and grouped by resettlement model type. It offers one explanation for why Wilson/Fish states may have better outcomes than traditional states since they consistently have a much smaller caseload of refugees to work with. Wilson/Fish states make up about 25% of all states but only work with 8-14% of the total caseload of refugees seeking work. 
