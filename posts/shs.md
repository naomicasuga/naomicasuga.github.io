---
layout: page
title: Senior High School Enrollment Analysis 2016-2021
---

<p>In recent years, changes in the basic education curriculum of the Philippines happened due to the implementation of the K to 12 Program. This meant that on top of kindergarten, six years of elementary education, and four years of (Junior) High School, students are now required to study two more years of Senior High School (SHS). The program was implemented for the Philippines to follow the global standard of 13 years of basic education. Students can choose their own strands in SHS and in S.Y. 2016-2017, the first batch to undergo SHS started Grade 11.</p>
<p>The dataset used, “Historical Enrollment Senior High School (Public, Private and SUCsLUCs) SY 2010-2011 to 2020-2021”, is from the Department of Education. A sample table is shown below.</p>
<p><img src="{{ 'assets/images/shs/shs1.jpg' | absolute_url }}" alt="" height="auto" width="1000" /></p>
<p>This was transformed to the dataset below for better analysis.</p>
<p><img src="{{ 'assets/images/shs/shs2.jpg' | absolute_url }}" alt="" height="auto" width="auto" /></p>

<hr class="major" />

<h3>Exploratory Data Analysis</h3>
<p><img src="{{ 'assets/images/shs/shs3.jpg' | absolute_url }}" alt="" height="auto" width="700" /></p>
<p>Power BI was used to explore the data. The first chart shown above shows the total number of Senior High School students enrolled per year. Those enrolled in 2016-2017 are significantly lesser than the succeeding years since this only comprises the Grade 11 population. The number almost doubled in 2017-2018 since this includes both Grades 11 and 12. It also seems like in 2020, the pandemic did not really affect the number of enrollees.</p>
<p><img src="{{ 'assets/images/shs/shs4.jpg' | absolute_url }}" alt="" height="auto" width="700" /></p>
<p>Looking further into the enrollees per grade level, there are more Grade 11 than Grade 12 students per year. It could also be noted that, except for 2018-2019, all years have lesser Grade 12 students than the Grade 11 students in the year before. For example, there are 1.10M Grade 11 in 2016-2017 but only 0.92M Grade 12 students enrolled in 2017-2018. It seems like some students stopped studying and did not enroll in Grade 12.</p>
<p><img src="{{ 'assets/images/shs/shs5.jpg' | absolute_url }}" alt="" height="auto" width="700" /></p>
<p>Next, we will look into the gender of the SHS students. Females enrolled are the majority in all school years. This is despite the 2020 data from the Philippine Statistics Authority that 52% of the overall population are male.</p>
<p><img src="{{ 'assets/images/shs/shs6.jpg' | absolute_url }}" alt="" height="auto" width="700" /></p>
<p>The chart above shows that majority of the students enroll in public schools, followed by private, and lastly State Universities and Colleges (SUC) / Local Universities and Colleges (LUC). Public school students are in an upward trend unlike private and SUCs/LUCs students which are in a constant range from 2017-2018.</p>
<p>It is important to note that DepEd offers vouchers for those who graduated from public JHS continuing their studies in a private SHS to assist them financially. It seems that the amount of the subsidy is not enough to cover the costs of studying in a private school since most still prefer studying in a public school. Aside from the tuition fees, another factor that could affect this number is the presence or number of schools in an area.</p>
<p><img src="{{ 'assets/images/shs/shs7.jpg' | absolute_url }}" alt="" height="auto" width="700" /></p>
<p>Next is the comparison of total number of students enrolled per region per year. NCR has the majority of students from 2016-2018. However, in 2018-2021, there were more enrollees in Region IV-A (CALABARZON).</p>
<p><img src="{{ 'assets/images/shs/shs8.jpg' | absolute_url }}" alt="" height="auto" width="700" /></p>
<p>Lastly, here are the Top 5 strands based on overall population per year. For reference, here are the tracks offered in different schools:</p>
<ol>
  <li>Academic Track
    <ul>
      <li>Accountancy, Business and Management (ABM)</li>
      <li>Science, Technology, Engineering, and Mathematics (STEM) </li>
      <li>Humanities and Social Science (HUMSS)</li>
      <li>General Academic Strand (GAS)</li>
    </ul>
  </li>
  <li>Technical-Vocational-Livelihood Track</li>
  <li>Sports Track</li>
  <li>Arts and Design Track</li>
  <li>Maritime Track</li>
</ol>
<p>It is apparent that TVL has the majority of all strands. One of the goals of SHS is to make students job-ready right after graduation. It seems that TVL is the most practical strand since this equips students with skills for them to be eligible to take National Certifications from TESDA and to be able to apply for jobs after.</p>
<p>Academic Tracks fill the rest of the Top 5. Among these, it is interesting to note that HUMSS has been gaining popularity over the years since it is the only one with a clear upward trend.</p>

<hr class="major" />

<h3>Next Steps</h3>
<p>After looking into the enrollment of Senior High School students over the years, it would be interesting to compare these numbers with the following datasets:</p>
<ol>
  <li>Data on schools, their locations, and the strands they offer</li>
  <li>Population per Region specifically the age group of SHS students</li>
  <li>Data on where the students studied in Junior High School</li>
  <li>Data on the students who availed the DepEd voucher</li>
  <li>Data on how many students continued to college or started working after SHS</li>
</ol>

<hr class="major" />

<h3>References</h3>
<p>Department of Education. (n.d.). <i>Datasets.</i> Department of Education. https://www.deped.gov.ph/alternative-learning-system/resources/facts-and-figures/datasets/</p>
<p>Official Gazette. (n.d.). <i>The K to 12 Basic Education Program.</i> Official Gazette of the Republic of the Philippines. https://www.officialgazette.gov.ph/k-12/</p>
<p>Philippine Statistics Authority. (2022, Aug 12). <i>Age and Sex Distribution in the Philippine Population (2020 Census of Population and Housing).</i> Philippine Statistics Authority. https://psa.gov.ph/content/age-and-sex-distribution-philippine-population-2020-census-population-and-housing</p>
