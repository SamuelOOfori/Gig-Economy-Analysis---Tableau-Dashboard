# Gig_Economy_Analysis-Tableau-Dashboard
#### This is a Gig Economy Analysis framed in Figma and visualised using Tableau (<a href="https://public.tableau.com/app/profile/samuel.ofori2139/viz/GigEconomyDashboard/ExecutiveView?publish=yes" target="_blank">Click to interact on Tableau Public<a/>)
---
## Introduction
The Gig economy, built around short-term, flexible, and freelance jobs instead of traditional, long-term employment is a key feature of the digital labor market. As a work model, the gig economy offers workers flexibility and autonomy, while giving businesses cost-effective access to talent and services when they need them. This analysis is aimed at providing insights into this market across 5 different geographical areas, aiming to provide information to both freelancers and businesses that patronise their services across these platforms: Fiverr; General Freelancers; PeoplePerHour; Totptal; and Upwork. Data for the visualisation was sourced from two sources, obtained from 10Alytics:
<ol>
  <li> Freelancer Details Data </li>
  <p>
        <details><summary>📂<emphasis>Data Dictionary</emphasis>  </summary>
        <ol>
          <li>Freelance_ID </li>
          <li>Job Category [Type of freelance work done]</li>
          <li>Platform [Online Platform for Freelancing]</li>
          <li>Experience Level [Experience level of Freelancer] </li>
          <li> Client Region</li>
          <li>Payment Method</li>
        </ol>
      </details>
  </p>
  <li> Job & Earning Data </li>
  <p>
    <details><summary> 📂 <emphasis> Data Dictionary</emphasis></summary>
      <ol>
          <li>Freelance_ID </li>
          <li>Job Completed [Number of Jobs Successfully Completed] </li>
          <li> Earnings ($) </li>
          <li> Hourly Rate ($) </li>
          <li> Job Success Rate </li>
          <li> Client Rating </li>
          <li> Job Duration_Days </li>
          <li> Rehire Rate </li>  
          <li> Marketing Spend [Amount spent on marketing ($)]</li>
        </ol>
    </details>
  </p>
</ol>

## Problem Statement

The Gig economy has grown rapidly since the dawn of the internet, broadening access to talent for businesses and work oppotunities for professionals. Freelancers and businesses nonetheless often struggle to predict job success rates across platforms, demand for certain skills, factors for success and often the most reliable platforms for freelancing. This has called for data-driven insights to forecast freelancer job trends and earnings, to which this analysis sought to answer. 

## Rationale for Project

This analysis in its attempt to answer the call for data-driven insights within this field aimed to: 
<ol>
  <li>Analyse freelancer job trends;</li>
  <li>Assess freelancer earnings;</li>
  <li>Identify key success factors;</li>
  <li>Provide a geographic overview of the Gig economy.</li>   
</ol>

## Project Plan 
The project was executed in six(6) steps spanning three tools: Microsoft Excel, Figma and Tableau. 
<ol>
  <li> First step involved a assessment of the Gig economy and the nature of this economy across contexts. This step largely involved reading articles and publications related to the subject matter to identify key parameters relevant in this field </li>
  <li>Next step involved data exploration to identify strengths and shortcomings of the data, followed by data cleaning and transformation in Microsoft Excel </li>
  <li>Next, the data importated into Tableau with necessary assigment of data types to ensure uniformity and coherence in analysis. A join was then initiated at the physcial level using the Freelance ID as the primary key </li>
  <li> Relevant charts were next enivsaged (planned) with relevant KPIs selected and then created in Tableau </li>
  <li> A wireframe for the visualisation was then created in Figma using the visualisation plan created in the previous step. The dashboard was sectioned into an executive and geographic view</li>
  <li> The dashboard was finally built in Tableau with key insights gleaned and drafted into a PowerPoint presentation </li>
</ol>

## Wireframe in Figma 
Taking advantage of the flexibility offered by designing in Figma, I desined my dashboard first in Figma then imported into Tableau. 
<img src="WireFrame - Gig Eco. Dashboard.png"> 
<details> <summary> 📂 Each page is here for those interested </summary>
  <img src="Sheet 1 Final.png">
  <img src="Sheet 2.png">
</details>

## Dashboard 
The dashboard has two views, the Executive View and the Geographic View.
<ol>
  <li> The Executive View captures key insights about the data including the number of freelancers, the median job rates, the distribution of earnings across job types and experience, the job success ratings and the number of jobs completed.
    <img src="Exec. View.png">
  </li>
  <li> The Geographic View focuses on presenting an overview marketing expenditure for freelancers and the relationship with earnings, as well as the nature of the rehire rate across the geographic distribution of the data
  <img src="Geographic View.png"
  </li>
</ol>

## Analysis and Key Insights
There are 1950 freelancers within the dataset with clients spanning USA, Australia, Canada, Middle East, United Kingdom and other parts of Europe. These freelancers have completed a total of 294K jobs for an average earnings of $5,000. A deep dive into the data is presented below: 
### Earnings Analysis 
Earnings tend to be data points that often exhibit a high level of variability. Although the variability in the data is relatively small, as the median and mean are quite similar, the median was employed for a more reliable analysis when the data is drilled down. In cases where the median was very similar across the variables, the average was employed to explore possible differences. The earnings analysis showed that: 
<ol>
  <li>
    The median earnings across the freelancers was $5K at a median rate of $52.29/hr.
  </li>
  <li> 
    The job type that earned freelancers the most was <i> Application Development </i> at $5.2K whiles <i> Search Engine Optimisation </i> earned the least at $4.2K and had the least amount earned for a job at $51. It is however worth noting that at a similar of average of $5.1K, <i>Graphic Design</i> has a higher lower earn as compared to <i>Customer Support</i>,  and <i>Digital Marketing</i>
  </li>
  <li>
   Hourly rate for jobs sat between $99/hr and $5/hr, with the latter found only within the intermediate experienced freelancers. Interestly, beginners had the highest hourly rate at $8/hr. Median hourly rate and experience showed an interesting relationship based on the platform where freelancers worked. The analysis showed that regardless of experience, freelancers on <i>PeoplePerHour</i> were in the top two for high hourly rates. Totptal on the other hand had a majorly low hourly rate for <i>Beginners</i> and <i>Intermediate</i> freelancers. For <i>Beginners</i>, <i>Fiver</i> seemed most favorable for higher hourly rates whiles <i>PeoplePerHour</i> provided a higher average hourly rate for <i>Experts</i>. For intermediately experienced freelancers, <i>Upwork</i> provides a larger means for earning at a higher hourly rate, almost as high as the maximum average hourly rate for <i>Experts</i>, as compared to the other platforms. 
  </li>
</ol>

### Job Success Rate Analysis (Distribution shown as tooltip on dashboard)
The analysis showed that <i> Graphic Design</i> were most likely to be completed successfully as compared to <i> Web Development </i> with the least likehood of completion averagely. With over 39K <i>Graphic Design</i> jobs completed, over 64% of the jobs were successfully completed at 70%-90% completion status as was quite similar with <i>Data Entry</i> jobs. <i>Web Development </i> jobs were however found to often be left halfway done. Although <i>App Development</i> averagely earned the most, such jobs are often left halfway done as well. A phenomenon most likely due to the lower than the general median earnings for such jobs.

### Marketing Expenditure Analysis
Spending more on marketing was identified as not directly related to earning more for freelancers. Whiles location did matter in the outcome for spending on marketing themselves as freelancers, such expenditure in most cases did not yield high earnings. In Australia as the largest market with the highest median marketing expenditure, where over 47K jobs were executed, the highest marketing expenditure of $495 on marketing yielded the Graphic Design freelancer about $7.9K in earnings as compared to the highest earner who earned $9.96K from Digital Marketing. It is however significant to mention that the Graphic Design freelancer worked less jobs at a much higher rate on <i>Upwork</i> as compared to the Digital Marketer on <i>Fiverr</i>. This therefore is a clear outlier as the median earnings and hourly rate for Graphic Design on Upwork is much lower than that for the freelancer of interest. In Asia however, the freelancer with the highest marketing expenditure had a earnings within the 10th percentile although they did not sit among the top two earners within the region. In Canada, where the lowest median marketing expenditure is observed, the top two spenders on marketing made quite high earnings whereas the third highest observed a loss of over $100. Clearly, the success of marketing expenditure, with respect to translating into earnings goes beyond the magnitude of the expenditure.  

### Platform + Location Based Analysis 
<i>Upwork</i> was identified as the platform with the most freelancers, having completed over 61K jobs at a average rate of $53.48/hr, earning over $5K in revenue. Averagely, freelancers with intermediate experience get the best hourly rate on <i>Upwork</i> whiles Application Development made the most earnings. Although freelancers <i>Toptal</i> completed a similar amount of jobs as those on <i>Upwork</i>, the platform completed them with a lower number of freelancers. Unlike <i>Upwork</i>, Toptal has the highest median hourly rate for freelancers with <i>Expert</i> level of experience. Despite having the lowest number of freelancers, <i>PeoplePerHour</i> has a higher median rate of $55.60/hr, with freelancers with <i>Beginner</i> earning close to this amount. While <i>Expert</i> level freelancers earn the most per hour averagely, <i>Graphic Designers</i> have earned the most on this platform. The top two jobs however with the highest job success rates are <i>Applica Develoment and Data Entry</i>. 

Australia as mentioned had a total of over 47K jobs completed across 298 freelancers. With an expected average of 44days for a job from clients in this region and a rehire rate at about 45% with an average success rate of 75.5%. The average rating in the region nonetheless is 4 out of 5 stars. Although jobs from customers in the UK had the lowest success rate of just about 73.9%, clients from here are more likely to rehire freelancers although that rarely happens as well (46.4%). Similarly, jobs from the UK tend to often last about 44days and the average rating is 4 out of 5 stars. The clients in the United States however averagely score the freelancers 4.1 out of 5 stars with an average success rate of 75.2% across jobs. Across all geogeaphic areas, the least customer rating for top earning freelancers was 3 out of 5 stars. 

## Final Words
The Gig Economy, like every other market requires relevant information for stakeholders to make relevant decisions in order to thrive, survive and earn. The analysis shows varied possibilities for freelancers across different platforms and client regions. As freelancers, it is relevant to prioritise job completion and a proper selection of platforms based on the level of experience as well as choice of jobs sought in order the make the most out of this market and the platforms. Spending on marketing does not guarantee increased earnings, improved skill and great service delivery however show consistent gains for freelancers.

<a href="https://public.tableau.com/app/profile/samuel.ofori2139/vizzes" target="_blank"> You can access other visualisations of mine on Tableau Public (click here) </a>. 
