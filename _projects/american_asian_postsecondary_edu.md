---
name: Postsecondary Education of Asians in the US
tools: [Power BI, HTML, Python]
image: assets/pngs/project.image.png
description: This is a little project about postsecondary education with viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# How is University life for Asians in the US?

As a rising senior, I understand the importance of having access to universities, and I'm looking forward to my undergraduate school life as well. Gradually growing up, I became increasingly curious about how university life would be like.
According to information presented to the public found in NCES and on the Internet, I investigated what university life would be like for Asians. 

In this little project, I collected data and other types of information, which include issues of financial aid, policy, and cultural differences.

# What is Education & How I made this?

I am not good at giving definitions, but as a student, I've developed my relatively superficial insight into the term: education. In my opinion, education should be accessible to all people. I believe that most people should be offered a chance to study.
Therefore, I checked the information on the policy, financial aid, and so on.

What's more, education is not only about learning some skills, but it's about building oneself and future development. Therefore, when investigating the school lives of students, we can't partially focus on their academic performance. 
Instead, paying attention to their mental health is also required, so I also took a look at some research on students' feelings when they're on campus.

Last but not least, education cannot be single-handedly represented by the marks students have gotten; it's a long-term issue. Then I check the information related to students' living situation to see the effect of higher education. 

# Dashboard

<!-- 按钮部分 -->
<!-- 下载按钮部分 -->
<div style="text-align:center; margin:20px 0;">
  <a href="{{ site.baseurl }}/assets/phd_clean.xlsx" download
     style="display:inline-block; padding:10px 20px; background:#0078D7; color:#fff;
            text-decoration:none; border-radius:6px; font-weight:bold;">
     Download The Data
  </a>
</div>




---


<!-- Power BI 报表嵌入 -->
<div style="position:relative; margin:0 auto; max-width:1200px; padding-top:56.25%;">
  <iframe 
    title="phd form"
    src="https://app.powerbigov.us/view?r=eyJrIjoiZGRkZTc2YzAtZTE2ZS00MWIyLTk5YTctNzFiODc5Y2U0ZmU3IiwidCI6Ijg1NTI4ODdjLWNiYzMtNGVlNS05ZmQzLWVhMjE3ZTMwMjZmYyJ9"
    style="position:absolute; top:0; left:0; width:100%; height:100%; border:0;"
    allowfullscreen="true">
  </iframe>
</div>

# Analysis of Data
1. Enrollment Rate and Graduation Rate：
By comparing enrollment and graduation rates among different ethnic groups, we can see that Asian students have the highest enrollment rate. At the same time, their graduation rate within 4–6 years at undergraduate schools is also relatively high.
The high enrollment rate may come from the importance Asian families place on higher education and the relatively strong financial support they can give. The high graduation rate shows that Asian students put emphasis on completing their degrees and also have strong abilities.

2. Financial Aid：
Asian students receive financial aid at a relatively lower rate, but the average amount of aid they get is relatively high.
This shows that the financial situation of Asian families is polarized. Some families have strong financial support and do not rely much on aid, while others depend more on aid and have significant financial needs.

3. Degree Attainment：
The proportion of Asian students who earn bachelor’s and higher degrees is increasing, which shows that Asian students often tend to continue further study, reflecting their pursuit of higher education levels.

4. Income After Graduation：
After finishing undergraduate or higher education, Asian students usually earn a higher median income compared to other groups. Also, there's a positive correlation: the higher the degree, the higher the median income. This shows that for Asian students in the U.S., income after graduation is closely related to education level.

# More Discoveries
1. Policy
   
   According to the US Department of Education, Wikipedia, and other sources of information, it's apparent that several policies have been implemented, offering a better setting for development.
   
   Admissions
   In 2023, the U.S. Supreme Court ended the long-used race-based admission policy（affirmative action） in colleges. This decision was seen as a way to make education more fair. However, legacy admissions (special priority for children of alumni) still preclude true fairness in the admission process.
   Prior research reports—such as the Harvard Kennedy School Working Paper (2023), the IHEP Report “Legacy Admissions: The Unfair Advantage”, and the book "No Longer Separate, Not Yet Equal" by Espenshade and Radford—showed that racial unfairness in admissions lowers the acceptance rates of minority students and greatly reduces their chances to receive higher education. Fortunately, these problems are now being noticed and slowly being improved.

   Supporting Resources
   Some policies focusing on AAPI (Asian American and Pacific Islander) students have been created to support Asian students in higher education. These policies include suggestions on helping immigrant, bilingual, and refugee Asian students, reducing unfair punishment, and improving college preparation support. In addition, the Asian American University Resource Center has been set up to provide substantial help for Asian students in the U.S., encouraging mutual support and a sense of belonging among different Asian groups.

2. Sense of Belonging & Mental Health

   A sense of belonging on campus is closely related to students’ mental health. The higher the sense of belonging, the better their mental health, which then influences their educational outcomes. Therefore, students’ sense of belonging and access to mental health support should be taken seriously.

   For a long time, cultural differences between East and West have been a difficult gap to bridge. Even today, these differences and the stereotypes that come from them still affect Asian students.
   Research has shown that Asian students face cultural barriers when seeking mental health support. They use these services less often, hide their emotions, pay more attention to physical discomfort than psychological problems, and feel shame about mental illness. As a result, they are more likely to experience anxiety and other negative emotions, which harm their studies and daily life.

   At the same time, the “model minority” stereotype continues to put pressure on Asian students. This stereotype ignores their real mental health needs and individual differences, forcing them into the image of being completely self-reliant. In the end, it reduces their willingness to ask for help and further weakens their sense of belonging at school.

   Fortunately, many universities have created Asian American Resource Centers. These centers help ease students’ anxiety and provide important support for a stronger sense of belonging.

# Thoughts

In conclusion, educational fairness in the United States has been improving, and minority students are receiving more support, which offers them better prospects.
Economically, Asian students are gaining more financial aid each year, showing progress in the fairness of economic support.
In terms of policy, new programs and laws continue to help minority students access higher education. However, the fairness of the admission system still needs improvement. The imbalance caused by racial differences goes against the purpose of education. I hope that in the future, through more discussion and effort, the admission process can become fairer.

At the student level, belonging and mental health support are also important. Many universities have created resource centers that give minority students guidance and care. Yet, cultural barriers are not easy to remove. Minority students not only need support within their own groups, but also communication with others. By sharing their ideas, they can reduce misunderstandings about their background. Cultural exchange classes or events, such as festivals, can bring students together, increase their sense of belonging, and improve their mental health.




# Information Sources

- **Data of the Dashboard**: [NCES Current Tables](https://nces.ed.gov/programs/digest/current_tables.asp)

- **Policy of Education**:  
  - [U.S. Department of Education: Higher Education Policy](https://www.ed.gov/laws-and-policy/higher-education-laws-and-policy/higher-education-policy)  
  - [Wikipedia: Legacy Preferences](https://en.wikipedia.org/wiki/Legacy_preferences)  
  - [IHEP Report: Legacy Admissions](https://www.ihep.org/legacy-admissions-report)  
  - [Harvard Kennedy School Working Paper(2023)](https://dash.harvard.edu/handle/1/37371446)

- **Research on Students' Mental Health**:  
  - [Wikipedia: Asian American University Resource Center](https://en.wikipedia.org/wiki/Asian_American_university_resource_center)  
  - [PubMed Article](https://pubmed.ncbi.nlm.nih.gov/36853990/)  
  - [Verywell Mind: Model Minority Myth](https://www.verywellmind.com/what-is-the-model-minority-myth-6259907)

                    


